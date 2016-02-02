#### Test 57924002d5e0b14_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1612): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1612): Module APK com.google.android.play.games already loaded
V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GAv4    ( 3043): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3043):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3043):   adb logcat -s GAv4
W/GAv4    ( 3043): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/qtaguid ( 2601): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2601): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2601): untagSocket(37) failed with errno -22
D/Finsky  ( 2601): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
W/GAv4    ( 3043): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3043): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3043): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
--------- beginning of system
I/ActivityManager(  760): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3084 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 3084): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3084): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 2601): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/MultiDex( 3084): VM with version 2.1.0 has multidex support
I/MultiDex( 3084): install
I/MultiDex( 3084): VM has multidex support, MultiDex support library is disabled.
W/ResourcesManager( 3043): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3043): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 3084): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
V/JNIHelp ( 3043): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3043): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3043): Installed default security provider GmsCore_OpenSSL
W/ActivityThread( 3084): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3084): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3c766e11: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3084): Installed default security provider GmsCore_OpenSSL
I/Icing   ( 1612): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/WearableService( 1566): callingUid 10008, callindPid: 1566
V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationInitializer( 1612): Restart initialization of location
E/MDM     ( 1566): [225] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1566): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/qtaguid ( 2601): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2601): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2601): untagSocket(37) failed with errno -22
V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ChimeraCfgMgr( 3084): Reading stored module config
D/ChimeraCfgMgr( 3084): Loading module com.google.android.gms.car from APK com.google.android.gms
W/GCoreFlp( 1566): No location to return for getLastLocation()
W/FusedLocationProvider( 1566): location=null
D/NativeLibraryUtils( 3084): Install completed successfully. count=14 extracted=0
D/CAR.SERVICE( 3084): Connecting to CarCallService...
I/art     ( 3084): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3084): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/Icing   ( 1612): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
D/CAR.SERVICE( 3084): com.google.android.projection.gearhead isn't installed.
D/CAR.TEL.Service( 3084): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 3084): Creating a new PhoneAdapter instance
W/ActivityManager(  760): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3084): setListener: com.google.android.gms.car.dn@802014
W/ActivityManager(  760): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3084): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3084): Starting CarCallService with initial phone null
D/CAR.SERVICE( 3084): Package validated; name: com.android.vending
I/Icing   ( 1612): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
V/Finsky  ( 2601): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/Icing   ( 1612): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/qtaguid ( 2601): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2601): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2601): untagSocket(37) failed with errno -22
,W/ResourcesManager( 2601): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2601): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 2601): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/Finsky  ( 2601): [1] DailyHygiene.access$600: Logging device features
D/DeviceConnectionService( 1566): client connected with version: 8296000
D/Finsky  ( 2601): [265] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2601): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2601): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/AndroidRuntime( 3145): 
D/AndroidRuntime( 3145): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3145): CheckJNI is OFF
D/AndroidRuntime( 3145): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3177 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3145): Shutting down VM
V/ActivityManager(  760): Display changed displayId=0
I/ActivityManager(  760): Killing 2571:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
I/WebViewFactory( 3177): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/ActivityManager(  760): Killing 2022:com.google.android.deskclock/u0a38 (adj 15): empty #18
,W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_2571/cgroup.procs: No such file or directory
,W/libprocessgroup(  760): failed to open /acct/uid_10038/pid_2022/cgroup.procs: No such file or directory
,I/LibraryLoader( 3177): Time to load native libraries: 3 ms (timestamps 8721-8724)
,I/LibraryLoader( 3177): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3177): Binding Chromium to main looper Looper (main, tid 1) {39c27ea7}
,I/LibraryLoader( 3177): Expected native library version number "",actual native library version number ""
,I/chromium( 3177): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3177): Initializing chromium process, singleProcess=true
,W/art     ( 3177): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3177): ApplicationContext is null in ApplicationStatus
,W/chromium( 3177): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3177): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3177): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3177): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
,D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6e66a17:true
,W/art     ( 3177): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3177): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3177): CordovaWebView is running on device made by: LGE
,W/art     ( 3177): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3177): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3177): Render dirty regions requested: true
,D/Atlas   ( 3177): Validating map...
,W/ActivityManager(  760): Activity pause timeout for ActivityRecord{2c6ef0c3 u0 com.test.thalitest/.MainActivity t216}
,I/art     (  760): Explicit concurrent mark sweep GC freed 21091(999KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 825us total 49.509ms
,W/chromium( 3177): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,I/OpenGLRenderer( 3177): Initialized EGL, version 1.4
D/OpenGLRenderer( 3177): Enabling debug mode 0
,W/IInputConnectionWrapper( 3177): showStatusIcon on inactive InputConnection
,I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +618ms (total +47s450ms)
,W/BindingManager( 3177): Cannot call determinedVisibility() - never saw a connection for the pid: 3177
,D/JsMessageQueue( 3177): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3177): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342720
,I/chromium( 3177): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  760): Killing 2509:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_2509/cgroup.procs: No such file or directory
,W/jxcore-log( 3177): Initializing JXcore engine
W/jxcore-log( 3177): JXcore engine is ready
,W/Thread-306( 3228): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8048]" dev="sockfs" ino=8048 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-306( 3228): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-306( 3228): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9510]" dev="sockfs" ino=9510 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-306( 3228): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19620]" dev="sockfs" ino=19620 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3177): Starting JXcore engine
,W/jxcore-log( 3177): Platform android
W/jxcore-log( 3177): 
W/jxcore-log( 3177): Process ARCH arm
W/jxcore-log( 3177): 
,I/jxcore-log( 3177): JXcore Cordova bridge is ready!
I/jxcore-log( 3177): 
W/jxcore-log( 3177): JXcore engine is started
,I/jxcore-log( 3177): Toggling radios to true
I/jxcore-log( 3177): 
,D/BluetoothAdapter( 3177): enable(): BT is already enabled..!
,D/WifiService(  760): New client listening to asynchronous messages
,D/WifiService(  760): setWifiEnabled: true pid=3177, uid=10270
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3177): Radios toggled,
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): My device name is: LGE-Nexus 5
I/jxcore-log( 3177): 
,I/wpa_supplicant(  986): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  760): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  760): do suspend true
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1566): Read error: ssl=0x9d762e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1566): SSL shutdown failed: ssl=0x9d762e00: I/O error during system call, Broken pipe
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  760): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  986): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/ConnectivityService(  760): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
E/native  (  760): do suspend true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): ValidatedState{ when=-6ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-6ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/ConnectivityService(  760): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  904): CM callback handler got msg 524292
D/Nat464Xlat(  760): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  760): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1612): CM callback handler got msg 524292
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  760): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1239): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Disconnected - quitting
,D/WifiNetworkAgent(  760): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  986): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  986): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  986): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  986): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  760): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  182): Setting iface cfg
E/WifiStateMachine(  760): Start Dhcp Watchdog 2
,E/native  (  760): do suspend false
,E/WifiStateMachine(  760): scanCount==0 - aborting
,D/CAR.SERVICE( 3084): mConnectedToCar = false, abort
,E/ActivityThread( 3084): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2eb39d7c that was originally bound here
E/ActivityThread( 3084): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2eb39d7c that was originally bound here
E/ActivityThread( 3084): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3084): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3084): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3084): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3084): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3084): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3084): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3084): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3084): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3084): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3084): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3084): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3084): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3084): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3084): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3084): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3084): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3084): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3084): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3084): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3084): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3084): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3084): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3084): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@12eaaa67 that was originally bound here
E/ActivityThread( 3084): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@12eaaa67 that was originally bound here
E/ActivityThread( 3084): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3084): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3084): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3084): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3084): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3084): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3084): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3084): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3084): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3084): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3084): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3084): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3084): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3084): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3084): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3084): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3084): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3084): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3084): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3084): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3084): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3084): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  760): Unbind failed: could not find connection for android.os.BinderProxy@2bb41ff6
,I/dhcpcd  ( 3262): version 5.5.6 starting
E/dhcpcd  ( 3262): get_duid: Read-only file system
,I/dhcpcd  ( 3262): wlan0: rebinding lease of 192.168.1.114
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
D/Tethering(  760): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2716): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1612): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1612): onCreate
,D/SystemUpdateService( 1612): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1612): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1612): active receiver: enabled
,I/iu.UploadsManager( 1612): num queued entries: 0
I/iu.UploadsManager( 1612): num updated entries: 0
,I/SystemUpdateService( 1612): showing system update notification
,I/Babel   ( 1882): connection state changed from CONNECTED to DISCONNECTED
,I/iu.SyncManager( 1612): NEXT; no task
,I/ActivityManager(  760): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3274 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  760): No APN found to select.
,E/GpsLocationProvider(  760): No APN found to select.
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1612): retry (wakeup: false) in 3599920 ms
,D/SystemUpdateService( 1612): onDestroy
,I/GAv4    ( 3274): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3274):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3274):   adb logcat -s GAv4
,W/GAv4    ( 3274): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3274): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3274): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/dhcpcd  ( 3262): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3262): wlan0: leased 192.168.1.114 for 86400 seconds
,I/WebViewFactory( 3274): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3274): Time to load native libraries: 1 ms (timestamps 4512-4513)
I/LibraryLoader( 3274): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3274): Binding Chromium to main looper Looper (main, tid 1) {3935908b}
,I/LibraryLoader( 3274): Expected native library version number "",actual native library version number ""
I/chromium( 3274): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3274): Initializing chromium process, singleProcess=true
W/art     ( 3274): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3274): ApplicationContext is null in ApplicationStatus
,W/chromium( 3274): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3274): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3274): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3274): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3274): Starting up...
,W/AudioManagerAndroid( 3274): Requires BLUETOOTH permission
,I/ActivityManager(  760): Killing 2693:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,E/native  (  760): do suspend true
,W/libprocessgroup(  760): failed to open /acct/uid_10003/pid_2693/cgroup.procs: No such file or directory
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  760): Adding iface wlan0 to network 101
,E/WifiStateMachine(  760): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/ConnectivityService(  760): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  760): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  760): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  760): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  760): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  760): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  760): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  904): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1612): CM callback handler got msg 524290
,V/MusicLeanback( 2716): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1612): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1612): onCreate
,D/SystemUpdateService( 1612): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/jxcore-log( 3177): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3177): 
,I/SystemUpdateService( 1612): active receiver: enabled
I/SystemUpdateService( 1612): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,I/iu.Environment( 1612): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1612): num queued entries: 0
,I/iu.UploadsManager( 1612): num updated entries: 0
I/iu.SyncManager( 1612): NEXT; no task
,V/SystemUpdateService( 1612): retry (wakeup: false) in 3599991 ms
,D/SystemUpdateService( 1612): onDestroy
,W/art     ( 2858): Suspending all threads took: 11.754ms
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 19:17:42 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454440662913], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454440662896]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Validated
D/ConnectivityService(  760): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  904): CM callback handler got msg 524290
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1239): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1612): CM callback handler got msg 524290
,I/Babel   ( 1882): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3177): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3177): 
,I/jxcore-log( 3177): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3177): 
,D/ConnectivityService(  760): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2716): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  760): No APN found to select.
,V/MusicLeanback( 2716): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1612): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1612): onCreate
,D/SystemUpdateService( 1612): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1612): active receiver: enabled
,I/SystemUpdateService( 1612): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1612): retry (wakeup: false) in 3599979 ms
,D/SystemUpdateService( 1612): onDestroy
,I/jxcore-log( 3177): Test app app.js loaded
I/jxcore-log( 3177): 
,I/chromium( 3177): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3177): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3177): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3177): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3177): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3177): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3177): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3177): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3177): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3177): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3177): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a78f3e added. We now have 1 listener(s)
,I/jxcore-log( 3177): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3177): 
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2601): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2601): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1566): Vacuum at: now=1454440685310 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1566): disconnect managed GoogleApiClient
,I/ActivityManager(  760): Killing 2674:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  760): Client connection lost with reason: 4
,W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_2674/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3496 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3496): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3496):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3496):   adb logcat -s GAv4
,W/GAv4    ( 3496): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3496): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3496): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  760): Killing 2548:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2548/cgroup.procs: No such file or directory
,W/bt-smp  ( 2053): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2053): Plain text(LSB ~ MSB) = ca 5a 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2053): Encrypted text(LSB ~ MSB) = 46 9c 48 8d 91 fe 15 3e db 90 e6 c1 76 51 8e 6d 
,W/bt-btm  ( 2053): Stopping oneshot timer
,I/PhenotypeConfigurator( 1566): Scheduling Phenotype for one-off execution 13342 seconds from now (1454441563379)
,D/GetConfigurationSnapshotOperation( 1566): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1566): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1566): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UsageStatsService(  760): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
