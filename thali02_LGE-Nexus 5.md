#### Test 584164489c56086_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1699): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1699): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3092): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3092):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3092):   adb logcat -s GAv4
W/GAv4    ( 3092): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3092): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3092): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3092): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2656): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  761): Killing 2458:com.google.android.youtube/u0a80 (adj 15): empty #17
W/ResourcesManager( 3092): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3092): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  761): failed to open /acct/uid_10080/pid_2458/cgroup.procs: No such file or directory
I/ActivityManager(  761): Killing 2104:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 3092): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3092): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3092): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  761): failed to open /acct/uid_10038/pid_2104/cgroup.procs: No such file or directory
V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1699): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1699): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1699): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1699): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3157): 
D/AndroidRuntime( 3157): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3157): CheckJNI is OFF
D/AndroidRuntime( 3157): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3178 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3157): Shutting down VM
V/ActivityManager(  761): Display changed displayId=0
,I/WebViewFactory( 3178): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3178): Time to load native libraries: 2 ms (timestamps 5658-5660)
I/LibraryLoader( 3178): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3178): Binding Chromium to main looper Looper (main, tid 1) {2b25f5c7}
I/LibraryLoader( 3178): Expected native library version number "",actual native library version number ""
I/chromium( 3178): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3178): Initializing chromium process, singleProcess=true
W/art     ( 3178): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3178): ApplicationContext is null in ApplicationStatus
,W/chromium( 3178): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3178): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3178): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3178): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b50f4d9:true
,W/art     ( 3178): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3178): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3178): CordovaWebView is running on device made by: LGE
,W/art     ( 3178): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3178): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3178): Render dirty regions requested: true
,D/Atlas   ( 3178): Validating map...
,W/chromium( 3178): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3178): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3178): Enabling debug mode 0
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +459ms (total +43s23ms)
,W/IInputConnectionWrapper( 3178): showStatusIcon on inactive InputConnection
,W/BindingManager( 3178): Cannot call determinedVisibility() - never saw a connection for the pid: 3178
,D/JsMessageQueue( 3178): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3178): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342080
,I/chromium( 3178): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  761): Killing 2615:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10069/pid_2615/cgroup.procs: No such file or directory
,D/Finsky  ( 2656): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/jxcore-log( 3178): Initializing JXcore engine
,W/jxcore-log( 3178): JXcore engine is ready
I/art     ( 1629): Explicit concurrent mark sweep GC freed 31695(2MB) AllocSpace objects, 25(400KB) LOS objects, 39% free, 21MB/35MB, paused 846us total 54.794ms
,W/Thread-306( 3233): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6572]" dev="sockfs" ino=6572 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-306( 3233): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-306( 3233): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8502]" dev="sockfs" ino=8502 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-306( 3233): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19682]" dev="sockfs" ino=19682 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3178): Starting JXcore engine
,W/jxcore-log( 3178): Platform android
W/jxcore-log( 3178): 
W/jxcore-log( 3178): Process ARCH arm
W/jxcore-log( 3178): 
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3178): JXcore Cordova bridge is ready!
I/jxcore-log( 3178): 
W/jxcore-log( 3178): JXcore engine is started
,I/qtaguid ( 2656): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2656): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2656): untagSocket(37) failed with errno -22
D/Finsky  ( 2656): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  761): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3252 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/jxcore-log( 3178): Toggling radios to true
I/jxcore-log( 3178): 
,D/BluetoothAdapter( 3178): enable(): BT is already enabled..!
,D/WifiService(  761): setWifiEnabled: true pid=3178, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  761): New client listening to asynchronous messages
,I/jxcore-log( 3178): Radios toggled
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): My device name is: LGE-Nexus 5
I/jxcore-log( 3178): 
,I/wpa_supplicant( 1040): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  761): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1629): Read error: ssl=0xb3ca3000: I/O error during system call, Connection timed out
,V/NativeCrypto( 1629): SSL shutdown failed: ssl=0xb3ca3000: I/O error during system call, Broken pipe
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  761): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1040): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  761): do suspend true
,W/Finsky  ( 2656): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: javax.net.ssl.SSLException: Read error: ssl=0xafe8f000: I/O error during system call, Connection timed out
,D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,W/ResourcesManager( 3252): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3252): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524292
D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1699): CM callback handler got msg 524292
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/CommandListener(  179): Clearing all IP addresses on wlan0
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
,D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1240): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
,I/MultiDex( 3252): VM with version 2.1.0 has multidex support
I/MultiDex( 3252): install
I/MultiDex( 3252): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3252): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3252): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3252): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@ffd94d8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3252): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1629): callingUid 10008, callindPid: 1629
,E/MDM     ( 1629): [227] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ChimeraCfgMgr( 3252): Reading stored module config
D/AuthorizationBluetoothService( 1629): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1699): Restart initialization of location
,D/ChimeraCfgMgr( 3252): Loading module com.google.android.gms.car from APK com.google.android.gms
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1629): No location to return for getLastLocation()
W/FusedLocationProvider( 1629): location=null
,D/CAR.SERVICE( 3252): Connecting to CarCallService...
,D/NativeLibraryUtils( 3252): Install completed successfully. count=14 extracted=0
,I/art     ( 3252): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 3252): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 3252): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 3252): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 3252): Creating a new PhoneAdapter instance
,W/ActivityManager(  761): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3252): setListener: com.google.android.gms.car.dn@102a4187
W/ActivityManager(  761): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3252): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3252): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 3252): Package validated; name: com.android.vending
,V/Finsky  ( 2656): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/art     (  761): Explicit concurrent mark sweep GC freed 25881(1239KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.033ms total 91.262ms
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2656): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: org.apache.http.conn.HttpHostConnectException: Connection to https://android.clients.google.com refused
,D/Finsky  ( 2656): [1] DailyHygiene.access$600: Logging device features
,D/Finsky  ( 2656): [1] DailyHygiene.reschedule: Scheduling new run in 92 minutes (failures=3)
,D/DeviceConnectionService( 1629): client connected with version: 8296000
,D/Finsky  ( 2656): [270] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2656): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 2656): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  761): Killing 2567:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_2567/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1040): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1040): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1040): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1040): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  761): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  761): Start Dhcp Watchdog 2
,E/native  (  761): do suspend false
,E/WifiStateMachine(  761): scanCount==0 - aborting
,I/dhcpcd  ( 3330): version 5.5.6 starting
E/dhcpcd  ( 3330): get_duid: Read-only file system
,I/dhcpcd  ( 3330): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3330): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3330): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2751): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1699): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1699): onCreate
,D/SystemUpdateService( 1699): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1699): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1699): active receiver: enabled
,I/iu.UploadsManager( 1699): num queued entries: 0
I/iu.UploadsManager( 1699): num updated entries: 0
I/iu.SyncManager( 1699): NEXT; no task
,I/SystemUpdateService( 1699): showing system update notification
I/Babel   ( 1946): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  761): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3369 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  761): No APN found to select.
,E/GpsLocationProvider(  761): No APN found to select.
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1699): retry (wakeup: false) in 3599930 ms
,D/SystemUpdateService( 1699): onDestroy
,E/native  (  761): do suspend true
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  761): Adding iface wlan0 to network 101
,E/WifiStateMachine(  761): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  761): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  761): Adding Route [fe80::/64 -> :: wlan0] to network 101
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
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  761): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1699): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
,I/GAv4    ( 3369): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3369):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3369):   adb logcat -s GAv4
,W/GAv4    ( 3369): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3369): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3369): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 09:19:57 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455009597392], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455009597372]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Validated
,D/ConnectivityService(  761): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1699): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1240): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WebViewFactory( 3369): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3369): Time to load native libraries: 2 ms (timestamps 1546-1548)
I/LibraryLoader( 3369): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3369): Binding Chromium to main looper Looper (main, tid 1) {13ebe408}
I/LibraryLoader( 3369): Expected native library version number "",actual native library version number ""
I/chromium( 3369): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3369): Initializing chromium process, singleProcess=true
,W/art     ( 3369): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3369): ApplicationContext is null in ApplicationStatus
,W/chromium( 3369): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3369): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3369): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3369): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3369): Requires BLUETOOTH permission
,I/NSApplication( 3369): Starting up...
,I/ActivityManager(  761): Killing 2727:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2727/cgroup.procs: No such file or directory
,I/jxcore-log( 3178): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3178): 
,V/MusicLeanback( 2751): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1699): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1699): onCreate
,D/SystemUpdateService( 1699): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1699): active receiver: enabled
,I/iu.Environment( 1699): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1699): num queued entries: 0
I/iu.UploadsManager( 1699): num updated entries: 0
I/iu.SyncManager( 1699): NEXT; no task
,I/SystemUpdateService( 1699): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1699): retry (wakeup: false) in 3599931 ms
,D/SystemUpdateService( 1699): onDestroy
,I/Babel   ( 1946): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  761): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3178): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3178): 
I/jxcore-log( 3178): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3178): 
,D/CAR.SERVICE( 3252): mConnectedToCar = false, abort
,E/ActivityThread( 3252): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@194d5e25 that was originally bound here
E/ActivityThread( 3252): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@194d5e25 that was originally bound here
E/ActivityThread( 3252): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3252): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3252): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3252): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3252): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3252): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3252): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3252): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3252): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3252): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3252): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3252): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3252): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3252): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3252): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3252): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3252): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3252): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3252): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3252): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3252): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3252): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3252): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3252): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3d96dc6 that was originally bound here
E/ActivityThread( 3252): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3d96dc6 that was originally bound here
E/ActivityThread( 3252): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3252): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3252): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3252): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3252): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3252): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3252): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3252): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3252): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3252): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3252): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3252): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3252): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3252): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3252): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3252): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3252): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3252): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3252): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3252): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3252): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3252): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  761): Unbind failed: could not find connection for android.os.BinderProxy@b504d83
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2751): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2751): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1699): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1699): onCreate
,D/SystemUpdateService( 1699): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1699): active receiver: enabled
,I/SystemUpdateService( 1699): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
,E/GpsLocationProvider(  761): No APN found to select.
,V/SystemUpdateService( 1699): retry (wakeup: false) in 3599983 ms
,D/SystemUpdateService( 1699): onDestroy
,I/jxcore-log( 3178): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): Test app app.js loaded
I/jxcore-log( 3178): 
,I/chromium( 3178): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28a67da2 added. We now have 1 listener(s)
,I/jxcore-log( 3178): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3178): 
,D/Finsky  ( 2656): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2656): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1629): Vacuum at: now=1455009624478 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1629): disconnect managed GoogleApiClient
,I/jxcore-log( 3178): TAP version 13
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # multiplex can send data
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 1 String should be length:200
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # enqueue and run in order
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 2 firstPromise setTimeout
I/jxcore-log( 3178): 
I/jxcore-log( 3178): ok 3 firstPromise result
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 4 firstPromise testValue
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 5 secondPromise setTimeout
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 6 secondPromise result
I/jxcore-log( 3178): 
I/jxcore-log( 3178): ok 7 secondPromise testValue
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 8 thirdPromise in promise
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 9 thirdPromise result
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 10 thirdPromise testValue
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # basic
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 11 sane
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # another
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 12 sane
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 13 should be equal
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 14 null
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 15 (unnamed assert)
I/jxcore-log( 3178): 
I/jxcore-log( 3178): ok 16 should be equal
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 17 should not throw
I/jxcore-log( 3178): 
I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 18 (unnamed assert)
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 19 (unnamed assert)
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 20 should not throw
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 21 should be equal
I/jxcore-log( 3178): 
I/jxcore-log( 3178): ok 22 should be equal
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 23 should be equal
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # failed to get mobile documents path
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 24 should be equal
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 25 should be equal
I/jxcore-log( 3178): 
I/jxcore-log( 3178): ok 26 should be equal
I/jxcore-log( 3178): 
I/jxcore-log( 3178): ok 27 should be equal
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # #init should register the networkChanged event
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 28 should be equal
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # #startBroadcasting should throw on null device name
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 29 should throw
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 30 should throw
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 31 should throw
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 32 should throw
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # #startBroadcasting should throw on negative port
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 33 should throw
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # #startBroadcasting should throw on too large port
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 34 should throw
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 35 should be equal
I/jxcore-log( 3178): 
I/jxcore-log( 3178): ok 36 should be equal
I/jxcore-log( 3178): 
I/jxcore-log( 3178): ok 37 should be equal
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 38 should be equal
I/jxcore-log( 3178): 
I/jxcore-log( 3178): ok 39 should be equal
I/jxcore-log( 3178): 
I/jxcore-log( 3178): ok 40 should be equal
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 41 should be equal
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 42 should be equal
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 43 should be equal
I/jxcore-log( 3178): 
I/jxcore-log( 3178): ok 44 should be equal
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 45 should be equal
I/jxcore-log( 3178): 
I/jxcore-log( 3178): ok 46 should be equal
I/jxcore-log( 3178): 
I/jxcore-log( 3178): ok 47 should be equal
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 48 should be equal
I/jxcore-log( 3178): 
I/jxcore-log( 3178): ok 49 should be equal
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 50 should be equal
I/jxcore-log( 3178): 
I/jxcore-log( 3178): ok 51 should be equal
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 52 should be equal
I/jxcore-log( 3178): 
I/jxcore-log( 3178): ok 53 should be equal
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # #start should fail if called twice in a row
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 54 specific error should be received
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # #startListeningForAdvertisements should fail if start not called
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 55 specific error should be returned
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # should be able to call #stopListeningForAdvertisements many times
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 56 error should be null
I/jxcore-log( 3178): 
I/jxcore-log( 3178): ok 57 error should be null
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # should be able to call #startListeningForAdvertisements many times
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 58 error should be null
I/jxcore-log( 3178): 
I/jxcore-log( 3178): ok 59 error should be null
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # should be able to call #startUpdateAdvertisingAndListening many times
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 60 error should be null
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 61 error should be null
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # #startUpdateAdvertisingAndListening should fail if start not called
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): ok 62 specific error should be returned
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # teardown
I/jxcore-log( 3178): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16770a33 added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819493.3178
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3178): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819493.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3178): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): start: OK
I/io.jxcore.node.ConnectionHelper( 3178): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819493.3178, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3178): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3178): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819493.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819493.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1455009819493.3178","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3178): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819493.3178, mode: WIFI
I/wpa_supplicant( 1040): p2p0: CTRL-EVENT-SCAN-STARTED 
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3178): onDiscoveryManagerStateChanged: RUNNING_WIFI
,I/io.jxcore.node.ConnectionHelper( 3178): start: OK
,I/jxcore-log( 3178): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 3178): 
,I/io.jxcore.node.ConnectionHelper( 3178): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3178): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3178): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 1040): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3178): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3178): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3178): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3178): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3178): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 3178): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98e168f added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819555.3178
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3178): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819555.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3178): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): start: OK
I/io.jxcore.node.ConnectionHelper( 3178): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819555.3178, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3178): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3178): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819555.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819555.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1455009819555.3178","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3178): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): start: Starting P2P device discovery...
,I/wpa_supplicant( 1040): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819555.3178, mode: WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3178): onDiscoveryManagerStateChanged: RUNNING_WIFI
,I/wpa_supplicant( 1040): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery stopped successfully
,I/io.jxcore.node.ConnectionHelper( 3178): start: OK
,I/jxcore-log( 3178): ok 65 Should be able to call startBroadcasting without error
I/jxcore-log( 3178): 
I/io.jxcore.node.ConnectionHelper( 3178): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3178): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3178): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3178): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3178): clear
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3178): Service requests cleared successfully
,I/io.jxcore.node.ConnectionHelper( 3178): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3178): ok 66 Should be able to call stopBroadcasting without error
I/jxcore-log( 3178): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f5f8cab added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819605.3178
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3178): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819605.3178","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): start: OK
I/io.jxcore.node.ConnectionHelper( 3178): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3178): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3178): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819605.3178, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3178): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3178): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819605.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819605.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1455009819605.3178","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): startWifiPeerDiscovery: Wi-Fi Direct OK
I/wpa_supplicant( 1040): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: OK
I/io.jxcore.node.ConnectionHelper( 3178): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819605.3178, mode: WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3178): ok 67 Should be able to call startBroadcasting without error
I/jxcore-log( 3178): 
,I/io.jxcore.node.ConnectionHelper( 3178): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): setState: NOT_STARTED
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stopForRestart
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3178): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 3178): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3178): onConnectionManagerStateChanged: NOT_STARTED
,I/wpa_supplicant( 1040): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3178): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3178): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3178): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3178): Service requests cleared successfully
,I/jxcore-log( 3178): ok 68 Should be able to call stopBroadcasting without error
I/jxcore-log( 3178): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28884887 added. We now have 5 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819641.3178
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3178): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819641.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): start: OK
I/io.jxcore.node.ConnectionHelper( 3178): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3178): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3178): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819641.3178, mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3178): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3178): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819641.3178","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819641.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1455009819641.3178","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onIsWifiPeerDiscoveryStartedChanged: true
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: OK
I/wpa_supplicant( 1040): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819641.3178, mode: WIFI
,I/io.jxcore.node.ConnectionHelper( 3178): start: OK
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3178): ok 69 Should be able to call startBroadcasting without error
I/jxcore-log( 3178): 
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3178): onDiscoveryManagerStateChanged: RUNNING_WIFI
,I/io.jxcore.node.ConnectionHelper( 3178): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): stop: Stopping Bluetooth...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): release: 1 listener(s) left
I/wpa_supplicant( 1040): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3178): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3178): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3178): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3178): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3178): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3178): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3178): ok 70 Should be able to call stopBroadcasting without error
I/jxcore-log( 3178): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1896e623 added. We now have 6 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819676.3178
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3178): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819676.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3178): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): start: OK
,I/io.jxcore.node.ConnectionHelper( 3178): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3178): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819676.3178, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3178): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3178): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819676.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819676.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1455009819676.3178","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): start: Starting P2P device discovery...
,I/wpa_supplicant( 1040): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819676.3178, mode: WIFI
,I/io.jxcore.node.ConnectionHelper( 3178): start: OK
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3178): ok 71 Should be able to call startBroadcasting without error
I/jxcore-log( 3178): 
I/io.jxcore.node.ConnectionHelper( 3178): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stopForRestart
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3178): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): stop: Stopping services
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3178): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3178): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): onServerStopped
I/wpa_supplicant( 1040): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3178): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3178): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3178): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3178): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3178): ok 72 Should be able to call stopBroadcasting without error
I/jxcore-log( 3178): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@367c17f added. We now have 7 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819716.3178
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3178): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819716.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3178): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): start: OK
I/io.jxcore.node.ConnectionHelper( 3178): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3178): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819716.3178, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3178): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3178): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819716.3178","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819716.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1455009819716.3178","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): setState: RUNNING_WIFI
I/wpa_supplicant( 1040): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: OK
I/io.jxcore.node.ConnectionHelper( 3178): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819716.3178, mode: WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3178): ok 73 Should be able to call startBroadcasting without error
I/jxcore-log( 3178): 
I/io.jxcore.node.ConnectionHelper( 3178): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): shutdown
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3178): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3178): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3178): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): stop: Stopping services
I/wpa_supplicant( 1040): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3178): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3178): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3178): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3178): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3178): ok 74 Should be able to call stopBroadcasting without error
I/jxcore-log( 3178): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2440f69b added. We now have 8 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819754.3178
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3178): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819754.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3178): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): start: OK
I/io.jxcore.node.ConnectionHelper( 3178): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819754.3178, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3178): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,W/BluetoothAdapter( 3178): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3178): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819754.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819754.3178","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1455009819754.3178","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): startWifiPeerDiscovery: Wi-Fi Direct OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: OK
I/io.jxcore.node.ConnectionHelper( 3178): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819754.3178, mode: WIFI
I/wpa_supplicant( 1040): p2p0: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3178): ok 75 Should be able to call startBroadcasting without error
I/jxcore-log( 3178): 
I/io.jxcore.node.ConnectionHelper( 3178): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3178): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3178): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): stop: Stopping services
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: STARTED
I/wpa_supplicant( 1040): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3178): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3178): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3178): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3178): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3178): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3178): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 3178): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1aae6177 added. We now have 9 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819789.3178
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3178): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819789.3178","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3178): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): start: OK
I/io.jxcore.node.ConnectionHelper( 3178): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3178): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819789.3178, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3178): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3178): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819789.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819789.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1455009819789.3178","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onIsWifiPeerDiscoveryStartedChanged: true
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: OK
I/wpa_supplicant( 1040): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819789.3178, mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3178): start: OK
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3178): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log( 3178): 
I/io.jxcore.node.ConnectionHelper( 3178): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): onServerStopped
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3178): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/io.jxcore.node.ConnectionHelper( 3178): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3178): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): stop: Stopping services
,I/wpa_supplicant( 1040): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3178): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3178): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3178): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3178): Service requests cleared successfully
I/jxcore-log( 3178): ok 78 Should be able to call stopBroadcasting without error
I/jxcore-log( 3178): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91d9e13 added. We now have 10 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819827.3178
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3178): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819827.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): start: OK
I/io.jxcore.node.ConnectionHelper( 3178): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3178): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819827.3178, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3178): bind: Binding a new listener
W/BluetoothAdapter( 3178): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3178): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819827.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819827.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1455009819827.3178","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: OK
I/io.jxcore.node.ConnectionHelper( 3178): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819827.3178, mode: WIFI
I/wpa_supplicant( 1040): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3178): ok 79 Should be able to call startBroadcasting without error
I/jxcore-log( 3178): 
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 3178): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): setState: NOT_STARTED
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stopForRestart
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3178): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3178): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: STARTED
,I/io.jxcore.node.ConnectionHelper( 3178): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): Local services cleared successfully
I/wpa_supplicant( 1040): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3178): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3178): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3178): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3178): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3178): ok 80 Should be able to call stopBroadcasting without error
I/jxcore-log( 3178): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3178): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13a086f added. We now have 11 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819864.3178
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3178): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819864.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): start: OK
I/io.jxcore.node.ConnectionHelper( 3178): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3178): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3178): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819864.3178, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3178): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3178): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819864.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: {"pi":"34:FC:EF:11:AE:67","pn":"1455009819864.3178","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1455009819864.3178","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: OK
I/wpa_supplicant( 1040): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1455009819864.3178, mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3178): start: OK
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3178): ok 81 Should be able to call startBroadcasting without error
I/jxcore-log( 3178): 
,I/io.jxcore.node.ConnectionHelper( 3178): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): shutdown
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3178): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3178): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3178): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1040): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3178): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3178): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3178): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3178): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3178): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3178): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3178): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3178): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3178): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3178): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3178): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3178): ok 82 Should be able to call stopBroadcasting without error
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): # setup
I/jxcore-log( 3178): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): Start timer timeout, starting now...
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3178): start: Cannot start, because not initialized
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  761): Explicit concurrent mark sweep GC freed 45544(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 1.225ms total 158.217ms
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  761): Killing 2707:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  761): Client connection lost with reason: 4
,W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2707/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3606 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3606): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3606):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3606):   adb logcat -s GAv4
,W/GAv4    ( 3606): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3606): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3606): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  761): Killing 2586:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2586/cgroup.procs: No such file or directory
,W/bt-smp  ( 2132): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2132): Plain text(LSB ~ MSB) = 78 af 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2132): Encrypted text(LSB ~ MSB) = 84 b5 6c 17 6e 76 eb cd 3b f2 fc 91 2b 13 80 18 
W/bt-btm  ( 2132): Stopping oneshot timer
,I/EventLogService( 1699): Aggregate from 1455008401163 (log), 1455008401163 (data)
,I/PhenotypeConfigurator( 1629): Scheduling Phenotype for one-off execution 5697 seconds from now (1455010498604)
,D/GetConfigurationSnapshotOperation( 1629): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1629): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1629): Using platform SSLCertificateSocketFactory
,I/UsageStatsService(  761): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3705): 
D/AndroidRuntime( 3705): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3705): CheckJNI is OFF
D/AndroidRuntime( 3705): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 3178:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  761): WIN DEATH: Window{2a4bc649 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  761): Client connection lost with reason: 4
W/PackageSettings(  761): Skipping PackageSetting{10bb313a com.example.hello/10278} due to missing metadata
I/ActivityManager(  761):   Force finishing activity ActivityRecord{2bb48925 u0 com.test.thalitest/.MainActivity t216}
W/ActivityManager(  761): Spurious death for ProcessRecord{1ed5854f 3178:com.test.thalitest/u0a270}, curProc for 3178: null
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/art     ( 1285): Explicit concurrent mark sweep GC freed 3959(294KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 560us total 16.540ms
I/art     ( 1344): Explicit concurrent mark sweep GC freed 7959(564KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 341us total 27.750ms
I/art     ( 1699): Explicit concurrent mark sweep GC freed 5554(339KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 22MB/30MB, paused 481us total 43.537ms
I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1629): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1085): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1085): run()
D/VoicemailCleanupService( 2869): Cleaning up data for package: com.test.thalitest
I/Decoder ( 1085): createOrResetDecoder
D/NetworkChangeNotifierAutoDetect(  950): Network connectivity changed, type is: 2
I/UpdateIcingCorporaServi( 1344): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1285): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2b25f5c7 new=com.google.android.velvet.VelvetApplication@2b25f5c7
I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3735 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/LibraryLoader( 1505): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
I/art     (  761): Explicit concurrent mark sweep GC freed 17767(1121KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 897us total 106.769ms
I/art     (  761): WaitForGcToComplete blocked for 67.362ms for cause Explicit
I/LibraryLoader( 1505): Time to load native libraries: 65 ms (timestamps 6697-6762)
I/LibraryLoader( 1505): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/chromium( 1505): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 1505): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1505): Attempt to remove local handle scope entry from IRT, ignoring
I/OpenGLRenderer(  950): Initialized EGL, version 1.4
D/OpenGLRenderer(  950): Enabling debug mode 0
I/ConfigService( 1629): onCreate
D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  761): removeObsoleteFile: deleting file=216_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader( 1085): run()
W/ContextImpl( 3735): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/UpdateIcingCorporaServi( 1344): UpdateCorporaTask done [took 189 ms] updated apps [took 189 ms] 
D/PackageBroadcastService( 1699): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1699): Clearing selected account for com.test.thalitest
W/InputMethodManagerService(  761): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@277be25d (uid=10034 pid=950)
D/ChimeraCfgMgr( 1699): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1699): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1699): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1629): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1629): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Keyboard.Facilitator.MainLanguageModelLoader( 1085): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
D/ChimeraCfgMgr( 1699): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1699): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1085): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1085): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1085): run()
I/StatsUtilsManager( 1085): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1085): shouldRecordStats() = Too Soon
I/art     (  761): Explicit concurrent mark sweep GC freed 4965(243KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.745ms total 203.218ms
D/gH_CompatibleDatabase( 1699): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1699): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1699): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1699): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1699): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1699): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1699): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1699): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1699): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1699): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1699): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1699): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1699): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  761): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3789 uid=10039 gids={50039, 9997} abi=armeabi-v7a
D/AndroidRuntime( 3705): Shutting down VM
I/GMPM-SVC( 1699): App measurement is starting up, version: 8489
I/GMPM-SVC( 1699): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/BaseAppContext( 1699): Using Auth Proxy for data requests.
W/BaseAppContext( 1699): Using Auth Proxy for data requests.
I/Icing   ( 1699): doRemovePackageData com.test.thalitest
I/ActivityManager(  761): Killing 2038:com.google.android.calendar/u0a31 (adj 15): empty #17
W/libprocessgroup(  761): failed to open /acct/uid_10031/pid_2038/cgroup.procs: No such file or directory
I/ActivityManager(  761): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3818 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/Launcher( 1285): Deferring update until onResume
I/ActivityManager(  761): Killing 1465:com.google.android.partnersetup/u0a13 (adj 15): empty #17
W/ResourcesManager( 1285): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1285): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1285): Deferring update until onResume
W/libprocessgroup(  761): failed to open /acct/uid_10013/pid_1465/cgroup.procs: No such file or directory
D/ExternalStorage( 3818): After updating volumes, found 1 active roots
W/ResourcesManager( 3092): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3092): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Documents( 3789): Update found 7 roots in 263ms
D/Documents( 3789): Update found 7 roots in 70ms

```
