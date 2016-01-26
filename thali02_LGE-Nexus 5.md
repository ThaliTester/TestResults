#### Test 564496605d11e75_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1622): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1622): Module APK com.google.android.play.games already loaded
V/GLSActivity( 1599): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GAv4    ( 3164): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3164):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3164):   adb logcat -s GAv4
W/GAv4    ( 3164): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3164): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3164): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3164): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
--------- beginning of system
I/ActivityManager(  756): Killing 2346:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
W/ResourcesManager( 3164): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3164): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/qtaguid ( 2622): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2622): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2622): untagSocket(37) failed with errno -22
W/libprocessgroup(  756): failed to open /acct/uid_1000/pid_2346/cgroup.procs: No such file or directory
D/Finsky  ( 2622): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
V/JNIHelp ( 3164): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/WearableService( 1599): callingUid 10008, callindPid: 1599
E/MDM     ( 1599): [175] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1599): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 1622): Restart initialization of location
V/GLSActivity( 1599): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/System  ( 3164): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3164): Installed default security provider GmsCore_OpenSSL
W/GCoreFlp( 1599): No location to return for getLastLocation()
W/FusedLocationProvider( 1599): location=null
V/GLSActivity( 1599): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2622): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2622): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 2622): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/Finsky  ( 2622): [1] DailyHygiene.access$600: Logging device features
I/Icing   ( 1622): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/DeviceConnectionService( 1599): client connected with version: 8296000
D/Finsky  ( 2622): [266] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 2622): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2622): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
V/GLSActivity( 1599): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1622): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1622): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1622): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/ActivityManager(  756): Killing 2078:com.google.android.deskclock/u0a38 (adj 15): empty #17
I/ActivityManager(  756): Killing 2436:com.google.android.youtube/u0a80 (adj 15): empty #18
W/libprocessgroup(  756): failed to open /acct/uid_10038/pid_2078/cgroup.procs: No such file or directory
,W/libprocessgroup(  756): failed to open /acct/uid_10080/pid_2436/cgroup.procs: No such file or directory
D/AndroidRuntime( 3230): 
D/AndroidRuntime( 3230): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3230): CheckJNI is OFF
D/AndroidRuntime( 3230): Calling main entry com.android.commands.am.Am
I/ActivityManager(  756): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  756): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3244 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3230): Shutting down VM
V/ActivityManager(  756): Display changed displayId=0
I/WebViewFactory( 3244): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3244): Time to load native libraries: 1 ms (timestamps 9685-9686)
I/LibraryLoader( 3244): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3244): Binding Chromium to main looper Looper (main, tid 1) {1f3cdab4}
I/LibraryLoader( 3244): Expected native library version number "",actual native library version number ""
I/chromium( 3244): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3244): Initializing chromium process, singleProcess=true
W/art     ( 3244): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3244): ApplicationContext is null in ApplicationStatus
W/chromium( 3244): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3244): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3244): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3244): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/ActivityManager(  756): Killing 2586:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,D/BluetoothManagerService(  756): Message: 20
D/BluetoothManagerService(  756): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@104378ad:true
,W/libprocessgroup(  756): failed to open /acct/uid_10069/pid_2586/cgroup.procs: No such file or directory
,W/art     ( 3244): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3244): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3244): CordovaWebView is running on device made by: LGE
,W/art     ( 3244): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3244): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3244): Render dirty regions requested: true
,D/Atlas   ( 3244): Validating map...
,W/chromium( 3244): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3244): Initialized EGL, version 1.4
D/OpenGLRenderer( 3244): Enabling debug mode 0
,I/Keyboard.Facilitator( 1097): onFinishInput()
,W/IInputConnectionWrapper( 3244): showStatusIcon on inactive InputConnection
,I/ActivityManager(  756): Displayed com.test.thalitest/.MainActivity: +412ms (total +53s659ms)
,W/BindingManager( 3244): Cannot call determinedVisibility() - never saw a connection for the pid: 3244
,D/JsMessageQueue( 3244): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3244): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,I/chromium( 3244): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3244): Initializing JXcore engine
W/jxcore-log( 3244): JXcore engine is ready
,W/Thread-303( 3307): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9367]" dev="sockfs" ino=9367 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-303( 3307): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-303( 3307): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10245]" dev="sockfs" ino=10245 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-303( 3307): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20634]" dev="sockfs" ino=20634 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3244): Starting JXcore engine
,W/jxcore-log( 3244): Platform android
W/jxcore-log( 3244): 
W/jxcore-log( 3244): Process ARCH arm
W/jxcore-log( 3244): 
,I/jxcore-log( 3244): JXcore Cordova bridge is ready!
I/jxcore-log( 3244): 
,W/jxcore-log( 3244): JXcore engine is started
,I/jxcore-log( 3244): Toggling radios to true
I/jxcore-log( 3244): 
,D/BluetoothAdapter( 3244): enable(): BT is already enabled..!
,D/WifiService(  756): New client listening to asynchronous messages
,D/WifiService(  756): setWifiEnabled: true pid=3244, uid=10270
E/WifiService(  756): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3244): Radios toggled
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): My device name is: LGE-Nexus 5
I/jxcore-log( 3244): 
,I/wpa_supplicant(  989): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  756): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  756): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1599): Read error: ssl=0xa4233e00: I/O error during system call, Connection timed out
V/NativeCrypto( 1599): SSL shutdown failed: ssl=0xa4233e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  756): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Forcing reevaluation
E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  756): Start Disconnecting Watchdog 1
,E/native  (  756): do suspend true
I/wpa_supplicant(  989): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): EvaluatingState{ when=-5ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/CommandListener(  181): Clearing all IP addresses on wlan0
D/ConnectivityService(  756): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  756): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  756): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1622): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  756): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1224): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): EvaluatingState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Disconnected - quitting
,D/WifiNetworkAgent(  756): NetworkAgent: NetworkAgent channel lost
,D/CAR.SERVICE( 3112): mConnectedToCar = false, abort
,E/ActivityThread( 3112): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1586f1e5 that was originally bound here
E/ActivityThread( 3112): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1586f1e5 that was originally bound here
E/ActivityThread( 3112): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3112): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3112): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3112): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3112): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3112): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3112): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3112): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3112): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3112): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3112): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3112): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3112): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3112): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3112): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3112): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3112): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3112): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3112): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3112): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3112): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3112): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3112): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3112): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@26265b74 that was originally bound here
E/ActivityThread( 3112): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@26265b74 that was originally bound here
E/ActivityThread( 3112): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3112): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3112): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3112): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3112): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3112): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3112): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3112): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3112): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3112): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3112): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3112): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3112): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3112): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3112): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3112): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3112): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3112): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3112): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3112): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3112): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3112): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  756): Unbind failed: could not find connection for android.os.BinderProxy@250e1db6
,I/wpa_supplicant(  989): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  989): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  989): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  989): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  756): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  181): Setting iface cfg
E/WifiStateMachine(  756): Start Dhcp Watchdog 2
,E/native  (  756): do suspend false
,E/WifiStateMachine(  756): scanCount==0 - aborting
,I/dhcpcd  ( 3354): version 5.5.6 starting
,E/dhcpcd  ( 3354): get_duid: Read-only file system
,I/dhcpcd  ( 3354): wlan0: rebinding lease of 192.168.1.114
,D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/Tethering(  756): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2752): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1622): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1622): onCreate
,D/SystemUpdateService( 1622): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1622): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1622): active receiver: enabled
I/iu.UploadsManager( 1622): num queued entries: 0
I/iu.UploadsManager( 1622): num updated entries: 0
I/iu.SyncManager( 1622): NEXT; no task
I/SystemUpdateService( 1622): showing system update notification
I/Babel   ( 1935): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  756): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3376 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  756): Explicit concurrent mark sweep GC freed 38531(1891KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 1.214ms total 83.276ms
,E/GpsLocationProvider(  756): No APN found to select.
,E/GpsLocationProvider(  756): No APN found to select.
,I/ValidateNoPeople(  756): skipping global notification
,V/SystemUpdateService( 1622): retry (wakeup: false) in 3599930 ms
,D/SystemUpdateService( 1622): onDestroy
,I/dhcpcd  ( 3354): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3354): wlan0: leased 192.168.1.114 for 86400 seconds
,I/GAv4    ( 3376): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3376):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3376):   adb logcat -s GAv4
,W/GAv4    ( 3376): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3376): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3376): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/native  (  756): do suspend true
,E/WifiStateMachine(  756): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  756): Adding iface wlan0 to network 101
,E/ConnectivityService(  756): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  756): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  756): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  756): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  756): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  756): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  756): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/CSLegacyTypeTracker(  756): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  756): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  756): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1622): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,I/WebViewFactory( 3376): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3376): Time to load native libraries: 2 ms (timestamps 5868-5870)
I/LibraryLoader( 3376): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3376): Binding Chromium to main looper Looper (main, tid 1) {15e25ac8}
,I/LibraryLoader( 3376): Expected native library version number "",actual native library version number ""
I/chromium( 3376): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3376): Initializing chromium process, singleProcess=true
W/art     ( 3376): Attempt to remove local handle scope entry from IRT, ignoring
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 26 Jan 2016 11:26:06 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453807566373], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453807566353]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Don't send network conditions - lacking user consent.
E/SysUtils( 3376): ApplicationContext is null in ApplicationStatus
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Validated
D/ConnectivityService(  756): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  756): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1224): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1622): CM callback handler got msg 524290
,W/chromium( 3376): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3376): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3376): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3376): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3376): Requires BLUETOOTH permission
,I/NSApplication( 3376): Starting up...
,I/ActivityManager(  756): Killing 2539:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/jxcore-log( 3244): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3244): 
,W/libprocessgroup(  756): failed to open /acct/uid_10045/pid_2539/cgroup.procs: No such file or directory
,V/MusicLeanback( 2752): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1622): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1622): onCreate
,D/SystemUpdateService( 1622): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/iu.Environment( 1622): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1622): num queued entries: 0
I/iu.UploadsManager( 1622): num updated entries: 0
I/iu.SyncManager( 1622): NEXT; no task
I/SystemUpdateService( 1622): active receiver: enabled
,I/SystemUpdateService( 1622): showing system update notification
,I/ValidateNoPeople(  756): skipping global notification
,V/SystemUpdateService( 1622): retry (wakeup: false) in 3599989 ms
,D/SystemUpdateService( 1622): onDestroy
,I/Babel   ( 1935): connection state changed from DISCONNECTED to CONNECTED
,I/GCM     ( 1622): Message from null null
E/GCM     ( 1622): Dropping message from null
,D/ConnectivityService(  756): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3244): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3244): 
,D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  756): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2752): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2752): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1622): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1622): onCreate
,D/SystemUpdateService( 1622): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/GpsLocationProvider(  756): No APN found to select.
,I/SystemUpdateService( 1622): active receiver: enabled
,I/SystemUpdateService( 1622): showing system update notification
,I/ValidateNoPeople(  756): skipping global notification
,V/SystemUpdateService( 1622): retry (wakeup: false) in 3599957 ms
,D/SystemUpdateService( 1622): onDestroy
,I/jxcore-log( 3244): Test app app.js loaded
I/jxcore-log( 3244): 
,I/chromium( 3244): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3244): BLE advertisement is supported
I/jxcore-log( 3244): 
,D/Finsky  ( 2622): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2622): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1599): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1599): Vacuum at: now=1453807588632 tag=VacuumService
,I/PhenotypeConfigurator( 1599): Scheduling Phenotype for one-off execution 7445 seconds from now (1453807589156)
,D/GetConfigurationSnapshotOperation( 1599): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1599): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1599): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1599): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1599): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1097): run()
I/Keyboard.Facilitator( 1097): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1599): disconnect managed GoogleApiClient
,I/jxcore-log( 3244): --= Surplus to requirements =--
I/jxcore-log( 3244): 
I/jxcore-log( 3244): ****TEST TOOK:  ms ****
I/jxcore-log( 3244): 
I/jxcore-log( 3244): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3244): 
,D/AndroidRuntime( 3590): 
D/AndroidRuntime( 3590): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3590): CheckJNI is OFF
,D/AndroidRuntime( 3590): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  756): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
,I/ActivityManager(  756): Killing 3244:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  756): WIN DEATH: Window{28014d8c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  756): Client connection lost with reason: 4
,I/ActivityManager(  756):   Force finishing activity ActivityRecord{aa84c18 u0 com.test.thalitest/.MainActivity t216}
,W/PackageSettings(  756): Skipping PackageSetting{2371e208 com.example.hello/10278} due to missing metadata
,W/ActivityManager(  756): Spurious death for ProcessRecord{140324b9 3244:com.test.thalitest/u0a270}, curProc for 3244: null
,I/ActivityManager(  756): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1622): Explicit concurrent mark sweep GC freed 7228(351KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 444us total 28.169ms
,I/art     ( 1354): Explicit concurrent mark sweep GC freed 481(31KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 347us total 20.462ms
,I/art     ( 1256): Explicit concurrent mark sweep GC freed 3990(295KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 651us total 17.154ms
,I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1097): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1599): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator.DecoderInitializer( 1097): run()
D/VoicemailCleanupService( 1332): Cleaning up data for package: com.test.thalitest
,I/Decoder ( 1097): createOrResetDecoder
,I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  944): Initialized EGL, version 1.4
,D/OpenGLRenderer(  944): Enabling debug mode 0
,I/art     (  756): Explicit concurrent mark sweep GC freed 36901(1925KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 2.797ms total 89.211ms
,I/UpdateIcingCorporaServi( 1354): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1256): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@32c426dd new=com.google.android.velvet.VelvetApplication@32c426dd
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1097): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1097): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
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
,I/ActivityManager(  756): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3631 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,W/InputMethodManagerService(  756): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@118b6727 (uid=10034 pid=944)
,D/BackupManagerService(  756): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  756): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  756): removeObsoleteFile: deleting file=216_task.xml
,W/InputMethodManagerService(  756): Got RemoteException sending setActive(false) notification to pid 3244 uid 10270
I/art     (  756): Explicit concurrent mark sweep GC freed 6004(343KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 6.784ms total 124.539ms
W/ContextImpl( 3631): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/Keyboard.Facilitator( 1097): onFinishInput()
,D/PackageBroadcastService( 1622): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1622): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1622): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1622): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1622): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1622): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  756): Killing 2730:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10003/pid_2730/cgroup.procs: No such file or directory
,I/LocationSettingsChecker( 1622): Removing dialog suppression flag for package com.test.thalitest
,I/Launcher( 1256): Deferring update until onResume
,E/NetworkScheduler.SchedulerReceiver( 1599): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1599): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/AndroidRuntime( 3590): Shutting down VM
,W/ResourcesManager( 1256): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1622): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1622): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1622): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1622): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/ResourcesManager( 1256): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1622): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1622): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1622): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/UpdateIcingCorporaServi( 1354): UpdateCorporaTask done [took 265 ms] updated apps [took 265 ms] 
,D/gH_CompatibleDatabase( 1622): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1622): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1622): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1622): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1622): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1622): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/Launcher( 1256): Deferring update until onResume
,I/ActivityManager(  756): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3664 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,W/BaseAppContext( 1622): Using Auth Proxy for data requests.
,W/BaseAppContext( 1622): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1622): App measurement is starting up, version: 8489
,I/GMPM-SVC( 1622): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/Icing   ( 1622): doRemovePackageData com.test.thalitest
,I/ActivityManager(  756): Killing 2691:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  756): Client connection lost with reason: 4
,I/ActivityManager(  756): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3689 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,W/libprocessgroup(  756): failed to open /acct/uid_1000/pid_2691/cgroup.procs: No such file or directory
,I/ActivityManager(  756): Killing 2560:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10070/pid_2560/cgroup.procs: No such file or directory
,D/ExternalStorage( 3689): After updating volumes, found 1 active roots
,W/ResourcesManager( 3164): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3164): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.

```
