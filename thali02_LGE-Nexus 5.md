#### Test 575312431745da8_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1594): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1594): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3102): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3102):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3102):   adb logcat -s GAv4
W/GAv4    ( 3102): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3102): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3102): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3102): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2626): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3102): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3102): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  760): Killing 2054:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 3102): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3102): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3102): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  760): failed to open /acct/uid_10038/pid_2054/cgroup.procs: No such file or directory
V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1594): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1594): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1594): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1594): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3157): 
D/AndroidRuntime( 3157): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3157): CheckJNI is OFF
D/AndroidRuntime( 3157): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3178 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3157): Shutting down VM
V/ActivityManager(  760): Display changed displayId=0
I/WebViewFactory( 3178): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3178): Time to load native libraries: 1 ms (timestamps 7198-7199)
I/LibraryLoader( 3178): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3178): Binding Chromium to main looper Looper (main, tid 1) {29985f01}
I/LibraryLoader( 3178): Expected native library version number "",actual native library version number ""
I/chromium( 3178): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3178): Initializing chromium process, singleProcess=true
W/art     ( 3178): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3178): ApplicationContext is null in ApplicationStatus
W/chromium( 3178): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3178): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3178): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3178): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@119308cb:true
,W/art     ( 3178): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3178): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3178): CordovaWebView is running on device made by: LGE
,W/art     ( 3178): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3178): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3178): Render dirty regions requested: true
,D/Atlas   ( 3178): Validating map...
,W/chromium( 3178): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/Finsky  ( 2626): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/OpenGLRenderer( 3178): Initialized EGL, version 1.4
D/OpenGLRenderer( 3178): Enabling debug mode 0
,I/art     ( 1570): Explicit concurrent mark sweep GC freed 33766(2MB) AllocSpace objects, 30(480KB) LOS objects, 40% free, 21MB/35MB, paused 1.665ms total 58.518ms
,W/IInputConnectionWrapper( 3178): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1064): onFinishInput()
,I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +399ms (total +44s528ms)
,V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BindingManager( 3178): Cannot call determinedVisibility() - never saw a connection for the pid: 3178
,D/JsMessageQueue( 3178): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3178): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,I/chromium( 3178): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2626): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2626): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2626): untagSocket(37) failed with errno -22
D/Finsky  ( 2626): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  760): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3249 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 3249): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3249): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3249): VM with version 2.1.0 has multidex support
I/MultiDex( 3249): install
I/MultiDex( 3249): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3249): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 2626): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2626): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2626): untagSocket(37) failed with errno -22
,W/ActivityThread( 3249): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3249): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@28c14fdb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3249): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1570): callingUid 10008, callindPid: 1570
,E/MDM     ( 1570): [221] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1570): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationInitializer( 1594): Restart initialization of location
,D/ChimeraCfgMgr( 3249): Reading stored module config
,W/GCoreFlp( 1570): No location to return for getLastLocation()
W/FusedLocationProvider( 1570): location=null
,D/ChimeraCfgMgr( 3249): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/CAR.SERVICE( 3249): Connecting to CarCallService...
,D/NativeLibraryUtils( 3249): Install completed successfully. count=14 extracted=0
,I/art     ( 3249): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3249): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 3249): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 3249): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 3249): Creating a new PhoneAdapter instance
W/ActivityManager(  760): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3249): setListener: com.google.android.gms.car.dn@36ebb466
W/ActivityManager(  760): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3249): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3249): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 3249): Package validated; name: com.android.vending
,V/Finsky  ( 2626): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/art     (  760): Explicit concurrent mark sweep GC freed 17296(818KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 932us total 58.090ms
,W/jxcore-log( 3178): Initializing JXcore engine
W/jxcore-log( 3178): JXcore engine is ready
,W/Thread-306( 3241): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7345]" dev="sockfs" ino=7345 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-306( 3241): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-306( 3241): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10482]" dev="sockfs" ino=10482 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-306( 3241): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19009]" dev="sockfs" ino=19009 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3178): Starting JXcore engine
,V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/jxcore-log( 3178): Platform android
W/jxcore-log( 3178): 
,W/jxcore-log( 3178): Process ARCH arm
W/jxcore-log( 3178): 
,I/qtaguid ( 2626): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2626): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2626): untagSocket(37) failed with errno -22
,W/ResourcesManager( 2626): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2626): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2626): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2626): [1] DailyHygiene.access$600: Logging device features
,I/jxcore-log( 3178): JXcore Cordova bridge is ready!
I/jxcore-log( 3178): 
W/jxcore-log( 3178): JXcore engine is started
,D/DeviceConnectionService( 1570): client connected with version: 8296000
,D/Finsky  ( 2626): [265] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2626): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 2626): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/jxcore-log( 3178): Toggling radios to true
I/jxcore-log( 3178): 
,D/BluetoothAdapter( 3178): enable(): BT is already enabled..!
,D/WifiService(  760): New client listening to asynchronous messages
D/WifiService(  760): setWifiEnabled: true pid=3178, uid=10270
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3178): Radios toggled
I/jxcore-log( 3178): 
I/jxcore-log( 3178): My device name is: LGE-Nexus 5
I/jxcore-log( 3178): 
I/wpa_supplicant( 1047): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  760): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  760): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1570): Read error: ssl=0xb3d2ae00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1570): SSL shutdown failed: ssl=0xb3d2ae00: I/O error during system call, Broken pipe
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/ConnectivityService(  760): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on <unknown ssid>
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  760): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1047): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  760): do suspend true
,I/ActivityManager(  760): Killing 2529:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,D/ConnectivityService(  760): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/Nat464Xlat(  760): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/CSLegacyTypeTracker(  760): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Disconnected - quitting
D/CommandListener(  180): Clearing all IP addresses on wlan0
D/ConnectivityManager.CallbackHandler( 1594): CM callback handler got msg 524292
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ActivityManager(  760): Killing 2578:com.google.android.gm.exchange/u0a69 (adj 15): empty #18
,W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_2529/cgroup.procs: No such file or directory
,W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_2578/cgroup.procs: No such file or directory
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  760): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1184): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  760): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiNetworkAgent(  760): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant( 1047): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1047): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1047): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1047): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  760): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  180): Setting iface cfg
E/WifiStateMachine(  760): Start Dhcp Watchdog 2
,E/native  (  760): do suspend false
,E/WifiStateMachine(  760): scanCount==0 - aborting
,I/dhcpcd  ( 3340): version 5.5.6 starting
E/dhcpcd  ( 3340): get_duid: Read-only file system
,I/dhcpcd  ( 3340): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3340): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3340): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  760): do suspend true
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  760): Adding iface wlan0 to network 101
,E/WifiStateMachine(  760): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  760): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  760): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  760): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  760): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  760): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  760): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  760): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1594): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Feb 2016 13:36:52 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454593012663], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454593012643]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Validated
D/ConnectivityService(  760): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1184): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1594): CM callback handler got msg 524290
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1594): CM callback handler got msg 524295
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2730): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2730): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2730): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1594): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1594): onCreate
,D/SystemUpdateService( 1594): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/ActivityManager(  760): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3374 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SystemUpdateService( 1594): active receiver: enabled
,E/GpsLocationProvider(  760): No APN found to select.
,E/GpsLocationProvider(  760): No APN found to select.
I/SystemUpdateService( 1594): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1594): retry (wakeup: false) in 3599951 ms
,D/SystemUpdateService( 1594): onDestroy
,I/GAv4    ( 3374): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3374):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3374):   adb logcat -s GAv4
,W/GAv4    ( 3374): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3374): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3374): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  760): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/WebViewFactory( 3374): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3374): Time to load native libraries: 1 ms (timestamps 3156-3157)
I/LibraryLoader( 3374): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3374): Binding Chromium to main looper Looper (main, tid 1) {1cf1e5cb}
,I/LibraryLoader( 3374): Expected native library version number "",actual native library version number ""
I/chromium( 3374): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3374): Initializing chromium process, singleProcess=true
W/art     ( 3374): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3374): ApplicationContext is null in ApplicationStatus
,W/chromium( 3374): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3374): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3374): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3374): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3374): Starting up...
,W/AudioManagerAndroid( 3374): Requires BLUETOOTH permission
,I/ActivityManager(  760): Killing 2710:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,I/jxcore-log( 3178): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3178): 
,W/libprocessgroup(  760): failed to open /acct/uid_10003/pid_2710/cgroup.procs: No such file or directory
,V/MusicLeanback( 2730): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1594): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1594): onCreate
,D/SystemUpdateService( 1594): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1594): active receiver: enabled
,I/SystemUpdateService( 1594): showing system update notification
,D/CAR.SERVICE( 3249): mConnectedToCar = false, abort
,I/ValidateNoPeople(  760): skipping global notification
,E/ActivityThread( 3249): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@143d018e that was originally bound here
E/ActivityThread( 3249): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@143d018e that was originally bound here
E/ActivityThread( 3249): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3249): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3249): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3249): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3249): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3249): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3249): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3249): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3249): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3249): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3249): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3249): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3249): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3249): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3249): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3249): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3249): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3249): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3249): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3249): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3249): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3249): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3249): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,V/SystemUpdateService( 1594): retry (wakeup: false) in 3599947 ms
,E/ActivityThread( 3249): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@37c574c1 that was originally bound here
E/ActivityThread( 3249): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@37c574c1 that was originally bound here
E/ActivityThread( 3249): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3249): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3249): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3249): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3249): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3249): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3249): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3249): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3249): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3249): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3249): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3249): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3249): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3249): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3249): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3249): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3249): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3249): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3249): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3249): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3249): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3249): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  760): Unbind failed: could not find connection for android.os.BinderProxy@2caa282b
,D/SystemUpdateService( 1594): onDestroy
,I/jxcore-log( 3178): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3178): 
I/jxcore-log( 3178): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3178): 
,I/jxcore-log( 3178): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3178): 
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
I/NetworkMonitor( 2730): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2730): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  760): No APN found to select.
,I/SystemUpdateService( 1594): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1594): onCreate
,D/SystemUpdateService( 1594): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1594): active receiver: enabled
,I/SystemUpdateService( 1594): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1594): retry (wakeup: false) in 3599966 ms
,D/SystemUpdateService( 1594): onDestroy
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
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3178): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37698d94 added. We now have 1 listener(s)
,I/jxcore-log( 3178): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3178): 
,V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2626): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2626): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/GoogleURLConnFactory( 1570): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PhenotypeConfigurator( 1570): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,W/PhenotypeConfigurator( 1570): Server returned 404
,I/VacuumService( 1570): Vacuum at: now=1454593040552 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1064): run()
I/Keyboard.Facilitator( 1064): flushDynamicLanguageModels()
,I/ConfigService( 1570): onCreate
,I/ConfigService( 1570): onDestroy
,I/ClearcutLoggerApiImpl( 1570): disconnect managed GoogleApiClient
,I/PhenotypeConfigurator( 1570): Scheduling Phenotype for one-off execution 7464 seconds from now (1454593128222)
,D/GetConfigurationSnapshotOperation( 1570): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1570): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1570): Using platform SSLCertificateSocketFactory
,I/art     (  760): Explicit concurrent mark sweep GC freed 56841(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 923us total 58.076ms
,V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1570): Explicit concurrent mark sweep GC freed 139495(7MB) AllocSpace objects, 22(375KB) LOS objects, 39% free, 24MB/40MB, paused 1.108ms total 83.380ms
,E/DataBuffer( 1570): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1e098599)
E/DataBuffer( 1570): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1e18b05e)
E/DataBuffer( 1570): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1cf3ec3f)
E/DataBuffer( 1570): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1d90f90c)
E/DataBuffer( 1570): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2de3e255)
,I/ActivityManager(  760): Killing 2691:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  760): Client connection lost with reason: 4
,W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_2691/cgroup.procs: No such file or directory
,W/bt-smp  ( 2099): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
,W/bt-smp  ( 2099): Plain text(LSB ~ MSB) = 14 56 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2099): Encrypted text(LSB ~ MSB) = 30 6d 05 5b 75 d1 0b b6 e0 25 00 66 be 3e e3 e0 
,W/bt-btm  ( 2099): Stopping oneshot timer
,I/ActivityManager(  760): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3649 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3649): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3649):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3649):   adb logcat -s GAv4
,W/GAv4    ( 3649): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3649): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3649): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  760): Killing 2549:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2549/cgroup.procs: No such file or directory
,I/UsageStatsService(  760): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
