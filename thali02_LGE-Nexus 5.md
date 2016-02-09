#### Test 58751238ee11130_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1598): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1598): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3039): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3039):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3039):   adb logcat -s GAv4
W/GAv4    ( 3039): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3039): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3039): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3039): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2620): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3039): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3039): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/JNIHelp ( 3039): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3039): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3039): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/qtaguid ( 2620): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2620): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2620): untagSocket(37) failed with errno -22
D/Finsky  ( 2620): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
I/ActivityManager(  735): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3094 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 3094): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3094): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 3094): VM with version 2.1.0 has multidex support
I/MultiDex( 3094): install
I/MultiDex( 3094): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 3094): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 3094): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3094): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@104b973b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3094): Installed default security provider GmsCore_OpenSSL
I/Icing   ( 1598): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/ChimeraCfgMgr( 3094): Reading stored module config
D/WearableService( 1566): callingUid 10008, callindPid: 1566
E/MDM     ( 1566): [225] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1566): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 1598): Restart initialization of location
I/qtaguid ( 2620): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2620): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2620): untagSocket(37) failed with errno -22
D/ChimeraCfgMgr( 3094): Loading module com.google.android.gms.car from APK com.google.android.gms
V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1566): No location to return for getLastLocation()
W/FusedLocationProvider( 1566): location=null
I/Icing   ( 1598): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1598): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
D/NativeLibraryUtils( 3094): Install completed successfully. count=14 extracted=0
D/CAR.SERVICE( 3094): Connecting to CarCallService...
I/Icing   ( 1598): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/art     ( 3094): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3094): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.SERVICE( 3094): com.google.android.projection.gearhead isn't installed.
D/CAR.TEL.Service( 3094): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 3094): Creating a new PhoneAdapter instance
W/ActivityManager(  735): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3094): setListener: com.google.android.gms.car.dn@2c962346
W/ActivityManager(  735): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3094): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3094): Starting CarCallService with initial phone null
D/CAR.SERVICE( 3094): Package validated; name: com.android.vending
V/Finsky  ( 2620): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/qtaguid ( 2620): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2620): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2620): untagSocket(37) failed with errno -22
D/AndroidRuntime( 3142): 
D/AndroidRuntime( 3142): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3142): CheckJNI is OFF
W/ResourcesManager( 2620): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/AndroidRuntime( 3142): Calling main entry com.android.commands.am.Am
W/ResourcesManager( 2620): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  735): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  735): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3163 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3142): Shutting down VM
V/ActivityManager(  735): Display changed displayId=0
I/WebViewFactory( 3163): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3163): Time to load native libraries: 2 ms (timestamps 6902-6904)
I/LibraryLoader( 3163): Expected native library version number "",actual native library version number ""
W/ResourcesManager( 2620): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/WebViewChromiumFactoryProvider( 3163): Binding Chromium to main looper Looper (main, tid 1) {1a285d61}
I/LibraryLoader( 3163): Expected native library version number "",actual native library version number ""
I/chromium( 3163): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/Finsky  ( 2620): [1] DailyHygiene.access$600: Logging device features
I/BrowserStartupController( 3163): Initializing chromium process, singleProcess=true
W/art     ( 3163): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3163): ApplicationContext is null in ApplicationStatus
D/DeviceConnectionService( 1566): client connected with version: 8296000
D/Finsky  ( 2620): [265] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,W/chromium( 3163): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/libEGL  ( 3163): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3163): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3163): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/Finsky  ( 2620): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2620): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2fa11b8c:true
,W/art     ( 3163): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     (  735): Explicit concurrent mark sweep GC freed 19340(871KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 815us total 49.547ms
,W/AwContents( 3163): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3163): CordovaWebView is running on device made by: LGE
,W/art     ( 3163): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3163): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3163): Render dirty regions requested: true
,D/Atlas   ( 3163): Validating map...
,W/chromium( 3163): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3163): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3163): Enabling debug mode 0
,I/ActivityManager(  735): Killing 2585:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,I/Keyboard.Facilitator( 1046): onFinishInput()
,W/BindingManager( 3163): Cannot call determinedVisibility() - never saw a connection for the pid: 3163
,W/IInputConnectionWrapper( 3163): showStatusIcon on inactive InputConnection
,I/ActivityManager(  735): Killing 2071:com.google.android.deskclock/u0a38 (adj 15): empty #18
,D/JsMessageQueue( 3163): Set native->JS mode to OnlineEventsBridgeMode
,W/libprocessgroup(  735): failed to open /acct/uid_10038/pid_2071/cgroup.procs: No such file or directory
,W/libprocessgroup(  735): failed to open /acct/uid_10069/pid_2585/cgroup.procs: No such file or directory
,I/ActivityManager(  735): Displayed com.test.thalitest/.MainActivity: +583ms (total +46s968ms)
,D/jxcore_app_log( 3163): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258381056
,I/chromium( 3163): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  735): Killing 2537:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/jxcore-log( 3163): Initializing JXcore engine
W/jxcore-log( 3163): JXcore engine is ready
,W/libprocessgroup(  735): failed to open /acct/uid_10045/pid_2537/cgroup.procs: No such file or directory
,W/Thread-306( 3224): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8340]" dev="sockfs" ino=8340 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-306( 3224): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-306( 3224): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8497]" dev="sockfs" ino=8497 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-306( 3224): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17882]" dev="sockfs" ino=17882 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3163): Starting JXcore engine
,W/jxcore-log( 3163): Platform android
W/jxcore-log( 3163): 
W/jxcore-log( 3163): Process ARCH arm
W/jxcore-log( 3163): 
,I/jxcore-log( 3163): JXcore Cordova bridge is ready!
I/jxcore-log( 3163): 
W/jxcore-log( 3163): JXcore engine is started
,I/jxcore-log( 3163): Toggling radios to true
I/jxcore-log( 3163): 
,D/BluetoothAdapter( 3163): enable(): BT is already enabled..!
,D/WifiService(  735): New client listening to asynchronous messages
,D/WifiService(  735): setWifiEnabled: true pid=3163, uid=10270
E/WifiService(  735): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3163): Radios toggled
I/jxcore-log( 3163): 
,I/jxcore-log( 3163): My device name is: LGE-Nexus 5
I/jxcore-log( 3163): 
,I/wpa_supplicant( 1035): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  735): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  735): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1566): Read error: ssl=0xaf97ce00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1566): SSL shutdown failed: ssl=0xaf97ce00: I/O error during system call, Broken pipe
D/ConnectivityService(  735): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): ValidatedState{ when=-4ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-4ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  735): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1035): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  735): do suspend true
,D/ConnectivityService(  735): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
D/Nat464Xlat(  735): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/CSLegacyTypeTracker(  735): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1598): CM callback handler got msg 524292
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  735): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  735): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/TelephonyNetworkFactory( 1165): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  735): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant( 1035): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1035): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1035): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1035): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  735): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  735): Start Dhcp Watchdog 2
,E/native  (  735): do suspend false
,E/WifiStateMachine(  735): scanCount==0 - aborting
,I/dhcpcd  ( 3258): version 5.5.6 starting
E/dhcpcd  ( 3258): get_duid: Read-only file system
,I/dhcpcd  ( 3258): wlan0: rebinding lease of 192.168.1.114
,D/CAR.SERVICE( 3094): mConnectedToCar = false, abort
,E/ActivityThread( 3094): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1997f46e that was originally bound here
E/ActivityThread( 3094): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1997f46e that was originally bound here
E/ActivityThread( 3094): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3094): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3094): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3094): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3094): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3094): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3094): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3094): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3094): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3094): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3094): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3094): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3094): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3094): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3094): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3094): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3094): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3094): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3094): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3094): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3094): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3094): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3094): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3094): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@37aad321 that was originally bound here
E/ActivityThread( 3094): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@37aad321 that was originally bound here
E/ActivityThread( 3094): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3094): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3094): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3094): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3094): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3094): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3094): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3094): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3094): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3094): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3094): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3094): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3094): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3094): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3094): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3094): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3094): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3094): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3094): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3094): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3094): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3094): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  735): Unbind failed: could not find connection for android.os.BinderProxy@37f91fb5
,I/dhcpcd  ( 3258): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/dhcpcd  ( 3258): wlan0: leased 192.168.1.114 for 86400 seconds
,D/Tethering(  735): MasterInitialState.processMessage what=3
D/Tethering(  735): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2720): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  735): No APN found to select.
,I/SystemUpdateService( 1598): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1598): onCreate
,D/SystemUpdateService( 1598): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1598): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1598): num queued entries: 0
,I/iu.UploadsManager( 1598): num updated entries: 0
,I/iu.SyncManager( 1598): NEXT; no task
,I/ActivityManager(  735): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3283 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  735): No APN found to select.
,I/SystemUpdateService( 1598): active receiver: enabled
,I/Babel   ( 1897): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1598): showing system update notification
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1598): retry (wakeup: false) in 3599919 ms
,D/SystemUpdateService( 1598): onDestroy
,E/native  (  735): do suspend true
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  735): Adding iface wlan0 to network 101
,E/WifiStateMachine(  735): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  735): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  735): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  735): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  735): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  735): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  735): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  735): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  735): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  735): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1598): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/Nat464Xlat(  735): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  735): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1598): CM callback handler got msg 524295
,I/GAv4    ( 3283): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3283):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3283):   adb logcat -s GAv4
,W/GAv4    ( 3283): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3283): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3283): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 14:21:09 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455027669874], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455027669854]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Validated
,D/ConnectivityService(  735): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1598): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1165): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WebViewFactory( 3283): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3283): Time to load native libraries: 1 ms (timestamps 2576-2577)
I/LibraryLoader( 3283): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3283): Binding Chromium to main looper Looper (main, tid 1) {16ccc52b}
,I/LibraryLoader( 3283): Expected native library version number "",actual native library version number ""
,I/chromium( 3283): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3283): Initializing chromium process, singleProcess=true
W/art     ( 3283): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3283): ApplicationContext is null in ApplicationStatus
,W/chromium( 3283): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3283): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3283): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3283): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3283): Requires BLUETOOTH permission
,I/NSApplication( 3283): Starting up...
,I/ActivityManager(  735): Killing 2698:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10003/pid_2698/cgroup.procs: No such file or directory
,V/MusicLeanback( 2720): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1598): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1598): onCreate
,D/SystemUpdateService( 1598): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1598): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1598): num queued entries: 0
I/iu.UploadsManager( 1598): num updated entries: 0
I/iu.SyncManager( 1598): NEXT; no task
,I/SystemUpdateService( 1598): active receiver: enabled
,I/SystemUpdateService( 1598): showing system update notification
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1598): retry (wakeup: false) in 3599987 ms
,D/SystemUpdateService( 1598): onDestroy
,I/Babel   ( 1897): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3163): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3163): 
,D/ConnectivityService(  735): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3163): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3163): 
,I/jxcore-log( 3163): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3163): 
,I/jxcore-log( 3163): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3163): 
,I/jxcore-log( 3163): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3163): 
,I/jxcore-log( 3163): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3163): 
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2720): type=WIFI subType= reason=null isConnected=true
V/MusicLeanback( 2720): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1598): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1598): onCreate
D/SystemUpdateService( 1598): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1598): active receiver: enabled
E/GpsLocationProvider(  735): No APN found to select.
,I/SystemUpdateService( 1598): showing system update notification
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1598): retry (wakeup: false) in 3599989 ms
,D/SystemUpdateService( 1598): onDestroy
,I/jxcore-log( 3163): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3163): 
,I/jxcore-log( 3163): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3163): 
,I/jxcore-log( 3163): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3163): 
,I/jxcore-log( 3163): Test app app.js loaded
I/jxcore-log( 3163): 
,I/chromium( 3163): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3163): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3163): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3163): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3163): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3163): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3163): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3163): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3163): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3163): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3163): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15d41958 added. We now have 1 listener(s)
,I/jxcore-log( 3163): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3163): 
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2620): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2620): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1566): Vacuum at: now=1455027694184 tag=VacuumService
,I/PhenotypeConfigurator( 1566): Scheduling Phenotype for one-off execution 4346 seconds from now (1455027694615)
,D/GetConfigurationSnapshotOperation( 1566): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1566): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1566): Using platform SSLCertificateSocketFactory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1046): run()
I/Keyboard.Facilitator( 1046): flushDynamicLanguageModels()
,I/ConfigService( 1566): onCreate
,I/ConfigService( 1566): onDestroy
,I/ClearcutLoggerApiImpl( 1566): disconnect managed GoogleApiClient
,I/jxcore-log( 3163): --= Surplus to requirements =--
I/jxcore-log( 3163): 
I/jxcore-log( 3163): ****TEST TOOK:  ms ****
I/jxcore-log( 3163): 
I/jxcore-log( 3163): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3163): 
,D/AndroidRuntime( 3500): 
D/AndroidRuntime( 3500): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3500): CheckJNI is OFF
,D/AndroidRuntime( 3500): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  735): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
,I/ActivityManager(  735): Killing 3163:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  735): WIN DEATH: Window{16d1db45 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  735): Client connection lost with reason: 4
,W/PackageSettings(  735): Skipping PackageSetting{3d5233e5 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  735):   Force finishing activity ActivityRecord{1e7f85e2 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  735): Spurious death for ProcessRecord{34a59cba 3163:com.test.thalitest/u0a270}, curProc for 3163: null
I/ActivityManager(  735): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  735):   Force finishing activity ActivityRecord{1e7f85e2 u0 com.test.thalitest/.MainActivity t216 f}
W/ActivityManager(  735): Duplicate finish request for ActivityRecord{1e7f85e2 u0 com.test.thalitest/.MainActivity t216 f}
,I/art     ( 1598): Explicit concurrent mark sweep GC freed 5447(266KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/30MB, paused 705us total 28.188ms
,I/art     ( 1316): Explicit concurrent mark sweep GC freed 6028(487KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 322us total 30.158ms
,I/InputReader(  735): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1566): Ignoring removeGeofence because network location is disabled.
,I/art     ( 1225): Explicit concurrent mark sweep GC freed 3970(294KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 580us total 26.397ms
,I/Keyboard.Facilitator( 1046): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1046): run()
I/Decoder ( 1046): createOrResetDecoder
,I/Adreno-EGL(  946): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  946): Initialized EGL, version 1.4
,I/ConfigService( 1566): onCreate
,D/OpenGLRenderer(  946): Enabling debug mode 0
I/UpdateIcingCorporaServi( 1316): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/VoicemailCleanupService( 2824): Cleaning up data for package: com.test.thalitest
,W/Launcher( 1225): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@9a98086 new=com.google.android.velvet.VelvetApplication@9a98086
,I/art     (  735): Explicit concurrent mark sweep GC freed 55235(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 1.211ms total 103.809ms
,I/art     (  735): WaitForGcToComplete blocked for 94.688ms for cause Explicit
,I/ActivityManager(  735): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3541 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,W/InputMethodManagerService(  735): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@2846b335 (uid=10034 pid=946)
,W/ContextImpl( 3541): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/BackupManagerService(  735): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  735): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1046): run()
D/PackageBroadcastService( 1598): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1598): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1598): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1598): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1598): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1598): Module APK com.google.android.play.games already loaded
D/TaskPersister(  735): removeObsoleteFile: deleting file=216_task.xml
,E/NetworkScheduler.SchedulerReceiver( 1566): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1566): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1598): Removing dialog suppression flag for package com.test.thalitest
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1046): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1046): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1046): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1046): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1046): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1046): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1046): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1046): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1046): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1046): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1046): run()
I/StatsUtilsManager( 1046): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1046): shouldRecordStats() = Too Soon
,I/art     (  735): Explicit concurrent mark sweep GC freed 10209(544KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.715ms total 168.460ms
W/InputMethodManagerService(  735): Got RemoteException sending setActive(false) notification to pid 3163 uid 10270
,I/Keyboard.Facilitator( 1046): onFinishInput()
,D/gH_CompatibleDatabase( 1598): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1598): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1598): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1598): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/ActivityManager(  735): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3576 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,D/gH_CompatibleDatabase( 1598): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1598): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1598): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1598): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1598): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1598): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1598): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1598): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1598): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/Launcher( 1225): Deferring update until onResume
,I/UpdateIcingCorporaServi( 1316): UpdateCorporaTask done [took 266 ms] updated apps [took 266 ms] 
,D/AndroidRuntime( 3500): Shutting down VM
,W/BaseAppContext( 1598): Using Auth Proxy for data requests.
,W/BaseAppContext( 1598): Using Auth Proxy for data requests.
I/ActivityManager(  735): Killing 2679:com.android.settings/1000 (adj 15): empty #17
,W/ResourcesManager( 1225): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/WifiService(  735): Client connection lost with reason: 4
,W/ResourcesManager( 1225): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1225): Deferring update until onResume
,W/libprocessgroup(  735): failed to open /acct/uid_1000/pid_2679/cgroup.procs: No such file or directory
,I/GMPM-SVC( 1598): App measurement is starting up, version: 8489
I/GMPM-SVC( 1598): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/Icing   ( 1598): doRemovePackageData com.test.thalitest
,I/ActivityManager(  735): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3600 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  735): Killing 2558:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10070/pid_2558/cgroup.procs: No such file or directory
,I/ActivityManager(  735): Killing 2004:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10031/pid_2004/cgroup.procs: No such file or directory
,D/ExternalStorage( 3600): After updating volumes, found 1 active roots
,W/ResourcesManager( 3039): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3039): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3576): Update found 7 roots in 298ms
,D/Documents( 3576): Update found 7 roots in 183ms

```
