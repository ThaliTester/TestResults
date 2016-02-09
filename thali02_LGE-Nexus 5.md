#### Test 583805004f2b042_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 2991): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2991):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2991):   adb logcat -s GAv4
D/ChimeraCfgMgr( 1622): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1622): Module APK com.google.android.play.games already loaded
W/GAv4    ( 2991): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2991): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2991): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 2991): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2557): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 2991): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2991): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  739): Killing 2032:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 2991): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 2991): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2991): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  739): failed to open /acct/uid_10038/pid_2032/cgroup.procs: No such file or directory
V/GLSActivity( 1565): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1622): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1622): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1622): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1622): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
D/Finsky  ( 2557): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1565): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1565): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1565): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1565): Explicit concurrent mark sweep GC freed 34359(2MB) AllocSpace objects, 31(496KB) LOS objects, 40% free, 21MB/35MB, paused 923us total 41.255ms
,D/AndroidRuntime( 3053): 
D/AndroidRuntime( 3053): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3053): CheckJNI is OFF
D/AndroidRuntime( 3053): Calling main entry com.android.commands.am.Am
I/ActivityManager(  739): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  739): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3071 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3053): Shutting down VM
V/ActivityManager(  739): Display changed displayId=0
I/WebViewFactory( 3071): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3071): Time to load native libraries: 1 ms (timestamps 5026-5027)
I/LibraryLoader( 3071): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3071): Binding Chromium to main looper Looper (main, tid 1) {11583825}
I/LibraryLoader( 3071): Expected native library version number "",actual native library version number ""
I/chromium( 3071): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3071): Initializing chromium process, singleProcess=true
W/art     ( 3071): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3071): ApplicationContext is null in ApplicationStatus
W/chromium( 3071): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3071): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3071): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3071): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  739): Message: 20
D/BluetoothManagerService(  739): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3be0e3ba:true
,W/art     ( 3071): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3071): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3071): CordovaWebView is running on device made by: LGE
,W/art     ( 3071): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3071): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3071): Render dirty regions requested: true
,D/Atlas   ( 3071): Validating map...
,W/chromium( 3071): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3071): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3071): Enabling debug mode 0
,W/BindingManager( 3071): Cannot call determinedVisibility() - never saw a connection for the pid: 3071
,I/ActivityManager(  739): Displayed com.test.thalitest/.MainActivity: +432ms (total +45s138ms)
,W/IInputConnectionWrapper( 3071): showStatusIcon on inactive InputConnection
,V/GLSActivity( 1565): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/JsMessageQueue( 3071): Set native->JS mode to OnlineEventsBridgeMode
,I/qtaguid ( 2557): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2557): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2557): untagSocket(37) failed with errno -22
,D/Finsky  ( 2557): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1565): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/jxcore_app_log( 3071): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257343360
I/ActivityManager(  739): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3133 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/chromium( 3071): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ResourcesManager( 3133): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3133): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3133): VM with version 2.1.0 has multidex support
,I/MultiDex( 3133): install
I/MultiDex( 3133): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3133): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3133): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3133): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e74ce5f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3133): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1565): callingUid 10008, callindPid: 1565
D/LocationInitializer( 1622): Restart initialization of location
D/AuthorizationBluetoothService( 1565): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/ChimeraCfgMgr( 3133): Reading stored module config
E/MDM     ( 1565): [222] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1565): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 3133): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/GCoreFlp( 1565): No location to return for getLastLocation()
W/FusedLocationProvider( 1565): location=null
,I/qtaguid ( 2557): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2557): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2557): untagSocket(37) failed with errno -22
,D/NativeLibraryUtils( 3133): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 3133): Connecting to CarCallService...
,I/art     ( 3133): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3133): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 3133): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 3133): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 3133): Creating a new PhoneAdapter instance
W/ActivityManager(  739): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3133): setListener: com.google.android.gms.car.dn@20a94ba
W/ActivityManager(  739): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3133): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3133): Starting CarCallService with initial phone null
,I/art     (  739): Explicit concurrent mark sweep GC freed 16020(721KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 971us total 50.005ms
,D/CAR.SERVICE( 3133): Package validated; name: com.android.vending
,V/Finsky  ( 2557): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1565): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2557): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2557): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2557): untagSocket(37) failed with errno -22
,W/jxcore-log( 3071): Initializing JXcore engine
W/jxcore-log( 3071): JXcore engine is ready
,W/Thread-303( 3139): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9324]" dev="sockfs" ino=9324 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-303( 3139): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-303( 3139): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10432]" dev="sockfs" ino=10432 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-303( 3139): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18134]" dev="sockfs" ino=18134 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3071): Starting JXcore engine
,W/ResourcesManager( 2557): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2557): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/jxcore-log( 3071): Platform android
W/jxcore-log( 3071): 
W/jxcore-log( 3071): Process ARCH arm
W/jxcore-log( 3071): 
,W/ResourcesManager( 2557): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2557): [1] DailyHygiene.access$600: Logging device features
,D/DeviceConnectionService( 1565): client connected with version: 8296000
,D/Finsky  ( 2557): [265] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1565): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2557): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2557): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/jxcore-log( 3071): JXcore Cordova bridge is ready!
I/jxcore-log( 3071): 
,W/jxcore-log( 3071): JXcore engine is started
,I/ActivityManager(  739): Killing 2485:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/jxcore-log( 3071): Toggling radios to true
I/jxcore-log( 3071): 
,D/BluetoothAdapter( 3071): enable(): BT is already enabled..!
,D/WifiService(  739): setWifiEnabled: true pid=3071, uid=10270
E/WifiService(  739): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  739): New client listening to asynchronous messages
,I/jxcore-log( 3071): Radios toggled
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): My device name is: LGE-Nexus 5
I/jxcore-log( 3071): 
,I/ActivityManager(  739): Killing 2529:com.google.android.gm.exchange/u0a69 (adj 15): empty #18
,I/wpa_supplicant(  986): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  739): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  739): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  739): do suspend true
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1565): Read error: ssl=0xb3f47e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1565): SSL shutdown failed: ssl=0xb3f47e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  739): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  739): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  739): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  739): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  739): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  739): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  739): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,W/libprocessgroup(  739): failed to open /acct/uid_10045/pid_2485/cgroup.procs: No such file or directory
,W/libprocessgroup(  739): failed to open /acct/uid_10069/pid_2529/cgroup.procs: No such file or directory
,D/ConnectivityService(  739): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  739): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  739): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  739): Start Disconnecting Watchdog 1
,E/native  (  739): do suspend true
,I/wpa_supplicant(  986): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/ConnectivityService(  739): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  739): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  739): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  739): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  739): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  739): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler( 1622): CM callback handler got msg 524292
D/ConnectivityService(  739): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  739): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  739): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  739): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/TelephonyNetworkFactory( 1234): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  739): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  986): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  986): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  986): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  986): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  739): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  739): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  739): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  739): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  182): Setting iface cfg
,E/WifiStateMachine(  739): Start Dhcp Watchdog 2
,E/native  (  739): do suspend false
,E/WifiStateMachine(  739): scanCount==0 - aborting
,I/dhcpcd  ( 3207): version 5.5.6 starting
E/dhcpcd  ( 3207): get_duid: Read-only file system
,I/dhcpcd  ( 3207): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3207): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3207): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  739): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  739): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  739): MasterInitialState.processMessage what=3
,D/Tethering(  739): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2667): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1622): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1622): onCreate
,D/SystemUpdateService( 1622): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1622): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1622): num queued entries: 0
,I/SystemUpdateService( 1622): active receiver: enabled
,I/SystemUpdateService( 1622): showing system update notification
,I/Babel   ( 1884): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 1622): num updated entries: 0
I/iu.SyncManager( 1622): NEXT; no task
,I/ActivityManager(  739): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3231 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/GpsLocationProvider(  739): No APN found to select.
,E/GpsLocationProvider(  739): No APN found to select.
,V/SystemUpdateService( 1622): retry (wakeup: false) in 3599923 ms
,I/ValidateNoPeople(  739): skipping global notification
,D/SystemUpdateService( 1622): onDestroy
,E/native  (  739): do suspend true
,D/ConnectivityService(  739): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  739): Adding iface wlan0 to network 101
,E/WifiStateMachine(  739): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  739): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  739): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  739): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  739): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  739): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  739): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  739): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  739): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  739): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  739):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  739): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  739): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  739): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  739): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  739): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  739): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  739): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  739): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1622): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
,I/GAv4    ( 3231): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3231):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3231):   adb logcat -s GAv4
,W/GAv4    ( 3231): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3231): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3231): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  739): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 16:35:52 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455035751953], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455035751937]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  739): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  739): Validated
,D/ConnectivityService(  739): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  739): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  739): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  739): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  739): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1622): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1234): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Nat464Xlat(  739): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  739): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1622): CM callback handler got msg 524295
,I/WebViewFactory( 3231): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3231): Time to load native libraries: 1 ms (timestamps 849-850),
I/LibraryLoader( 3231): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3231): Binding Chromium to main looper Looper (main, tid 1) {35940d4f}
I/LibraryLoader( 3231): Expected native library version number "",actual native library version number ""
I/chromium( 3231): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3231): Initializing chromium process, singleProcess=true
,W/art     ( 3231): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3231): ApplicationContext is null in ApplicationStatus
,W/chromium( 3231): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3231): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3231): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3231): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3231): Requires BLUETOOTH permission
,I/NSApplication( 3231): Starting up...
,I/ActivityManager(  739): Killing 2641:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  739): failed to open /acct/uid_10003/pid_2641/cgroup.procs: No such file or directory
,V/MusicLeanback( 2667): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/CAR.SERVICE( 3133): mConnectedToCar = false, abort
,I/SystemUpdateService( 1622): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,E/ActivityThread( 3133): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2938fb62 that was originally bound here
E/ActivityThread( 3133): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2938fb62 that was originally bound here
E/ActivityThread( 3133): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3133): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3133): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3133): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3133): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3133): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3133): ,	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3133): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3133): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3133): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3133): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3133): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3133): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3133): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3133): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3133): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3133): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3133): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3133): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3133): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3133): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3133): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3133): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,D/SystemUpdateService( 1622): onCreate
,E/ActivityThread( 3133): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@279511e5 that was originally bound here
E/ActivityThread( 3133): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@279511e5 that was originally bound here
E/ActivityThread( 3133): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3133): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3133): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3133): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3133): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3133): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3133): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3133): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3133): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3133): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3133): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3133): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3133): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3133): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3133): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3133): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3133): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3133): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3133): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3133): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3133): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3133): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  739): Unbind failed: could not find connection for android.os.BinderProxy@1111ebdb
,D/SystemUpdateService( 1622): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1622): active receiver: enabled
,I/SystemUpdateService( 1622): showing system update notification
,I/iu.Environment( 1622): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ValidateNoPeople(  739): skipping global notification
,I/iu.UploadsManager( 1622): num queued entries: 0
,I/iu.UploadsManager( 1622): num updated entries: 0
I/iu.SyncManager( 1622): NEXT; no task
V/SystemUpdateService( 1622): retry (wakeup: false) in 3599991 ms
,D/SystemUpdateService( 1622): onDestroy
,I/jxcore-log( 3071): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3071): 
,I/Babel   ( 1884): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  739): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3071): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3071): 
,D/ConnectivityService(  739): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  739): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2667): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2667): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1622): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1622): onCreate
,D/SystemUpdateService( 1622): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/GpsLocationProvider(  739): No APN found to select.
,I/SystemUpdateService( 1622): active receiver: enabled
,I/SystemUpdateService( 1622): showing system update notification
,I/ValidateNoPeople(  739): skipping global notification
,V/SystemUpdateService( 1622): retry (wakeup: false) in 3599984 ms
,D/SystemUpdateService( 1622): onDestroy
,I/jxcore-log( 3071): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): Test app app.js loaded
I/jxcore-log( 3071): 
,I/chromium( 3071): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3071): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3071): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3071): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3071): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3071): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3071): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3071): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3071): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3071): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3071): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f32bed4 added. We now have 1 listener(s)
,I/jxcore-log( 3071): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): TAP version 13
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): # setup
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # #generatePreambleAndBeacons null ECDH for local device
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): ok 1 publicKeysToNotify cannot be null
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): # teardown
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): # setup
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): # #generatePreambleAndBeacons null ECDH for local device
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): ok 2 ecdhForLocalDevice cannot be null
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): # teardown
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # setup
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # #generatePreambleAndBeacons expiration out of range lower
I/jxcore-log( 3071): 
I/jxcore-log( 3071): ok 3 secondsUntilExpiration out of range.
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # teardown
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # setup
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # #generatePreambleAndBeacons expiration out of range upper
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): ok 4 secondsUntilExpiration out of range.
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # teardown
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # setup
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): ok 5 should be equal
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # teardown
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # setup
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): ok 6 should be equal
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): ok 7 should be equal
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): ok 8 should be equal
I/jxcore-log( 3071): 
I/jxcore-log( 3071): ok 9 should be equal
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # teardown
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # setup
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): ok 10 should throw
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): # teardown
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # setup
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): ok 11 Preamble expiration must be a 64 bit integer
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # teardown
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # setup
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # #parseBeacons expiration out of range lower
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): ok 12 Expiration out of range
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): # teardown
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # setup
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): # #parseBeacons expiration out of range lower
I/jxcore-log( 3071): 
I/jxcore-log( 3071): ok 13 Expiration out of range
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # teardown
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # setup
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # #parseBeacons no beacons returns null
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): ok 14 should be equal
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): # teardown
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): # setup
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): ok 15 Malformed encrypted beacon key ID
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # teardown
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # setup
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): ok 16 should be equal
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): # teardown
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): # setup
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # #parseBeacons addressBookCallback returns no matches
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): ok 17 should be equal
I/jxcore-log( 3071): 
I/jxcore-log( 3071): ok 18 should be equal
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): # teardown
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): # setup
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): ok 19 should be equal
I/jxcore-log( 3071): 
I/jxcore-log( 3071): ok 20 (unnamed assert)
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): # teardown
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): # setup
I/jxcore-log( 3071): 
I/jxcore-log( 3071): # #parseBeacons with beacons both for and not for the user
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): ok 21 (unnamed assert)
I/jxcore-log( 3071): 
,I/jxcore-log( 3071): # teardown
I/jxcore-log( 3071): 
,V/GLSActivity( 1565): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1565): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2557): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2557): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1565): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1565): Vacuum at: now=1455035776999 tag=VacuumService
,D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 2055): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 2055): Disconnected process message: 11, size: 0
,I/ClearcutLoggerApiImpl( 1565): disconnect managed GoogleApiClient
,I/jxcore-log( 3071): --= Surplus to requirements =--
I/jxcore-log( 3071): 
I/jxcore-log( 3071): ****TEST TOOK:  ms ****
I/jxcore-log( 3071): 
I/jxcore-log( 3071): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3071): 
,D/AndroidRuntime( 3433): 
D/AndroidRuntime( 3433): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3433): CheckJNI is OFF
,D/AndroidRuntime( 3433): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  739): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  739): Killing 3071:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  739): WIN DEATH: Window{3b5e2c5b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  739): Client connection lost with reason: 4
,W/PackageSettings(  739): Skipping PackageSetting{137a6a69 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  739):   Force finishing activity ActivityRecord{7123d57 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  739): Spurious death for ProcessRecord{3b3e5f43 3071:com.test.thalitest/u0a270}, curProc for 3071: null
,I/ActivityManager(  739): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  739):   Force finishing activity ActivityRecord{7123d57 u0 com.test.thalitest/.MainActivity t216 f}
W/ActivityManager(  739): Duplicate finish request for ActivityRecord{7123d57 u0 com.test.thalitest/.MainActivity t216 f}
,I/art     ( 1286): Explicit concurrent mark sweep GC freed 3934(293KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 326us total 46.916ms
,I/Keyboard.Facilitator( 1100): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1565): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  739): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1622): Explicit concurrent mark sweep GC freed 3940(206KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/30MB, paused 437us total 98.689ms
,I/art     ( 1419): Explicit concurrent mark sweep GC freed 10247(701KB) AllocSpace objects, 1(39KB) LOS objects, 24% free, 19MB/25MB, paused 437us total 46.394ms
,I/Keyboard.Facilitator.DecoderInitializer( 1100): run()
,I/Decoder ( 1100): createOrResetDecoder
,I/Adreno-EGL(  950): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  950): Initialized EGL, version 1.4
,I/art     (  739): Explicit concurrent mark sweep GC freed 54364(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 1.948ms total 109.276ms
,D/OpenGLRenderer(  950): Enabling debug mode 0
,D/VoicemailCleanupService( 2772): Cleaning up data for package: com.test.thalitest
,I/art     (  739): WaitForGcToComplete blocked for 33.427ms for cause Explicit
,W/Launcher( 1286): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@15495dfa new=com.google.android.velvet.VelvetApplication@15495dfa
I/UpdateIcingCorporaServi( 1419): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ConfigService( 1565): onCreate
,I/ActivityManager(  739): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3474 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  739): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  739): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  739): removeObsoleteFile: deleting file=216_task.xml
,W/InputMethodManagerService(  739): Got RemoteException sending setActive(false) notification to pid 3071 uid 10270
,I/Keyboard.Facilitator( 1100): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1100): run()
,I/UpdateIcingCorporaServi( 1419): UpdateCorporaTask done [took 117 ms] updated apps [took 117 ms] 
,W/ContextImpl( 3474): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1622): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1622): Clearing selected account for com.test.thalitest
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1100): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,D/ChimeraCfgMgr( 1622): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1622): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1622): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1622): Module APK com.google.android.play.games already loaded
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Loading LM = contacts
,I/ActivityManager(  739): Killing 2621:com.android.settings/1000 (adj 15): empty #17
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1100): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1100): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1100): run()
I/StatsUtilsManager( 1100): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1100): shouldRecordStats() = Too Soon
,I/art     (  739): Explicit concurrent mark sweep GC freed 11194(569KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 7.093ms total 180.059ms
,D/WifiService(  739): Client connection lost with reason: 4
,D/AndroidRuntime( 3433): Shutting down VM
,W/libprocessgroup(  739): failed to open /acct/uid_1000/pid_2621/cgroup.procs: No such file or directory
,I/Launcher( 1286): Deferring update until onResume
,I/LocationSettingsChecker( 1622): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1565): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1565): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/ResourcesManager( 1286): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1622): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1622): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1622): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1622): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1622): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1622): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1622): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,W/ResourcesManager( 1286): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1622): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1622): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1622): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1622): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1622): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1622): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  739): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3506 uid=10039 gids={50039, 9997} abi=armeabi-v7a
I/Launcher( 1286): Deferring update until onResume
,I/GMPM-SVC( 1622): App measurement is starting up, version: 8489
I/GMPM-SVC( 1622): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1622): Using Auth Proxy for data requests.
,W/BaseAppContext( 1622): Using Auth Proxy for data requests.
,I/Icing   ( 1622): doRemovePackageData com.test.thalitest
,I/ActivityManager(  739): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3531 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  739): Killing 2503:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  739): failed to open /acct/uid_10070/pid_2503/cgroup.procs: No such file or directory
,I/ActivityManager(  739): Killing 1967:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  739): failed to open /acct/uid_10031/pid_1967/cgroup.procs: No such file or directory
,D/ExternalStorage( 3531): After updating volumes, found 1 active roots
,W/ResourcesManager( 2991): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2991): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.

```
