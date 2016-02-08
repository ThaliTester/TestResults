#### Test 581356550b07fff_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3063): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3063):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3063):   adb logcat -s GAv4
W/GAv4    ( 3063): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3063): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3063): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3063): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2569): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3063): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3063): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  760): Killing 2005:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 3063): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3063): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3063): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  760): failed to open /acct/uid_10038/pid_2005/cgroup.procs: No such file or directory
V/GLSActivity( 1561): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2569): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1561): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1561): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1561): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1561): Explicit concurrent mark sweep GC freed 33686(2MB) AllocSpace objects, 30(480KB) LOS objects, 40% free, 21MB/35MB, paused 902us total 62.107ms
I/Icing   ( 1620): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1620): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1620): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1620): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
V/GLSActivity( 1561): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/qtaguid ( 2569): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2569): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2569): untagSocket(37) failed with errno -22
D/Finsky  ( 2569): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
I/ActivityManager(  760): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3130 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
V/GLSActivity( 1561): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 3130): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3130): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 3130): VM with version 2.1.0 has multidex support
I/MultiDex( 3130): install
I/MultiDex( 3130): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 3130): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 3130): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3130): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bfe9093: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3130): Installed default security provider GmsCore_OpenSSL
D/LocationInitializer( 1620): Restart initialization of location
D/WearableService( 1561): callingUid 10008, callindPid: 1561
D/AuthorizationBluetoothService( 1561): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1561): [220] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ChimeraCfgMgr( 3130): Reading stored module config
V/GLSActivity( 1561): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1561): No location to return for getLastLocation()
W/FusedLocationProvider( 1561): location=null
D/AndroidRuntime( 3147): 
D/AndroidRuntime( 3147): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3147): CheckJNI is OFF
D/ChimeraCfgMgr( 3130): Loading module com.google.android.gms.car from APK com.google.android.gms
I/qtaguid ( 2569): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2569): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2569): untagSocket(37) failed with errno -22
D/CAR.SERVICE( 3130): Connecting to CarCallService...
D/NativeLibraryUtils( 3130): Install completed successfully. count=14 extracted=0
I/art     ( 3130): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3130): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/AndroidRuntime( 3147): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/CAR.SERVICE( 3130): com.google.android.projection.gearhead isn't installed.
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3187 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3147): Shutting down VM
D/CAR.TEL.Service( 3130): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 3130): Creating a new PhoneAdapter instance
W/ActivityManager(  760): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3130): setListener: com.google.android.gms.car.dn@39c24c7e
W/ActivityManager(  760): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3130): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3130): Starting CarCallService with initial phone null
V/ActivityManager(  760): Display changed displayId=0
D/CAR.SERVICE( 3130): Package validated; name: com.android.vending
I/WebViewFactory( 3187): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
V/Finsky  ( 2569): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/LibraryLoader( 3187): Time to load native libraries: 1 ms (timestamps 6782-6783)
I/LibraryLoader( 3187): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3187): Binding Chromium to main looper Looper (main, tid 1) {1c4e3079}
I/LibraryLoader( 3187): Expected native library version number "",actual native library version number ""
I/chromium( 3187): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3187): Initializing chromium process, singleProcess=true
W/art     ( 3187): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3187): ApplicationContext is null in ApplicationStatus
,W/chromium( 3187): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3187): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3187): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3187): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ec9c49a:true
,W/art     ( 3187): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3187): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3187): CordovaWebView is running on device made by: LGE
,W/art     ( 3187): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3187): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3187): Render dirty regions requested: true
,D/Atlas   ( 3187): Validating map...
,W/chromium( 3187): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3187): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3187): Enabling debug mode 0
,V/GLSActivity( 1561): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BindingManager( 3187): Cannot call determinedVisibility() - never saw a connection for the pid: 3187
W/IInputConnectionWrapper( 3187): showStatusIcon on inactive InputConnection
,I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +413ms (total +45s112ms)
,I/art     (  760): Explicit concurrent mark sweep GC freed 17481(786KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 846us total 53.529ms
,D/JsMessageQueue( 3187): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3187): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1405526272
,I/qtaguid ( 2569): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2569): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2569): untagSocket(37) failed with errno -22
,I/chromium( 3187): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ResourcesManager( 2569): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2569): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2569): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2569): [1] DailyHygiene.access$600: Logging device features
,D/DeviceConnectionService( 1561): client connected with version: 8296000
,D/Finsky  ( 2569): [265] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1561): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2569): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2569): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  760): Killing 2540:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_2540/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 2484:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_2484/cgroup.procs: No such file or directory
,W/jxcore-log( 3187): Initializing JXcore engine
W/jxcore-log( 3187): JXcore engine is ready
,W/Thread-311( 3242): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6479]" dev="sockfs" ino=6479 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-311( 3242): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-311( 3242): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6525]" dev="sockfs" ino=6525 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-311( 3242): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19912]" dev="sockfs" ino=19912 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3187): Starting JXcore engine
,W/jxcore-log( 3187): Platform android
W/jxcore-log( 3187): 
W/jxcore-log( 3187): Process ARCH arm
W/jxcore-log( 3187): 
,I/jxcore-log( 3187): JXcore Cordova bridge is ready!
I/jxcore-log( 3187): 
W/jxcore-log( 3187): JXcore engine is started
,I/jxcore-log( 3187): Toggling radios to true
I/jxcore-log( 3187): 
,D/BluetoothAdapter( 3187): enable(): BT is already enabled..!
,D/WifiService(  760): New client listening to asynchronous messages
,D/WifiService(  760): setWifiEnabled: true pid=3187, uid=10270
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3187): Radios toggled
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): My device name is: LGE-Nexus 5
I/jxcore-log( 3187): 
,I/wpa_supplicant(  984): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
E/WifiStateMachine(  760): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  760): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1561): Read error: ssl=0xb4194e00: I/O error during system call, Connection timed out
V/NativeCrypto( 1561): SSL shutdown failed: ssl=0xb4194e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  760): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  760): Start Disconnecting Watchdog 1
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/wpa_supplicant(  984): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  760): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  760): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
D/Nat464Xlat(  760): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  760): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityManager.CallbackHandler( 1620): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Disconnected - quitting
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  760): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1245): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  760): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiNetworkAgent(  760): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  984): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  984): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  984): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  984): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  760): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  178): Setting iface cfg
,E/WifiStateMachine(  760): Start Dhcp Watchdog 2
,E/native  (  760): do suspend false
,E/WifiStateMachine(  760): scanCount==0 - aborting
,I/dhcpcd  ( 3282): version 5.5.6 starting
E/dhcpcd  ( 3282): get_duid: Read-only file system
,I/dhcpcd  ( 3282): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3282): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3282): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  760): do suspend true
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  760): Adding iface wlan0 to network 101
,E/WifiStateMachine(  760): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  760): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  760): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  760): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  760): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  760): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  760): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  760): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1620): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Feb 2016 16:52:28 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454950348829], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454950348813]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Validated
,D/ConnectivityService(  760): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  760): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1620): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1245): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/CAR.SERVICE( 3130): mConnectedToCar = false, abort
,E/ActivityThread( 3130): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@8520ea6 that was originally bound here
E/ActivityThread( 3130): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@8520ea6 that was originally bound here
E/ActivityThread( 3130): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3130): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3130): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3130): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3130): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3130): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3130): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3130): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3130): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3130): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3130): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3130): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3130): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3130): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3130): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3130): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3130): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3130): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3130): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3130): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3130): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3130): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3130): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3130): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@d657e39 that was originally bound here
E/ActivityThread( 3130): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@d657e39 that was originally bound here
E/ActivityThread( 3130): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3130): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3130): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3130): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3130): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3130): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3130): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3130): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3130): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3130): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3130): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3130): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3130): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3130): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3130): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3130): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3130): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3130): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3130): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3130): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3130): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3130): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  760): Unbind failed: could not find connection for android.os.BinderProxy@314fc749
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1620): CM callback handler got msg 524295
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2702): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  760): No APN found to select.
,V/MusicLeanback( 2702): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2702): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  760): No APN found to select.
,I/SystemUpdateService( 1620): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1620): onCreate
,D/SystemUpdateService( 1620): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1620): active receiver: enabled
,I/SystemUpdateService( 1620): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
V/SystemUpdateService( 1620): retry (wakeup: false) in 3599984 ms
,I/ActivityManager(  760): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3335 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  760): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/SystemUpdateService( 1620): onDestroy
,I/GAv4    ( 3335): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3335):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3335):   adb logcat -s GAv4
,W/GAv4    ( 3335): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3335): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3335): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3335): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3335): Time to load native libraries: 1 ms (timestamps 2464-2465)
I/LibraryLoader( 3335): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3335): Binding Chromium to main looper Looper (main, tid 1) {35bcc483}
,I/LibraryLoader( 3335): Expected native library version number "",actual native library version number ""
I/chromium( 3335): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3335): Initializing chromium process, singleProcess=true
W/art     ( 3335): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3335): ApplicationContext is null in ApplicationStatus
,W/chromium( 3335): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3335): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3335): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3335): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3335): Starting up...
,I/ActivityManager(  760): Killing 2665:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/AudioManagerAndroid( 3335): Requires BLUETOOTH permission
,W/libprocessgroup(  760): failed to open /acct/uid_10003/pid_2665/cgroup.procs: No such file or directory
,V/MusicLeanback( 2702): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/SystemUpdateService( 1620): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1620): onCreate
D/SystemUpdateService( 1620): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1620): active receiver: enabled
,I/SystemUpdateService( 1620): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1620): retry (wakeup: false) in 3599990 ms
,D/SystemUpdateService( 1620): onDestroy
,I/jxcore-log( 3187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3187): 
,I/jxcore-log( 3187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3187): 
I/jxcore-log( 3187): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3187): 
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2702): type=WIFI subType= reason=null isConnected=true
V/MusicLeanback( 2702): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1620): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1620): onCreate
,D/SystemUpdateService( 1620): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1620): active receiver: enabled
,I/SystemUpdateService( 1620): showing system update notification
,E/GpsLocationProvider(  760): No APN found to select.
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1620): retry (wakeup: false) in 3599968 ms
,D/SystemUpdateService( 1620): onDestroy
,V/GLSActivity( 1561): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1561): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3187): Test app app.js loaded
I/jxcore-log( 3187): 
,I/chromium( 3187): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3187): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7785482 added. We now have 1 listener(s)
,I/jxcore-log( 3187): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3187): 
,D/Finsky  ( 2569): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2569): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,W/ProcessCpuTracker(  760): Skipping unknown process pid 3438
W/ProcessCpuTracker(  760): Skipping unknown process pid 3441
,V/GLSActivity( 1561): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1561): Vacuum at: now=1454950374689 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1561): disconnect managed GoogleApiClient
,I/jxcore-log( 3187): --= Surplus to requirements =--
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ****TEST TOOK:  ms ****
I/jxcore-log( 3187): 
I/jxcore-log( 3187): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3187): 
,D/AndroidRuntime( 3490): 
D/AndroidRuntime( 3490): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3490): CheckJNI is OFF
,D/AndroidRuntime( 3490): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  760): Killing 3187:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  760): WIN DEATH: Window{7ec884a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  760): Client connection lost with reason: 4
,W/PackageSettings(  760): Skipping PackageSetting{2d94057d com.example.hello/10278} due to missing metadata
,I/ActivityManager(  760):   Force finishing activity ActivityRecord{3ce4bab7 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  760): Spurious death for ProcessRecord{32c5714b 3187:com.test.thalitest/u0a270}, curProc for 3187: null
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  760):   Force finishing activity ActivityRecord{3ce4bab7 u0 com.test.thalitest/.MainActivity t216 f}
W/ActivityManager(  760): Duplicate finish request for ActivityRecord{3ce4bab7 u0 com.test.thalitest/.MainActivity t216 f}
,W/GeofencerStateMachine( 1561): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1305): Explicit concurrent mark sweep GC freed 3922(292KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 7.575ms total 59.245ms
,I/Keyboard.Facilitator( 1100): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1100): run()
,I/Decoder ( 1100): createOrResetDecoder
D/VoicemailCleanupService( 2846): Cleaning up data for package: com.test.thalitest
,I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  944): Initialized EGL, version 1.4
I/art     (  760): Explicit concurrent mark sweep GC freed 54541(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 14.982ms total 106.553ms
,I/art     (  760): WaitForGcToComplete blocked for 91.639ms for cause Explicit
,D/OpenGLRenderer(  944): Enabling debug mode 0
,I/art     ( 1420): Explicit concurrent mark sweep GC freed 10242(700KB) AllocSpace objects, 1(39KB) LOS objects, 24% free, 19MB/25MB, paused 317us total 116.116ms
,I/ConfigService( 1561): onCreate
,I/UpdateIcingCorporaServi( 1420): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1305): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@16a5b1be new=com.google.android.velvet.VelvetApplication@16a5b1be
,I/art     ( 1620): Explicit concurrent mark sweep GC freed 5666(277KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 505us total 156.920ms
,I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3532 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/art     (  760): Explicit concurrent mark sweep GC freed 6047(317KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 2.815ms total 97.249ms
,W/InputMethodManagerService(  760): Got RemoteException sending setActive(false) notification to pid 3187 uid 10270
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1100): run()
,I/Keyboard.Facilitator( 1100): onFinishInput()
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  760): removeObsoleteFile: deleting file=216_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1100): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1100): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1100): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1100): run()
I/StatsUtilsManager( 1100): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1100): shouldRecordStats() = Too Soon
,W/ContextImpl( 3532): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1620): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1620): Clearing selected account for com.test.thalitest
,I/UpdateIcingCorporaServi( 1420): UpdateCorporaTask done [took 146 ms] updated apps [took 146 ms] 
,D/ChimeraCfgMgr( 1620): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1620): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1620): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1620): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  760): Killing 2640:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  760): Client connection lost with reason: 4
,D/AndroidRuntime( 3490): Shutting down VM
,E/NetworkScheduler.SchedulerReceiver( 1561): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1561): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_2640/cgroup.procs: No such file or directory
,I/Launcher( 1305): Deferring update until onResume
,I/LocationSettingsChecker( 1620): Removing dialog suppression flag for package com.test.thalitest
,W/ResourcesManager( 1305): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1620): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1620): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1620): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1620): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1620): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1620): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1620): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
W/ResourcesManager( 1305): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1620): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1620): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1620): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1620): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1620): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1620): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/Launcher( 1305): Deferring update until onResume
,I/ActivityManager(  760): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3564 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,W/BaseAppContext( 1620): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1620): App measurement is starting up, version: 8489
,I/GMPM-SVC( 1620): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1620): Using Auth Proxy for data requests.
,I/Icing   ( 1620): doRemovePackageData com.test.thalitest
,I/ActivityManager(  760): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3590 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 2511:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2511/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 1944:com.google.android.calendar/u0a31 (adj 15): empty #17

```
