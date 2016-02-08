#### Test 58380500055030c_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3075): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3075):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3075):   adb logcat -s GAv4
W/GAv4    ( 3075): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/Finsky  ( 2605): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1578): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1578): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1578): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAv4    ( 3075): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3075): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3075): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2605): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3075): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3075): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 3075): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3075): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3075): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1578): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1578): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/qtaguid ( 2605): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2605): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2605): untagSocket(37) failed with errno -22
D/Finsky  ( 2605): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
I/Icing   ( 1634): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
V/GLSActivity( 1578): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  737): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3140 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/ResourcesManager( 3140): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3140): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/Icing   ( 1634): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1634): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/MultiDex( 3140): VM with version 2.1.0 has multidex support
I/MultiDex( 3140): install
I/MultiDex( 3140): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 3140): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/Icing   ( 1634): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
W/ActivityThread( 3140): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3140): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@da9a03: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3140): Installed default security provider GmsCore_OpenSSL
I/qtaguid ( 2605): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2605): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2605): untagSocket(37) failed with errno -22
D/WearableService( 1578): callingUid 10008, callindPid: 1578
E/MDM     ( 1578): [226] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 1634): Restart initialization of location
D/AuthorizationBluetoothService( 1578): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/ChimeraCfgMgr( 3140): Reading stored module config
V/GLSActivity( 1578): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1578): No location to return for getLastLocation()
W/FusedLocationProvider( 1578): location=null
D/ChimeraCfgMgr( 3140): Loading module com.google.android.gms.car from APK com.google.android.gms
D/CAR.SERVICE( 3140): Connecting to CarCallService...
I/art     ( 3140): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3140): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.SERVICE( 3140): com.google.android.projection.gearhead isn't installed.
D/CAR.TEL.Service( 3140): Creating a new CarCallService.
D/NativeLibraryUtils( 3140): Install completed successfully. count=14 extracted=0
D/CAR.TEL.PhoneAdapter( 3140): Creating a new PhoneAdapter instance
W/ActivityManager(  737): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3140): setListener: com.google.android.gms.car.dn@15dea4ae
W/ActivityManager(  737): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3140): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3140): Starting CarCallService with initial phone null
D/CAR.SERVICE( 3140): Package validated; name: com.android.vending
V/Finsky  ( 2605): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1578): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/qtaguid ( 2605): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2605): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2605): untagSocket(37) failed with errno -22
D/AndroidRuntime( 3186): 
D/AndroidRuntime( 3186): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3186): CheckJNI is OFF
D/AndroidRuntime( 3186): Calling main entry com.android.commands.am.Am
I/ActivityManager(  737): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
W/ResourcesManager( 2605): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2605): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  737): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3213 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3186): Shutting down VM
V/ActivityManager(  737): Display changed displayId=0
I/WebViewFactory( 3213): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3213): Time to load native libraries: 1 ms (timestamps 6644-6645)
I/LibraryLoader( 3213): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3213): Binding Chromium to main looper Looper (main, tid 1) {21449b69}
I/LibraryLoader( 3213): Expected native library version number "",actual native library version number ""
I/chromium( 3213): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/ResourcesManager( 2605): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/Finsky  ( 2605): [1] DailyHygiene.access$600: Logging device features
,I/BrowserStartupController( 3213): Initializing chromium process, singleProcess=true
,W/art     ( 3213): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3213): ApplicationContext is null in ApplicationStatus
,W/chromium( 3213): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3213): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3213): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,D/DeviceConnectionService( 1578): client connected with version: 8296000
I/Adreno-EGL( 3213): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/Finsky  ( 2605): [266] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1578): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2605): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2605): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/BluetoothManagerService(  737): Message: 20
,W/art     ( 3213): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3213): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3213): CordovaWebView is running on device made by: LGE
,W/art     ( 3213): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3213): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     (  737): Explicit concurrent mark sweep GC freed 18984(859KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.051ms total 95.275ms
D/BluetoothManagerService(  737): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6f62982:true
,D/OpenGLRenderer( 3213): Render dirty regions requested: true
,D/Atlas   ( 3213): Validating map...
,W/chromium( 3213): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3213): Initialized EGL, version 1.4
,I/ActivityManager(  737): Killing 2577:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
D/OpenGLRenderer( 3213): Enabling debug mode 0
,W/IInputConnectionWrapper( 3213): showStatusIcon on inactive InputConnection
,W/BindingManager( 3213): Cannot call determinedVisibility() - never saw a connection for the pid: 3213
,I/ActivityManager(  737): Killing 2055:com.google.android.deskclock/u0a38 (adj 15): empty #18
,D/JsMessageQueue( 3213): Set native->JS mode to OnlineEventsBridgeMode
,W/libprocessgroup(  737): failed to open /acct/uid_10069/pid_2577/cgroup.procs: No such file or directory
,W/libprocessgroup(  737): failed to open /acct/uid_10038/pid_2055/cgroup.procs: No such file or directory
,I/ActivityManager(  737): Displayed com.test.thalitest/.MainActivity: +533ms (total +46s310ms)
,D/jxcore_app_log( 3213): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342720
,I/chromium( 3213): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  737): Killing 2528:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  737): failed to open /acct/uid_10045/pid_2528/cgroup.procs: No such file or directory
,W/jxcore-log( 3213): Initializing JXcore engine
W/jxcore-log( 3213): JXcore engine is ready
,W/Thread-306( 3274): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7651]" dev="sockfs" ino=7651 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-306( 3274): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-306( 3274): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6608]" dev="sockfs" ino=6608 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-306( 3274): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20504]" dev="sockfs" ino=20504 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3213): Starting JXcore engine
,W/jxcore-log( 3213): Platform android
W/jxcore-log( 3213): 
W/jxcore-log( 3213): Process ARCH arm
W/jxcore-log( 3213): 
,I/jxcore-log( 3213): JXcore Cordova bridge is ready!
I/jxcore-log( 3213): 
,W/jxcore-log( 3213): JXcore engine is started
,I/jxcore-log( 3213): Toggling radios to true
I/jxcore-log( 3213): 
,D/BluetoothAdapter( 3213): enable(): BT is already enabled..!
,D/WifiService(  737): New client listening to asynchronous messages
,D/WifiService(  737): setWifiEnabled: true pid=3213, uid=10270
E/WifiService(  737): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3213): Radios toggled
I/jxcore-log( 3213): 
I/jxcore-log( 3213): My device name is: LGE-Nexus 5
I/jxcore-log( 3213): 
,I/wpa_supplicant(  993): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  737): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  737): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  737): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1578): Read error: ssl=0x9bb4de00: I/O error during system call, Connection timed out
V/NativeCrypto( 1578): SSL shutdown failed: ssl=0x9bb4de00: I/O error during system call, Broken pipe
,D/ConnectivityService(  737): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  737): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiConfigStore(  737): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  737): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  993): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/ConnectivityService(  737): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  737): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  737): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  737): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  737): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  737): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,E/native  (  737): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/ConnectivityService(  737): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  737): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524292
,D/Nat464Xlat(  737): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityManager.CallbackHandler( 1634): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  737): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  737): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/CSLegacyTypeTracker(  737): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  737): Disconnected - quitting
D/ConnectivityService(  737): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  737): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  737): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1252): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  737): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  993): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  993): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  993): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  993): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  737): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  737): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  737): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  737): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  737): Start Dhcp Watchdog 2
,E/native  (  737): do suspend false
,E/WifiStateMachine(  737): scanCount==0 - aborting
,I/dhcpcd  ( 3316): version 5.5.6 starting
,E/dhcpcd  ( 3316): get_duid: Read-only file system
,I/dhcpcd  ( 3316): wlan0: rebinding lease of 192.168.1.114
,D/CAR.SERVICE( 3140): mConnectedToCar = false, abort
,E/ActivityThread( 3140): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3ce50d6 that was originally bound here
E/ActivityThread( 3140): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3ce50d6 that was originally bound here
E/ActivityThread( 3140): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3140): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3140): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3140): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3140): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3140): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3140): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3140): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3140): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3140): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3140): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3140): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3140): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3140): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3140): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3140): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3140): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3140): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3140): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3140): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3140): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3140): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3140): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3140): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@4385929 that was originally bound here
E/ActivityThread( 3140): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@4385929 that was originally bound here
E/ActivityThread( 3140): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3140): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3140): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3140): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3140): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3140): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3140): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3140): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3140): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3140): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3140): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3140): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3140): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3140): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3140): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3140): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3140): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3140): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3140): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3140): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3140): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3140): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  737): Unbind failed: could not find connection for android.os.BinderProxy@1cc0a639
,I/dhcpcd  ( 3316): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3316): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  737): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  737): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  737): MasterInitialState.processMessage what=3
,D/Tethering(  737): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2736): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  737): No APN found to select.
,I/SystemUpdateService( 1634): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1634): onCreate
,D/SystemUpdateService( 1634): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1634): active receiver: enabled
,E/GpsLocationProvider(  737): No APN found to select.
,I/SystemUpdateService( 1634): showing system update notification
,I/iu.Environment( 1634): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1634): num queued entries: 0
,I/iu.UploadsManager( 1634): num updated entries: 0
I/iu.SyncManager( 1634): NEXT; no task
,I/Babel   ( 1887): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  737): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3362 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ValidateNoPeople(  737): skipping global notification
,V/SystemUpdateService( 1634): retry (wakeup: false) in 3599927 ms
,D/SystemUpdateService( 1634): onDestroy
,I/GAv4    ( 3362): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3362):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3362):   adb logcat -s GAv4
,W/GAv4    ( 3362): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3362): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3362): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/native  (  737): do suspend true
,D/ConnectivityService(  737): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  737): Adding iface wlan0 to network 101
,E/WifiStateMachine(  737): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  737): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  737): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  737): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  737): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  737): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  737): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  737): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  737): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  737): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  737):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  737): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  737): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  737): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  737): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  737): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  737): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  737): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::5255:27ff:fef0:fd0b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  737): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1634): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  737): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Feb 2016 22:32:29 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454970749756], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454970749738]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  737): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  737): Validated
,D/ConnectivityService(  737): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  737): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  737): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  737): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  737): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1634): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1252): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WebViewFactory( 3362): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3362): Time to load native libraries: 1 ms (timestamps 2447-2448)
I/LibraryLoader( 3362): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3362): Binding Chromium to main looper Looper (main, tid 1) {13be772d}
,I/LibraryLoader( 3362): Expected native library version number "",actual native library version number ""
I/chromium( 3362): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3362): Initializing chromium process, singleProcess=true
W/art     ( 3362): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3362): ApplicationContext is null in ApplicationStatus
,W/chromium( 3362): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3362): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3362): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3362): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3362): Requires BLUETOOTH permission
,I/NSApplication( 3362): Starting up...
,I/ActivityManager(  737): Killing 2709:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  737): failed to open /acct/uid_10003/pid_2709/cgroup.procs: No such file or directory
,V/MusicLeanback( 2736): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1634): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1634): onCreate
,D/SystemUpdateService( 1634): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1634): active receiver: enabled
,I/SystemUpdateService( 1634): showing system update notification
,I/iu.Environment( 1634): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1634): num queued entries: 0
,I/iu.UploadsManager( 1634): num updated entries: 0
,I/iu.SyncManager( 1634): NEXT; no task
,I/ValidateNoPeople(  737): skipping global notification
,V/SystemUpdateService( 1634): retry (wakeup: false) in 3599954 ms
,D/SystemUpdateService( 1634): onDestroy
,I/Babel   ( 1887): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3213): 
,D/ConnectivityService(  737): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3213): 
,D/ConnectivityService(  737): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  737): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2736): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2736): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1634): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1634): onCreate
,D/SystemUpdateService( 1634): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/GpsLocationProvider(  737): No APN found to select.
,I/SystemUpdateService( 1634): active receiver: enabled
,I/SystemUpdateService( 1634): showing system update notification
,I/ValidateNoPeople(  737): skipping global notification
,V/SystemUpdateService( 1634): retry (wakeup: false) in 3599985 ms
,D/SystemUpdateService( 1634): onDestroy
,I/jxcore-log( 3213): Test app app.js loaded
I/jxcore-log( 3213): 
,I/chromium( 3213): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2fe9541a added. We now have 1 listener(s)
,I/jxcore-log( 3213): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): TAP version 13
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 1 should be equal
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 2 should be equal
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 3 should be equal
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 4 should be equal
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 5 should be equal
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 6 should throw
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 7 should throw
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # #parseBeacons no beacons returns null
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 8 should be equal
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 9 should throw
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 10 should be equal
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # #parseBeacons addressBookCallback returns null for all
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 11 (unnamed assert)
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 12 should be equal
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 13 (unnamed assert)
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 14 (unnamed assert)
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # #parseBeacons with beacons both for and not for the user
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 15 (unnamed assert)
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,V/GLSActivity( 1578): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1578): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2605): [256] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2605): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1578): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1578): Vacuum at: now=1454970773778 tag=VacuumService
,I/PhenotypeConfigurator( 1578): Scheduling Phenotype for one-off execution 7160 seconds from now (1454970774181)
,D/GetConfigurationSnapshotOperation( 1578): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1578): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1578): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1578): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1578): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ClearcutLoggerApiImpl( 1578): disconnect managed GoogleApiClient
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # multiplex can send data
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 16 String should be length:200
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # enqueue and run in order
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 17 firstPromise setTimeout
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 18 firstPromise result
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 19 firstPromise testValue
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 20 secondPromise setTimeout
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 21 secondPromise result
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 22 secondPromise testValue
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 23 thirdPromise in promise
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 24 thirdPromise result
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 25 thirdPromise testValue
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # basic
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 26 sane
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # another
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 27 sane
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 28 should be equal
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 29 null
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 30 (unnamed assert)
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 31 should be equal
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 32 should not throw
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 33 (unnamed assert)
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 34 (unnamed assert)
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 35 should not throw
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 36 should be equal
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 37 should be equal
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # failed to extract public key because of corrupt pkcs12 file
,I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 38 should be equal
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # failed to get mobile documents path
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 39 should be equal
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 40 should be equal
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 41 should be equal
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 42 should be equal
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # #init should register the networkChanged event
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 43 should be equal
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # #startBroadcasting should throw on null device name,
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 44 should throw
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 45 should throw
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 46 should throw
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 47 should throw
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # #startBroadcasting should throw on negative port
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 48 should throw
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # #startBroadcasting should throw on too large port
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 49 should throw
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 50 should be equal
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 51 should be equal
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 52 should be equal
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 53 should be equal
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 54 should be equal
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 55 should be equal
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 56 should be equal
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 57 should be equal
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
,I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 58 should be equal
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 59 should be equal
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 60 should be equal
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 61 should be equal
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 62 should be equal
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 63 should be equal
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 64 should be equal
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 65 should be equal
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 66 should be equal
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): ok 67 should be equal
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ok 68 should be equal
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # setup
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3213): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2414eb4b added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970966719.3213
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): bind: Binding a new listener
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3213): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454970966719.3213","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3213): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): start: OK
I/io.jxcore.node.ConnectionHelper( 3213): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970966719.3213, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3213): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3213): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454970966719.3213","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454970966719.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454970966719.3213","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): setState: RUNNING_WIFI
,W/BluetoothAdapter( 3213): getBluetoothService() called with no BluetoothManagerCallback
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970966719.3213, mode: WIFI
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3213): onDiscoveryManagerStateChanged: RUNNING_WIFI
,I/io.jxcore.node.ConnectionHelper( 3213): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): Waiting for incoming connections...
,I/jxcore-log( 3213): ok 69 Should be able to call startBroadcasting without error
I/jxcore-log( 3213): 
,I/io.jxcore.node.ConnectionHelper( 3213): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3213): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3213): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3213): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3213): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3213): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3213): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3213): ok 70 Should be able to call stopBroadcasting without error
I/jxcore-log( 3213): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a44f127 added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970966785.3213
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): bind: Binding a new listener
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3213): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454970966785.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3213): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): start: OK
I/io.jxcore.node.ConnectionHelper( 3213): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970966785.3213, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3213): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3213): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454970966785.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454970966785.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454970966785.3213","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3213): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): start: Starting P2P device discovery...
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970966785.3213, mode: WIFI
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3213): onDiscoveryManagerStateChanged: RUNNING_WIFI
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3213): start: OK
I/jxcore-log( 3213): ok 71 Should be able to call startBroadcasting without error
I/jxcore-log( 3213): 
I/io.jxcore.node.ConnectionHelper( 3213): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3213): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3213): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3213): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3213): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3213): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3213): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3213): ok 72 Should be able to call stopBroadcasting without error
I/jxcore-log( 3213): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@318578c3 added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970966833.3213
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): bind: Binding a new listener
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3213): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454970966833.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3213): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): start: OK
I/io.jxcore.node.ConnectionHelper( 3213): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970966833.3213, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3213): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3213): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454970966833.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454970966833.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454970966833.3213","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3213): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): start: Starting P2P device discovery...
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970966833.3213, mode: WIFI
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/io.jxcore.node.ConnectionHelper( 3213): start: OK
I/jxcore-log( 3213): ok 73 Should be able to call startBroadcasting without error
I/jxcore-log( 3213): 
I/io.jxcore.node.ConnectionHelper( 3213): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): setState: NOT_STARTED
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3213): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3213): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3213): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): stop: Stopping services
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3213): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3213): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3213): clear
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3213): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3213): ok 74 Should be able to call stopBroadcasting without error
I/jxcore-log( 3213): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35bcde1f added. We now have 5 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970966881.3213
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): bind: Binding a new listener
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3213): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454970966881.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3213): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): start: OK
I/io.jxcore.node.ConnectionHelper( 3213): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3213): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970966881.3213, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3213): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3213): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454970966881.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454970966881.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454970966881.3213","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): startWifiPeerDiscovery: Wi-Fi Direct OK
I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970966881.3213, mode: WIFI
,I/io.jxcore.node.ConnectionHelper( 3213): start: OK
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3213): ok 75 Should be able to call startBroadcasting without error
I/jxcore-log( 3213): 
I/io.jxcore.node.ConnectionHelper( 3213): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): shutdown
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3213): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3213): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): stop: Stopping services
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3213): onConnectionManagerStateChanged: NOT_STARTED
I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3213): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3213): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3213): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3213): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3213): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 3213): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20db3d3b added. We now have 6 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970966918.3213
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): bind: Binding a new listener
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3213): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454970966918.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3213): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): start: OK
I/io.jxcore.node.ConnectionHelper( 3213): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970966918.3213, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3213): bind: Binding a new listener
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,W/BluetoothAdapter( 3213): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): Waiting for incoming connections...
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3213): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454970966918.3213","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454970966918.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454970966918.3213","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970966918.3213, mode: WIFI
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/io.jxcore.node.ConnectionHelper( 3213): start: OK
I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3213): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log( 3213): 
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: OK
I/io.jxcore.node.ConnectionHelper( 3213): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3213): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): onServerStopped
I/wpa_supplicant(  993): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3213): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3213): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): stop: Stopping services
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3213): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3213): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3213): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3213): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3213): ok 78 Should be able to call stopBroadcasting without error
I/jxcore-log( 3213): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11b67217 added. We now have 7 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970966954.3213
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): bind: Binding a new listener
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3213): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454970966954.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): start: OK
I/io.jxcore.node.ConnectionHelper( 3213): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3213): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3213): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970966954.3213, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3213): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3213): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454970966954.3213","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454970966954.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454970966954.3213","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: OK
I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970966954.3213, mode: WIFI
,I/io.jxcore.node.ConnectionHelper( 3213): start: OK
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3213): ok 79 Should be able to call startBroadcasting without error
I/jxcore-log( 3213): 
I/io.jxcore.node.ConnectionHelper( 3213): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3213): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): setState: NOT_STARTED
I/wpa_supplicant(  993): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3213): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 3213): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3213): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3213): clear
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3213): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery stopped successfully
I/jxcore-log( 3213): ok 80 Should be able to call stopBroadcasting without error
I/jxcore-log( 3213): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3213): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14a618b3 added. We now have 8 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970966983.3213,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): bind: Binding a new listener
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3213): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454970966983.3213","ra":"34:FC:EF:11:AE:67"},
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): start: OK
I/io.jxcore.node.ConnectionHelper( 3213): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 3213): onConnectionManagerStateChanged: RUNNING
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3213): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970966983.3213, mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3213): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onWifiStateChanged: State changed to 2,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3213): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454970966983.3213","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454970966983.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454970966983.3213","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/art     (  737): Explicit concurrent mark sweep GC freed 54387(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 746us total 57.424ms
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: OK
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970966983.3213, mode: WIFI
,I/io.jxcore.node.ConnectionHelper( 3213): start: OK
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3213): ok 81 Should be able to call startBroadcasting without error
I/jxcore-log( 3213): 
,I/io.jxcore.node.ConnectionHelper( 3213): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3213): stopProvideBluetoothMacAddressMode,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: NOT_INITIALIZED
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): restart: Cannot restart, because not initialized
I/io.jxcore.node.ConnectionHelper( 3213): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: STARTED
,I/io.jxcore.node.ConnectionHelper( 3213): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3213): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3213): clear,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3213): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3213): ok 82 Should be able to call stopBroadcasting without error
I/jxcore-log( 3213): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	,Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19df8d0f added. We now have 9 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3213): Service requests cleared successfully
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970967073.3213
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): bind: Binding a new listener
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3213): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454970967073.3213","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): start: OK
I/io.jxcore.node.ConnectionHelper( 3213): onConnectionManagerStateChanged: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3213): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970967073.3213, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): bind: Binding a new listener
W/BluetoothAdapter( 3213): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3213): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3213): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454970967073.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454970967073.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454970967073.3213","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): start: Starting P2P device discovery...,
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: OK
I/io.jxcore.node.ConnectionHelper( 3213): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970967073.3213, mode: WIFI
I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3213): ok 83 Should be able to call startBroadcasting without error
I/jxcore-log( 3213): 
I/io.jxcore.node.ConnectionHelper( 3213): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3213): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3213): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3213): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): stop: Stopping services
I/wpa_supplicant(  993): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: NOT_INITIALIZE,D
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3213): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3213): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3213): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3213): Service requests cleared successfully
I/jxcore-log( 3213): ok 84 Should be able to call stopBroadcasting without error
I/jxcore-log( 3213): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3591eb2b added. We now have 10 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): setDiscoveryMode: WIFI -> BLE_AND_WIFI
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970967109.3213
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): bind: Binding a new listener
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3213): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454970967109.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): start: OK
I/io.jxcore.node.ConnectionHelper( 3213): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3213): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970967109.3213, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): bind: Binding a new listener
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3213): bind: Binding a new listener
W/BluetoothAdapter( 3213): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3213): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454970967109.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454970967109.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454970967109.3213","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: OK
I/io.jxcore.node.ConnectionHelper( 3213): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970967109.3213, mode: WIFI
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3213): ok 85 Should be able to call startBroadcasting without error
I/jxcore-log( 3213): 
I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 3213): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3213): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3213): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3213): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): stop: Stopping P2P device discovery...
I/wpa_supplicant(  993): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3213): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3213): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3213): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery stopped successfully
I/jxcore-log( 3213): ok 86 Should be able to call stopBroadcasting without error
I/jxcore-log( 3213): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3213): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3213): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c20f07 added. We now have 11 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3213): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970967138.3213
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): bind: Binding a new listener
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3213): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454970967138.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): start: OK
I/io.jxcore.node.ConnectionHelper( 3213): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3213): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970967138.3213, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3213): bind: Binding a new listener
W/BluetoothAdapter( 3213): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): Waiting for incoming connections...
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3213): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1454970967138.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: {"pi":"34:FC:EF:11:AE:67","pn":"1454970967138.3213","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1454970967138.3213","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): setState: RUNNING_WIFI
I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1454970967138.3213, mode: WIFI
D/BluetoothManagerService(  737): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 3213): start: OK
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): start: OK
I/jxcore-log( 3213): ok 87 Should be able to call startBroadcasting without error
I/jxcore-log( 3213): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3213): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3213): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): shutdown
I/wpa_supplicant(  993): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3213): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3213): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3213): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3213): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 3213): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3213): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3213): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3213): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3213): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3213): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3213): Local services cleared successfully
I/jxcore-log( 3213): ok 88 Should be able to call stopBroadcasting without error
I/jxcore-log( 3213): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3213): Service requests cleared successfully
I/jxcore-log( 3213): # teardown
I/jxcore-log( 3213): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): Start timer timeout, starting now...
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3213): start: Cannot start, because not initialized
,I/ActivityManager(  737): Killing 2689:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  737): Client connection lost with reason: 4
,W/libprocessgroup(  737): failed to open /acct/uid_1000/pid_2689/cgroup.procs: No such file or directory
,I/ActivityManager(  737): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3632 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,W/bt-smp  ( 2088): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2088): Plain text(LSB ~ MSB) = 33 7d 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2088): Encrypted text(LSB ~ MSB) = a5 8f 45 c4 7a e0 02 30 69 88 4a 71 f6 04 b9 a8 
W/bt-btm  ( 2088): Stopping oneshot timer
,I/EventLogService( 1634): Aggregate from 1454969597235 (log), 1454969597235 (data)
,I/GAv4    ( 3632): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3632):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3632):   adb logcat -s GAv4
,W/GAv4    ( 3632): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3632): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3632): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  737): Killing 2548:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  737): failed to open /acct/uid_10070/pid_2548/cgroup.procs: No such file or directory
,I/UsageStatsService(  737): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3676): 
D/AndroidRuntime( 3676): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3676): CheckJNI is OFF
D/AndroidRuntime( 3676): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  737): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  737): Killing 3213:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
D/WifiService(  737): Client connection lost with reason: 4
I/WindowState(  737): WIN DEATH: Window{615bce u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  737): Skipping PackageSetting{3db7a16d com.example.hello/10278} due to missing metadata
I/ActivityManager(  737):   Force finishing activity ActivityRecord{29bb493b u0 com.test.thalitest/.MainActivity t216}
W/ActivityManager(  737): Spurious death for ProcessRecord{23a1c372 3213:com.test.thalitest/u0a270}, curProc for 3213: null
I/ActivityManager(  737): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/art     ( 1634): Explicit concurrent mark sweep GC freed 7260(408KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 22MB/30MB, paused 507us total 30.724ms
I/art     ( 1314): Explicit concurrent mark sweep GC freed 3963(294KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 637us total 22.602ms
I/art     ( 1378): Explicit concurrent mark sweep GC freed 13281(945KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 302us total 22.585ms
I/Keyboard.Facilitator( 1097): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1097): run()
I/InputReader(  737): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1578): Ignoring removeGeofence because network location is disabled.
I/Decoder ( 1097): createOrResetDecoder
I/art     (  737): Explicit concurrent mark sweep GC freed 14565(1076KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.546ms total 58.387ms
I/art     (  737): WaitForGcToComplete blocked for 17.306ms for cause Explicit
D/VoicemailCleanupService( 2857): Cleaning up data for package: com.test.thalitest
I/ConfigService( 1578): onCreate
I/UpdateIcingCorporaServi( 1378): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/Adreno-EGL(  948): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  948): Initialized EGL, version 1.4
W/Launcher( 1314): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2dc659ee new=com.google.android.velvet.VelvetApplication@2dc659ee
D/OpenGLRenderer(  948): Enabling debug mode 0
I/ActivityManager(  737): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3720 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  737): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  737): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  737): removeObsoleteFile: deleting file=216_task.xml
I/art     (  737): Explicit concurrent mark sweep GC freed 3878(209KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 967us total 104.787ms
W/InputMethodManagerService(  737): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@3dbca1a6 (uid=10034 pid=948)
I/Keyboard.Facilitator.MainLanguageModelLoader( 1097): run()
I/UpdateIcingCorporaServi( 1378): UpdateCorporaTask done [took 112 ms] updated apps [took 112 ms] 
W/ContextImpl( 3720): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/Keyboard.Facilitator.MainLanguageModelLoader( 1097): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1097): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1097): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1097): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1097): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1097): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1097): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1097): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1097): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1097): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1097): run()
I/StatsUtilsManager( 1097): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1097): shouldRecordStats() = Too Soon
D/ChimeraCfgMgr( 1634): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1634): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1634): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1634): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1634): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1634): Clearing selected account for com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1578): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1578): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/LocationSettingsChecker( 1634): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 1634): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1634): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1634): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1634): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1634): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1634): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1634): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1634): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1634): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1634): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1634): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1634): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1634): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/AndroidRuntime( 3676): Shutting down VM
I/ActivityManager(  737): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3751 uid=10039 gids={50039, 9997} abi=armeabi-v7a
W/BaseAppContext( 1634): Using Auth Proxy for data requests.
I/GMPM-SVC( 1634): App measurement is starting up, version: 8489
I/GMPM-SVC( 1634): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/BaseAppContext( 1634): Using Auth Proxy for data requests.
I/Icing   ( 1634): doRemovePackageData com.test.thalitest
I/ActivityManager(  737): Killing 1994:com.google.android.calendar/u0a31 (adj 15): empty #17
I/ActivityManager(  737): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3777 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
W/libprocessgroup(  737): failed to open /acct/uid_10031/pid_1994/cgroup.procs: No such file or directory
I/Launcher( 1314): Deferring update until onResume
W/ResourcesManager( 1314): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  737): Killing 1501:com.google.android.partnersetup/u0a13 (adj 15): empty #17
W/ResourcesManager( 1314): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1314): Deferring update until onResume
W/libprocessgroup(  737): failed to open /acct/uid_10013/pid_1501/cgroup.procs: No such file or directory
D/ExternalStorage( 3777): After updating volumes, found 1 active roots
W/ResourcesManager( 3075): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3075): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.

```
