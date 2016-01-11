#### Test 5497026186051be_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3099): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3099):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3099):   adb logcat -s GAv4
W/GAv4    ( 3099): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3099): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3099): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3099): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,D/Finsky  ( 2682): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3099): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3099): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  762): Killing 2492:com.google.android.youtube/u0a80 (adj 15): empty #17
D/AndroidRuntime( 3140): 
D/AndroidRuntime( 3140): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
V/JNIHelp ( 3099): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AndroidRuntime( 3140): CheckJNI is OFF
W/System  ( 3099): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3099): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  762): failed to open /acct/uid_10080/pid_2492/cgroup.procs: No such file or directory
V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3140): Calling main entry com.android.commands.am.Am
I/ActivityManager(  762): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  762): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3180 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3140): Shutting down VM
I/art     (  194): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 182us total 8.622ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 177us total 7.709ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 170us total 7.583ms
I/Icing   ( 1631): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
V/ActivityManager(  762): Display changed displayId=0
I/Icing   ( 1631): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1631): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1631): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/WebViewFactory( 3180): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3180): Time to load native libraries: 2 ms (timestamps 4591-4593)
I/LibraryLoader( 3180): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3180): Binding Chromium to main looper Looper (main, tid 1) {1d8a9977}
I/LibraryLoader( 3180): Expected native library version number "",actual native library version number ""
I/chromium( 3180): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3180): Initializing chromium process, singleProcess=true
W/art     ( 3180): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3180): ApplicationContext is null in ApplicationStatus
W/chromium( 3180): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3180): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3180): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3180): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  762): Message: 20
D/BluetoothManagerService(  762): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1afc0c48:true
W/art     ( 3180): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3180): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3180): CordovaWebView is running on device made by: LGE
W/art     ( 3180): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3180): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3180): Render dirty regions requested: true
D/Atlas   ( 3180): Validating map...
W/chromium( 3180): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3180): Initialized EGL, version 1.4
D/OpenGLRenderer( 3180): Enabling debug mode 0
W/BindingManager( 3180): Cannot call determinedVisibility() - never saw a connection for the pid: 3180
I/ActivityManager(  762): Displayed com.test.thalitest/.MainActivity: +543ms (total +52s938ms)
I/Keyboard.Facilitator( 1111): onFinishInput()
W/IInputConnectionWrapper( 3180): showStatusIcon on inactive InputConnection
D/JsMessageQueue( 3180): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3180): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3180): jxcore cordova android initializing
I/ActivityManager(  762): Killing 2075:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/libprocessgroup(  762): failed to open /acct/uid_10038/pid_2075/cgroup.procs: No such file or directory
,D/Finsky  ( 2682): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/jxcore-log( 3180): Initializing JXcore engine
W/jxcore-log( 3180): JXcore engine is ready
,W/jxcore-log( 3180): Starting JXcore engine
,W/.test.thalitest( 3180): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9385]" dev="sockfs" ino=9385 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3180): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3180): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9460]" dev="sockfs" ino=9460 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3180): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18893]" dev="sockfs" ino=18893 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3180): Platform android
W/jxcore-log( 3180): 
W/jxcore-log( 3180): Process ARCH arm
W/jxcore-log( 3180): 
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2682): Failed write_ctrl(u 37) res=-1 errno=22,
I/qtaguid ( 2682): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2682): untagSocket(37) failed with errno -22
,D/Finsky  ( 2682): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  762): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3268 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 3268): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3268): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3268): VM with version 2.1.0 has multidex support
I/MultiDex( 3268): install
I/MultiDex( 3268): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3268): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 2682): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2682): Untagging socket 37 failed errno=-22
,W/NetworkManagementSocketTagger( 2682): untagSocket(37) failed with errno -22
,W/ActivityThread( 3268): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3268): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@169cd461: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3268): Installed default security provider GmsCore_OpenSSL
,D/ChimeraCfgMgr( 3268): Reading stored module config
,D/WearableService( 1605): callingUid 10008, callindPid: 1605
,E/MDM     ( 1605): [229] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1605): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 1631): Restart initialization of location
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 3268): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/GCoreFlp( 1605): No location to return for getLastLocation()
,W/FusedLocationProvider( 1605): location=null
,I/jxcore-log( 3180): JXcore Cordova bridge is ready!
I/jxcore-log( 3180): 
,W/jxcore-log( 3180): JXcore engine is started
I/Choreographer( 3180): Skipped 120 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3180): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3180): Toggling radios to true
I/jxcore-log( 3180): 
,D/BluetoothAdapter( 3180): enable(): BT is already enabled..!
,D/WifiService(  762): New client listening to asynchronous messages
,D/WifiService(  762): setWifiEnabled: true pid=3180, uid=10270
E/WifiService(  762): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3180): Radios toggled
I/jxcore-log( 3180): 
,I/jxcore-log( 3180): My device name is: LGE-Nexus 5
I/jxcore-log( 3180): 
I/wpa_supplicant(  981): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,D/NativeLibraryUtils( 3268): Install completed successfully. count=14 extracted=0
,E/WifiStateMachine(  762): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  762): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
V/NativeCrypto( 1605): Read error: ssl=0x9d230000: I/O error during system call, Connection timed out
V/NativeCrypto( 1605): SSL shutdown failed: ssl=0x9d230000: I/O error during system call, Broken pipe
,D/ConnectivityService(  762): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/CAR.SERVICE( 3268): Connecting to CarCallService...
,E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  762): Start Disconnecting Watchdog 1
I/wpa_supplicant(  981): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  762): do suspend true
,I/art     ( 3268): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3268): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 3268): com.google.android.projection.gearhead isn't installed.
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  762): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  762): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  762): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler( 1631): CM callback handler got msg 524292
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  762): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1283): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  762): NetworkAgent: NetworkAgent channel lost
,D/CAR.TEL.Service( 3268): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 3268): Creating a new PhoneAdapter instance
,W/ActivityManager(  762): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3268): setListener: com.google.android.gms.car.dn@22d3faa4
W/ActivityManager(  762): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3268): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3268): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 3268): Package validated; name: com.android.vending
,V/Finsky  ( 2682): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/art     (  762): Explicit concurrent mark sweep GC freed 25494(1224KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.085ms total 53.738ms
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ElegantRequestDirector( 2682): I/O exception (javax.net.ssl.SSLException) caught when processing request: Write error: ssl=0xaff8f000: I/O error during system call, Broken pipe
I/ElegantRequestDirector( 2682): Retrying request
,W/Finsky  ( 2682): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: org.apache.http.conn.HttpHostConnectException: Connection to https://android.clients.google.com refused
D/Finsky  ( 2682): [1] DailyHygiene.access$600: Logging device features
,D/Finsky  ( 2682): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/DeviceConnectionService( 1605): client connected with version: 8296000
,D/Finsky  ( 2682): [272] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2682): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 2682): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  762): Killing 2644:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10069/pid_2644/cgroup.procs: No such file or directory
,I/wpa_supplicant(  981): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  981): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  981): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  981): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  762): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  762): Start Dhcp Watchdog 2
,E/native  (  762): do suspend false
,E/WifiStateMachine(  762): scanCount==0 - aborting
,I/dhcpcd  ( 3337): version 5.5.6 starting
,E/dhcpcd  ( 3337): get_duid: Read-only file system
,I/dhcpcd  ( 3337): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3337): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3337): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  762): do suspend true
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
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  762): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762):    accepting network in place of null
,D/CSLegacyTypeTracker(  762): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  762): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  762): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1631): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 11:28:43 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452511723961], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452511723944]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Validated
,D/ConnectivityService(  762): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  762): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1631): CM callback handler got msg 524290
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1283): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  762): MasterInitialState.processMessage what=3
,D/Tethering(  762): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2786): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 2786): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2786): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1631): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1631): onCreate
,D/SystemUpdateService( 1631): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1631): active receiver: enabled
,I/ActivityManager(  762): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3376 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  762): No APN found to select.
,I/SystemUpdateService( 1631): showing system update notification
,D/Nat464Xlat(  762): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  762): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,E/GpsLocationProvider(  762): No APN found to select.
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1631): CM callback handler got msg 524295
,I/ValidateNoPeople(  762): skipping global notification
,V/SystemUpdateService( 1631): retry (wakeup: false) in 3599907 ms
,D/SystemUpdateService( 1631): onDestroy
,D/ConnectivityService(  762): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/GAv4    ( 3376): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3376):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3376):   adb logcat -s GAv4
,W/GAv4    ( 3376): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3376): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3376): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3376): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3376): Time to load native libraries: 2 ms (timestamps 849-851)
I/LibraryLoader( 3376): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3376): Binding Chromium to main looper Looper (main, tid 1) {1b297d1}
I/LibraryLoader( 3376): Expected native library version number "",actual native library version number ""
I/chromium( 3376): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3376): Initializing chromium process, singleProcess=true
W/art     ( 3376): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3376): ApplicationContext is null in ApplicationStatus
,W/chromium( 3376): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3376): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3376): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3376): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3376): Starting up...
,W/AudioManagerAndroid( 3376): Requires BLUETOOTH permission
,I/ActivityManager(  762): Killing 2596:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10045/pid_2596/cgroup.procs: No such file or directory
,V/MusicLeanback( 2786): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1631): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1631): onCreate
,D/SystemUpdateService( 1631): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1631): active receiver: enabled
,I/SystemUpdateService( 1631): showing system update notification
,I/ValidateNoPeople(  762): skipping global notification
,V/SystemUpdateService( 1631): retry (wakeup: false) in 3599938 ms
,D/SystemUpdateService( 1631): onDestroy
,D/CAR.SERVICE( 3268): mConnectedToCar = false, abort
,E/ActivityThread( 3268): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@426f60c that was originally bound here
E/ActivityThread( 3268): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@426f60c that was originally bound here
E/ActivityThread( 3268): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3268): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3268): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3268): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3268): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3268): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3268): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3268): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3268): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3268): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3268): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3268): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3268): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3268): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3268): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3268): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3268): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3268): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3268): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3268): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3268): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3268): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3268): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3268): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@29b21537 that was originally bound here
E/ActivityThread( 3268): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@29b21537 that was originally bound here
E/ActivityThread( 3268): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3268): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3268): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3268): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3268): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3268): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3268): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3268): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3268): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3268): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3268): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3268): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3268): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3268): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3268): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3268): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3268): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3268): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3268): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3268): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3268): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3268): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  762): Unbind failed: could not find connection for android.os.BinderProxy@7df7b1a
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  762): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2786): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2786): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1631): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1631): onCreate
,D/SystemUpdateService( 1631): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1631): active receiver: enabled
,I/SystemUpdateService( 1631): showing system update notification
,I/ValidateNoPeople(  762): skipping global notification
,V/SystemUpdateService( 1631): retry (wakeup: false) in 3599977 ms
,D/SystemUpdateService( 1631): onDestroy
,E/GpsLocationProvider(  762): No APN found to select.
,I/jxcore-log( 3180): Test app app.js loaded
I/jxcore-log( 3180): 
,I/Choreographer( 3180): Skipped 375 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3180): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Finsky  ( 2682): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2682): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1605): Vacuum at: now=1452511751958 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1111): run()
I/Keyboard.Facilitator( 1111): flushDynamicLanguageModels()
,I/ConfigService( 1605): onCreate
,I/ConfigService( 1605): onDestroy
,I/ActivityManager(  762): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3534 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3534): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3534):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3534):   adb logcat -s GAv4
,W/GAv4    ( 3534): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3534): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3534): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  762): Killing 2765:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10003/pid_2765/cgroup.procs: No such file or directory
,I/ClearcutLoggerApiImpl( 1605): disconnect managed GoogleApiClient
,I/jxcore-log( 3180): --= Surplus to requirements =--
I/jxcore-log( 3180): 
I/jxcore-log( 3180): ****TEST TOOK:  ms ****
I/jxcore-log( 3180): 
I/jxcore-log( 3180): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3180): 
,D/AndroidRuntime( 3582): 
D/AndroidRuntime( 3582): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3582): CheckJNI is OFF
,D/AndroidRuntime( 3582): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  762): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  762): Killing 3180:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  762): WIN DEATH: Window{5ef1778 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  762): Client connection lost with reason: 4
,W/PackageSettings(  762): Skipping PackageSetting{13479a9b com.example.hello/10278} due to missing metadata
,I/ActivityManager(  762):   Force finishing activity ActivityRecord{3f3715ad u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  762): Spurious death for ProcessRecord{12ac04b1 3180:com.test.thalitest/u0a270}, curProc for 3180: null
I/ActivityManager(  762): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  762):   Force finishing activity ActivityRecord{3f3715ad u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  762): Duplicate finish request for ActivityRecord{3f3715ad u0 com.test.thalitest/.MainActivity t214 f}
,W/GeofencerStateMachine( 1605): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  762): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1312): Explicit concurrent mark sweep GC freed 7280(546KB) AllocSpace objects, 2(253KB) LOS objects, 38% free, 25MB/41MB, paused 229us total 37.574ms
,I/Keyboard.Facilitator( 1111): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1111): run()
,I/Adreno-EGL(  946): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  946): Initialized EGL, version 1.4
,D/OpenGLRenderer(  946): Enabling debug mode 0
,I/Decoder ( 1111): createOrResetDecoder
,D/VoicemailCleanupService( 1385): Cleaning up data for package: com.test.thalitest
,I/ConfigService( 1605): onCreate
,I/art     (  762): Explicit concurrent mark sweep GC freed 43580(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 1.708ms total 106.385ms
I/art     (  762): WaitForGcToComplete blocked for 29.574ms for cause Explicit
,I/art     ( 1358): Explicit concurrent mark sweep GC freed 11675(911KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 790us total 137.319ms
,I/art     ( 1631): Explicit concurrent mark sweep GC freed 5699(279KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 1.074ms total 153.374ms
,I/UpdateIcingCorporaServi( 1358): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1111): run()
,W/Launcher( 1312): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@37cfc9e4 new=com.google.android.velvet.VelvetApplication@37cfc9e4
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1111): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1111): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1111): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1111): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1111): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1111): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1111): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1111): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1111): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1111): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1111): run()
I/StatsUtilsManager( 1111): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1111): shouldRecordStats() = Too Soon
,I/ActivityManager(  762): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3625 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/art     (  762): Explicit concurrent mark sweep GC freed 5694(297KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.292ms total 124.088ms
,W/InputMethodManagerService(  762): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@13ff1b83 (uid=10034 pid=946)
,W/InputMethodManagerService(  762): Got RemoteException sending setActive(false) notification to pid 3180 uid 10270
,I/Keyboard.Facilitator( 1111): onFinishInput()
,I/UpdateIcingCorporaServi( 1358): UpdateCorporaTask done [took 119 ms] updated apps [took 118 ms] 
,W/ContextImpl( 3625): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1631): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1631): Clearing selected account for com.test.thalitest
,D/BackupManagerService(  762): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  762): Receieved: android.intent.action.PACKAGE_REMOVED
,D/ChimeraCfgMgr( 1631): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1631): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1631): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1631): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1631): Removing dialog suppression flag for package com.test.thalitest
,I/ActivityManager(  762): Killing 2740:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  762): Client connection lost with reason: 4
,D/gH_CompatibleDatabase( 1631): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1631): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1631): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1631): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1631): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1631): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1631): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1631): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1631): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1631): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1631): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1631): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1631): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/AndroidRuntime( 3582): Shutting down VM
,D/TaskPersister(  762): removeObsoleteFile: deleting file=214_task.xml
,W/libprocessgroup(  762): failed to open /acct/uid_1000/pid_2740/cgroup.procs: No such file or directory
,I/Launcher( 1312): Deferring update until onResume
,E/NetworkScheduler.SchedulerReceiver( 1605): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1605): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/ResourcesManager( 1312): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GMPM-SVC( 1631): App measurement is starting up, version: 8489
I/GMPM-SVC( 1631): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/ResourcesManager( 1312): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1312): Deferring update until onResume
,I/ActivityManager(  762): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3656 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/Icing   ( 1631): doRemovePackageData com.test.thalitest
,W/BaseAppContext( 1631): Using Auth Proxy for data requests.
,W/BaseAppContext( 1631): Using Auth Proxy for data requests.
,I/ActivityManager(  762): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3680 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  762): Killing 2615:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10070/pid_2615/cgroup.procs: No such file or directory
,I/ActivityManager(  762): Killing 2012:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10031/pid_2012/cgroup.procs: No such file or directory
,D/ExternalStorage( 3680): After updating volumes, found 1 active roots
,W/ResourcesManager( 3099): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3099): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.

```
