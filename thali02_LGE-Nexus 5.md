#### Test 57531243c766d4e_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/Finsky  ( 2584): [1] DfeNotificationManagerImpl.handleNotification: Handling notification type=[6], id=[EAMaEjQ2YWU3OGZiZWQzZGRkNzI6MyCx9rzzqCooBg]
V/GLSActivity( 1625): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1625): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GAv4    ( 3177): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3177):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3177):   adb logcat -s GAv4
W/GAv4    ( 3177): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3177): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3177): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3177): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
I/qtaguid ( 2584): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2584): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2584): untagSocket(37) failed with errno -22
D/Finsky  ( 2584): [1] DfeNotificationManagerImpl$3.onResponse: Notification [EAMaEjQ2YWU3OGZiZWQzZGRkNzI6MyCx9rzzqCooBg] successfully ack'd.
V/GLSActivity( 1625): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2584): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3177): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3177): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/qtaguid ( 2584): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2584): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2584): untagSocket(37) failed with errno -22
D/Finsky  ( 2584): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
V/JNIHelp ( 3177): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  761): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3236 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/System  ( 3177): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3177): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1625): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 3236): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3236): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 3236): VM with version 2.1.0 has multidex support
I/MultiDex( 3236): install
I/MultiDex( 3236): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 3236): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 3236): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3236): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3409d9a4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3236): Installed default security provider GmsCore_OpenSSL
D/ChimeraCfgMgr( 3236): Reading stored module config
D/WearableService( 1625): callingUid 10008, callindPid: 1625
E/MDM     ( 1625): [234] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1625): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 1648): Restart initialization of location
V/GLSActivity( 1625): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ChimeraCfgMgr( 3236): Loading module com.google.android.gms.car from APK com.google.android.gms
W/GCoreFlp( 1625): No location to return for getLastLocation()
W/FusedLocationProvider( 1625): location=null
D/CAR.SERVICE( 3236): Connecting to CarCallService...
D/NativeLibraryUtils( 3236): Install completed successfully. count=14 extracted=0
I/art     ( 3236): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3236): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/Icing   ( 1648): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/CAR.SERVICE( 3236): com.google.android.projection.gearhead isn't installed.
D/CAR.TEL.Service( 3236): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 3236): Creating a new PhoneAdapter instance
W/ActivityManager(  761): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3236): setListener: com.google.android.gms.car.dn@20cc3cc3
W/ActivityManager(  761): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3236): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3236): Starting CarCallService with initial phone null
I/Icing   ( 1648): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
D/CAR.SERVICE( 3236): Package validated; name: com.android.vending
I/Icing   ( 1648): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1648): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
V/Finsky  ( 2584): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/Finsky  ( 2584): [1] ContentSyncService$3.onMutationsApplied$12348bc5: App library has changed, requesting content sync.
,D/AndroidRuntime( 3291): 
D/AndroidRuntime( 3291): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3291): CheckJNI is OFF
D/AndroidRuntime( 3291): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3312 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3291): Shutting down VM
V/ActivityManager(  761): Display changed displayId=0
V/GLSActivity( 1625): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/WebViewFactory( 3312): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3312): Time to load native libraries: 1 ms (timestamps 7725-7726)
I/LibraryLoader( 3312): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3312): Binding Chromium to main looper Looper (main, tid 1) {2665f1b2}
,I/LibraryLoader( 3312): Expected native library version number "",actual native library version number ""
I/chromium( 3312): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3312): Initializing chromium process, singleProcess=true
W/art     ( 3312): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3312): ApplicationContext is null in ApplicationStatus
,W/chromium( 3312): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3312): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3312): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3312): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/qtaguid ( 2584): Failed write_ctrl(u 42) res=-1 errno=22
I/qtaguid ( 2584): Untagging socket 42 failed errno=-22
W/NetworkManagementSocketTagger( 2584): untagSocket(42) failed with errno -22
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@388f0989:true
,W/art     ( 3312): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3312): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3312): CordovaWebView is running on device made by: LGE
,W/art     ( 3312): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3312): Attempt to remove local handle scope entry from IRT, ignoring
,V/GLSActivity( 1625): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  761): Explicit concurrent mark sweep GC freed 16881(770KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 801us total 58.039ms
,D/OpenGLRenderer( 3312): Render dirty regions requested: true
,D/Atlas   ( 3312): Validating map...
,W/chromium( 3312): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3312): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3312): Enabling debug mode 0
,I/Keyboard.Facilitator( 1082): onFinishInput()
,W/BindingManager( 3312): Cannot call determinedVisibility() - never saw a connection for the pid: 3312
,W/IInputConnectionWrapper( 3312): showStatusIcon on inactive InputConnection
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +470ms (total +46s98ms)
,D/JsMessageQueue( 3312): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3312): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258391936
,I/chromium( 3312): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/qtaguid ( 2584): Failed write_ctrl(u 42) res=-1 errno=22
I/qtaguid ( 2584): Untagging socket 42 failed errno=-22
W/NetworkManagementSocketTagger( 2584): untagSocket(42) failed with errno -22
,W/ResourcesManager( 2584): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2584): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  761): Killing 1400:com.google.android.keep/u0a71 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10071/pid_1400/cgroup.procs: No such file or directory
,W/ResourcesManager( 2584): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2584): [1] DailyHygiene.access$600: Logging device features
,D/DeviceConnectionService( 1625): client connected with version: 8296000
D/Finsky  ( 2584): [257] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1625): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2584): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2584): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  761): Killing 2493:com.google.android.deskclock/u0a38 (adj 15): empty #17
,I/ActivityManager(  761): Killing 2752:com.qualcomm.timeservice/u0a76 (adj 15): empty #18
,W/libprocessgroup(  761): failed to open /acct/uid_10038/pid_2493/cgroup.procs: No such file or directory
,W/libprocessgroup(  761): failed to open /acct/uid_10076/pid_2752/cgroup.procs: No such file or directory
,W/jxcore-log( 3312): Initializing JXcore engine
W/jxcore-log( 3312): JXcore engine is ready
,W/Thread-311( 3370): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8404]" dev="sockfs" ino=8404 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-311( 3370): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-311( 3370): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9620]" dev="sockfs" ino=9620 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-311( 3370): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19433]" dev="sockfs" ino=19433 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3312): Starting JXcore engine
,W/jxcore-log( 3312): Platform android
W/jxcore-log( 3312): 
W/jxcore-log( 3312): Process ARCH arm
W/jxcore-log( 3312): 
,I/jxcore-log( 3312): JXcore Cordova bridge is ready!
I/jxcore-log( 3312): 
,W/jxcore-log( 3312): JXcore engine is started
,I/jxcore-log( 3312): Toggling radios to true
I/jxcore-log( 3312): 
,D/BluetoothAdapter( 3312): enable(): BT is already enabled..!
,D/WifiService(  761): New client listening to asynchronous messages
,D/WifiService(  761): setWifiEnabled: true pid=3312, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3312): Radios toggled
I/jxcore-log( 3312): 
,I/jxcore-log( 3312): My device name is: LGE-Nexus 5
I/jxcore-log( 3312): 
,I/wpa_supplicant( 1046): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  761): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1625): Read error: ssl=0x9ae92e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1625): SSL shutdown failed: ssl=0x9ae92e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=-3ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-3ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiStateMachine(  761): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1046): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  761): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  761): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler( 1648): CM callback handler got msg 524292
D/TelephonyNetworkFactory( 1233): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant( 1046): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1046): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1046): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1046): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  761): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
E/WifiStateMachine(  761): Start Dhcp Watchdog 2
,E/native  (  761): do suspend false
,E/WifiStateMachine(  761): scanCount==0 - aborting
,D/CAR.SERVICE( 3236): mConnectedToCar = false, abort
,E/ActivityThread( 3236): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@17079a41 that was originally bound here
E/ActivityThread( 3236): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@17079a41 that was originally bound here
E/ActivityThread( 3236): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3236): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3236): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3236): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3236): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3236): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3236): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3236): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3236): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3236): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3236): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3236): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3236): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3236): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3236): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3236): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3236): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3236): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3236): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3236): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3236): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3236): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3236): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3236): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1bbda072 that was originally bound here
E/ActivityThread( 3236): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1bbda072 that was originally bound here
E/ActivityThread( 3236): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3236): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3236): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3236): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3236): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3236): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3236): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3236): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3236): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3236): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3236): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3236): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3236): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3236): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3236): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3236): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3236): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3236): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3236): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3236): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3236): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3236): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  761): Unbind failed: could not find connection for android.os.BinderProxy@34715b9e
,I/dhcpcd  ( 3423): version 5.5.6 starting
E/dhcpcd  ( 3423): get_duid: Read-only file system
,I/dhcpcd  ( 3423): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3423): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3423): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
D/Tethering(  761): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2638): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1648): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1648): onCreate
,D/SystemUpdateService( 1648): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1648): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1648): active receiver: enabled
,I/iu.UploadsManager( 1648): num queued entries: 0
I/iu.UploadsManager( 1648): num updated entries: 0
I/iu.SyncManager( 1648): NEXT; no task
,I/ActivityManager(  761): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3461 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 2449): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1648): showing system update notification
,E/native  (  761): do suspend true
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  761): Adding iface wlan0 to network 101
E/WifiStateMachine(  761): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  761): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  761): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  761): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  761): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  761): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  761): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  761):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/CSLegacyTypeTracker(  761): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::5255:27ff:fef0:fd0b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1648): CM callback handler got msg 524290
,E/GpsLocationProvider(  761): No APN found to select.
,E/GpsLocationProvider(  761): No APN found to select.
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1648): retry (wakeup: false) in 3599894 ms
,D/SystemUpdateService( 1648): onDestroy
,I/GAv4    ( 3461): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3461):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3461):   adb logcat -s GAv4
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 29 Jan 2016 17:56:43 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454090203049], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454090203029]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Validated
D/ConnectivityService(  761): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1648): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1233): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/GAv4    ( 3461): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3461): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3461): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3461): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3461): Time to load native libraries: 2 ms (timestamps 3413-3415)
I/LibraryLoader( 3461): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3461): Binding Chromium to main looper Looper (main, tid 1) {1668f3d4}
I/LibraryLoader( 3461): Expected native library version number "",actual native library version number ""
I/chromium( 3461): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3461): Initializing chromium process, singleProcess=true
,W/art     ( 3461): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3461): ApplicationContext is null in ApplicationStatus
,W/chromium( 3461): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3461): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3461): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3461): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3461): Requires BLUETOOTH permission
,I/NSApplication( 3461): Starting up...
,I/ActivityManager(  761): Killing 2809:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2809/cgroup.procs: No such file or directory
,V/MusicLeanback( 2638): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1648): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1648): onCreate
,D/SystemUpdateService( 1648): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1648): active receiver: enabled
,I/SystemUpdateService( 1648): showing system update notification
,I/iu.Environment( 1648): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1648): num queued entries: 0
,I/iu.UploadsManager( 1648): num updated entries: 0
,I/iu.SyncManager( 1648): NEXT; no task
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1648): retry (wakeup: false) in 3599981 ms
,D/SystemUpdateService( 1648): onDestroy
,I/Babel   ( 2449): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3312): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3312): 
,D/ConnectivityService(  761): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3312): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3312): 
,I/jxcore-log( 3312): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3312): 
,I/jxcore-log( 3312): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3312): 
,I/jxcore-log( 3312): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3312): 
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2638): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2638): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1648): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1648): onCreate
D/SystemUpdateService( 1648): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1648): active receiver: enabled
,I/SystemUpdateService( 1648): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1648): retry (wakeup: false) in 3599988 ms
,D/SystemUpdateService( 1648): onDestroy
,E/GpsLocationProvider(  761): No APN found to select.
,W/SQLiteConnectionPool( 1648): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/jxcore-log( 3312): Test app app.js loaded
I/jxcore-log( 3312): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3312): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3312): BLE advertisement is supported
I/jxcore-log( 3312): 
,I/chromium( 3312): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/GLSActivity( 1625): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1625): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2584): [246] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2584): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1625): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1625): Vacuum at: now=1454090227496 tag=VacuumService
,I/PhenotypeConfigurator( 1625): Scheduling Phenotype for one-off execution 7359 seconds from now (1454090227938)
,D/GetConfigurationSnapshotOperation( 1625): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1625): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1625): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1625): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1625): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1082): run()
I/Keyboard.Facilitator( 1082): flushDynamicLanguageModels()
,I/ConfigService( 1625): onCreate
,I/art     ( 1625): Explicit concurrent mark sweep GC freed 113829(6MB) AllocSpace objects, 26(439KB) LOS objects, 39% free, 24MB/40MB, paused 899us total 63.984ms
,I/ConfigService( 1625): onDestroy
,I/ClearcutLoggerApiImpl( 1625): disconnect managed GoogleApiClient
,I/ActivityManager(  761): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3664 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3664): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3664):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3664):   adb logcat -s GAv4
,W/GAv4    ( 3664): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3664): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3664): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  761): Killing 2771:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  761): Client connection lost with reason: 4
,W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2771/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Killing 2516:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2516/cgroup.procs: No such file or directory
,W/bt-smp  ( 1923): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 1923): Plain text(LSB ~ MSB) = 9e 54 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1923): Encrypted text(LSB ~ MSB) = 40 43 c6 de 06 fa 40 d1 a5 54 15 40 0c 7a 06 9d 
,W/bt-btm  ( 1923): Stopping oneshot timer
,I/art     (  761): Explicit concurrent mark sweep GC freed 54751(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 1.155ms total 78.180ms
,I/UsageStatsService(  761): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
