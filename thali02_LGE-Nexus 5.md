#### Test 58135655a1ee273_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/DeviceConnectionService( 1573): client connected with version: 8296000
D/Finsky  ( 2594): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2594): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
--------- beginning of system
I/ActivityManager(  733): Killing 2059:com.google.android.deskclock/u0a38 (adj 15): empty #17
D/ChimeraCfgMgr( 1615): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1615): Module APK com.google.android.play.games already loaded
I/ActivityManager(  733): Killing 2407:com.google.android.youtube/u0a80 (adj 15): empty #18
W/libprocessgroup(  733): failed to open /acct/uid_10038/pid_2059/cgroup.procs: No such file or directory
W/libprocessgroup(  733): failed to open /acct/uid_10080/pid_2407/cgroup.procs: No such file or directory
I/GAv4    ( 3075): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3075):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3075):   adb logcat -s GAv4
W/GAv4    ( 3075): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3075): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3075): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3075): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2594): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
W/ResourcesManager( 3075): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3075): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 2594): [266] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/JNIHelp ( 3075): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3075): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3075): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1615): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1615): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1615): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1615): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/ActivityManager(  733): Killing 2561:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/libprocessgroup(  733): failed to open /acct/uid_10069/pid_2561/cgroup.procs: No such file or directory
,D/AndroidRuntime( 3163): 
D/AndroidRuntime( 3163): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3163): CheckJNI is OFF
D/AndroidRuntime( 3163): Calling main entry com.android.commands.am.Am
I/ActivityManager(  733): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  733): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3184 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3163): Shutting down VM
V/ActivityManager(  733): Display changed displayId=0
I/WebViewFactory( 3184): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3184): Time to load native libraries: 2 ms (timestamps 9049-9051)
I/LibraryLoader( 3184): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3184): Binding Chromium to main looper Looper (main, tid 1) {221879d6}
I/LibraryLoader( 3184): Expected native library version number "",actual native library version number ""
I/chromium( 3184): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3184): Initializing chromium process, singleProcess=true
W/art     ( 3184): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3184): ApplicationContext is null in ApplicationStatus
W/chromium( 3184): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3184): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3184): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3184): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  733): Message: 20
D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@306b42ad:true
,W/art     ( 3184): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3184): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3184): CordovaWebView is running on device made by: LGE
,W/art     ( 3184): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3184): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3184): Render dirty regions requested: true
,D/Atlas   ( 3184): Validating map...
,W/chromium( 3184): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3184): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3184): Enabling debug mode 0
,W/IInputConnectionWrapper( 3184): showStatusIcon on inactive InputConnection
,I/ActivityManager(  733): Displayed com.test.thalitest/.MainActivity: +417ms (total +49s122ms)
,W/BindingManager( 3184): Cannot call determinedVisibility() - never saw a connection for the pid: 3184
,D/JsMessageQueue( 3184): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3184): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,I/chromium( 3184): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  733): Killing 2514:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10045/pid_2514/cgroup.procs: No such file or directory
,W/jxcore-log( 3184): Initializing JXcore engine
W/jxcore-log( 3184): JXcore engine is ready
,W/Thread-306( 3232): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7942]" dev="sockfs" ino=7942 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-306( 3232): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-306( 3232): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9440]" dev="sockfs" ino=9440 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-306( 3232): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18295]" dev="sockfs" ino=18295 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3184): Starting JXcore engine
,W/jxcore-log( 3184): Platform android
W/jxcore-log( 3184): 
W/jxcore-log( 3184): Process ARCH arm
W/jxcore-log( 3184): 
,I/jxcore-log( 3184): JXcore Cordova bridge is ready!
I/jxcore-log( 3184): 
,W/jxcore-log( 3184): JXcore engine is started
,I/jxcore-log( 3184): Toggling radios to true
I/jxcore-log( 3184): 
,D/BluetoothAdapter( 3184): enable(): BT is already enabled..!
,D/WifiService(  733): New client listening to asynchronous messages
,D/WifiService(  733): setWifiEnabled: true pid=3184, uid=10270
E/WifiService(  733): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3184): Radios toggled
I/jxcore-log( 3184): 
I/jxcore-log( 3184): My device name is: LGE-Nexus 5
I/jxcore-log( 3184): 
,I/wpa_supplicant( 1025): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  733): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  733): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1573): Read error: ssl=0xb3c84e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1573): SSL shutdown failed: ssl=0xb3c84e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  733): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  733): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1025): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  733): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
D/ConnectivityService(  733): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  733): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  733): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1615): CM callback handler got msg 524292
D/ConnectivityService(  733): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1239): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  888): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Disconnected - quitting
,D/WifiNetworkAgent(  733): NetworkAgent: NetworkAgent channel lost
,D/CAR.SERVICE( 2987): mConnectedToCar = false, abort
,E/ActivityThread( 2987): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@26b34c1f that was originally bound here
E/ActivityThread( 2987): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@26b34c1f that was originally bound here
E/ActivityThread( 2987): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2987): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2987): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2987): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2987): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2987): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2987): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2987): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2987): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2987): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 2987): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 2987): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 2987): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 2987): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 2987): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 2987): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 2987): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2987): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2987): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2987): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2987): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2987): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2987): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/ActivityThread( 2987): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2946ec96 that was originally bound here
E/ActivityThread( 2987): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2946ec96 that was originally bound here
E/ActivityThread( 2987): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2987): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2987): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2987): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2987): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2987): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2987): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2987): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 2987): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 2987): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 2987): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 2987): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 2987): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 2987): 	at android.app.ActivityThread.access,$1900(ActivityThread.java:144)
E/ActivityThread( 2987): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 2987): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2987): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2987): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2987): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2987): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2987): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2987): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  733): Unbind failed: could not find connection for android.os.BinderProxy@256466d5
,W/NetworkUtils( 1346): OkHttp exception
,W/EventLoggerService( 1346): Unable to send logs Error code: 262146
,I/wpa_supplicant( 1025): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1025): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1025): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1025): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  733): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
E/WifiStateMachine(  733): Start Dhcp Watchdog 2
,E/native  (  733): do suspend false
,E/WifiStateMachine(  733): scanCount==0 - aborting
,I/dhcpcd  ( 3270): version 5.5.6 starting
E/dhcpcd  ( 3270): get_duid: Read-only file system
,I/dhcpcd  ( 3270): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3270): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3270): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  733): MasterInitialState.processMessage what=3
,D/Tethering(  733): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2698): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1615): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1615): onCreate
,D/SystemUpdateService( 1615): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1615): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1615): num queued entries: 0
I/iu.UploadsManager( 1615): num updated entries: 0
I/iu.SyncManager( 1615): NEXT; no task
,I/SystemUpdateService( 1615): active receiver: enabled
,I/SystemUpdateService( 1615): showing system update notification
,E/GpsLocationProvider(  733): No APN found to select.
,I/ValidateNoPeople(  733): skipping global notification
,V/SystemUpdateService( 1615): retry (wakeup: false) in 3599969 ms
,I/Babel   ( 1885): connection state changed from CONNECTED to DISCONNECTED
,E/native  (  733): do suspend true
,I/ActivityManager(  733): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3314 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  733): No APN found to select.
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  733): Adding iface wlan0 to network 101
,E/WifiStateMachine(  733): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/SystemUpdateService( 1615): onDestroy
,E/ConnectivityService(  733): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  733): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  733): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  733): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  733): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  733): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  733): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/CSLegacyTypeTracker(  733): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  733): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  733): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  888): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1615): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Feb 2016 14:46:41 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454597201878], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454597201856]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Validated
D/ConnectivityService(  733): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  733): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  888): CM callback handler got msg 524290
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1239): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1615): CM callback handler got msg 524290
,I/GAv4    ( 3314): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3314):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3314):   adb logcat -s GAv4
,W/GAv4    ( 3314): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3314): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3314): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3314): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3314): Time to load native libraries: 1 ms (timestamps 4691-4692)
I/LibraryLoader( 3314): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3314): Binding Chromium to main looper Looper (main, tid 1) {84b7258}
,I/LibraryLoader( 3314): Expected native library version number "",actual native library version number ""
,I/chromium( 3314): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3314): Initializing chromium process, singleProcess=true
,W/art     ( 3314): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3314): ApplicationContext is null in ApplicationStatus
,W/chromium( 3314): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3314): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3314): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3314): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3314): Requires BLUETOOTH permission
,I/NSApplication( 3314): Starting up...
,I/art     (  733): Explicit concurrent mark sweep GC freed 44266(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 989us total 75.129ms
,I/ActivityManager(  733): Killing 2670:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10003/pid_2670/cgroup.procs: No such file or directory
,I/jxcore-log( 3184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3184): 
,V/MusicLeanback( 2698): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1615): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1615): onCreate
,D/SystemUpdateService( 1615): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1615): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1615): active receiver: enabled
,I/iu.UploadsManager( 1615): num queued entries: 0
,I/iu.UploadsManager( 1615): num updated entries: 0
,I/iu.SyncManager( 1615): NEXT; no task
,I/SystemUpdateService( 1615): showing system update notification
,I/ValidateNoPeople(  733): skipping global notification
,V/SystemUpdateService( 1615): retry (wakeup: false) in 3599974 ms
,D/SystemUpdateService( 1615): onDestroy
,D/ConnectivityService(  733): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/Babel   ( 1885): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3184): 
,I/jxcore-log( 3184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3184): 
,I/jxcore-log( 3184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3184): 
,I/jxcore-log( 3184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3184): 
,I/jxcore-log( 3184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3184): 
,I/jxcore-log( 3184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3184): 
I/jxcore-log( 3184): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3184): 
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  733): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2698): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  733): No APN found to select.
,V/MusicLeanback( 2698): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/SystemUpdateService( 1615): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1615): onCreate
D/SystemUpdateService( 1615): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/SystemUpdateService( 1615): active receiver: enabled
I/SystemUpdateService( 1615): showing system update notification
,V/SystemUpdateService( 1615): retry (wakeup: false) in 3599977 ms
I/ValidateNoPeople(  733): skipping global notification
,D/SystemUpdateService( 1615): onDestroy
,I/jxcore-log( 3184): Test app app.js loaded
I/jxcore-log( 3184): 
,I/chromium( 3184): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3184): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3184): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3184): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3184): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3184): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3184): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3184): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3184): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3184): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3184): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b87a57 added. We now have 1 listener(s)
,I/jxcore-log( 3184): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3184): 
,D/Finsky  ( 2594): [256] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2594): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1573): Vacuum at: now=1454597224086 tag=VacuumService
,I/PhenotypeConfigurator( 1573): Scheduling Phenotype for one-off execution 6282 seconds from now (1454597224444)
,D/GetConfigurationSnapshotOperation( 1573): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1573): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1573): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ClearcutLoggerApiImpl( 1573): disconnect managed GoogleApiClient
,I/jxcore-log( 3184): --= Surplus to requirements =--
I/jxcore-log( 3184): 
I/jxcore-log( 3184): ****TEST TOOK:  ms ****
I/jxcore-log( 3184): 
I/jxcore-log( 3184): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3184): 
,D/AndroidRuntime( 3517): 
D/AndroidRuntime( 3517): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3517): CheckJNI is OFF
,D/AndroidRuntime( 3517): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  733): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  733): Killing 3184:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  733): WIN DEATH: Window{347c2d60 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  733): Client connection lost with reason: 4
,W/PackageSettings(  733): Skipping PackageSetting{3caa130a com.example.hello/10278} due to missing metadata
I/ActivityManager(  733):   Force finishing activity ActivityRecord{b963b2c u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  733): Spurious death for ProcessRecord{3066c103 3184:com.test.thalitest/u0a270}, curProc for 3184: null
,I/ActivityManager(  733): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  733):   Force finishing activity ActivityRecord{b963b2c u0 com.test.thalitest/.MainActivity t216 f}
W/ActivityManager(  733): Duplicate finish request for ActivityRecord{b963b2c u0 com.test.thalitest/.MainActivity t216 f}
,I/InputReader(  733): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1573): Ignoring removeGeofence because network location is disabled.
,I/art     (  733): Explicit concurrent mark sweep GC freed 27020(1420KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 1.431ms total 57.507ms
,I/art     ( 1300): Explicit concurrent mark sweep GC freed 3945(293KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 222us total 44.486ms
,I/Keyboard.Facilitator( 1081): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1081): run()
,I/Adreno-EGL(  934): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  934): Initialized EGL, version 1.4
,D/OpenGLRenderer(  934): Enabling debug mode 0
,D/VoicemailCleanupService( 2798): Cleaning up data for package: com.test.thalitest
,I/Decoder ( 1081): createOrResetDecoder
,I/ConfigService( 1573): onCreate
,I/art     ( 1346): Explicit concurrent mark sweep GC freed 375(27KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 1.306ms total 143.496ms
,I/art     ( 1615): Explicit concurrent mark sweep GC freed 7420(359KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 457us total 149.112ms
,I/UpdateIcingCorporaServi( 1346): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1300): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@b0f4457 new=com.google.android.velvet.VelvetApplication@b0f4457
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1081): run()
,D/BackupManagerService(  733): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  733): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  733): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3560 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/TaskPersister(  733): removeObsoleteFile: deleting file=216_task.xml
,I/art     (  733): Explicit concurrent mark sweep GC freed 7055(410KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 4.063ms total 126.638ms
,W/InputMethodManagerService(  733): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@101aa56c (uid=10034 pid=934)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1081): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1081): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1081): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1081): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1081): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1081): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1081): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1081): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1081): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1081): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1081): run()
I/StatsUtilsManager( 1081): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1081): shouldRecordStats() = Too Soon
,I/UpdateIcingCorporaServi( 1346): UpdateCorporaTask done [took 104 ms] updated apps [took 104 ms] 
,W/ContextImpl( 3560): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1615): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1615): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1615): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1615): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1615): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1615): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  733): Killing 2645:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  733): Client connection lost with reason: 4
,D/AndroidRuntime( 3517): Shutting down VM
,W/libprocessgroup(  733): failed to open /acct/uid_1000/pid_2645/cgroup.procs: No such file or directory
,I/Launcher( 1300): Deferring update until onResume
,E/NetworkScheduler.SchedulerReceiver( 1573): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1573): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1615): Removing dialog suppression flag for package com.test.thalitest
,W/ResourcesManager( 1300): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1615): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1615): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1615): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1615): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1615): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
W/ResourcesManager( 1300): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1615): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1615): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1615): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1615): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1615): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1615): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1615): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
I/Launcher( 1300): Deferring update until onResume
D/gH_CompatibleDatabase( 1615): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  733): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3592 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,W/BaseAppContext( 1615): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1615): App measurement is starting up, version: 8489
I/GMPM-SVC( 1615): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1615): Using Auth Proxy for data requests.
,E/SQLiteDatabase( 1615): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1615): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1615): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1615): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1615): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1615): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1615): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1615): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1615): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1615): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1615): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1615): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1615): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1615): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1615): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1615): 	at com.google.android.gms.common.k.a.delete(SourceFile:272)
E/SQLiteDatabase( 1615): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/SQLiteDatabase( 1615): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1615): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1615): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1615): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/SQLiteDatabase( 1615): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1615): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1615): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteDatabase( 1615): 	at java.lang.Thread.run(Thread.java:818)
E/ClearPendingStateOp( 1615): Runtime exception while performing operation
E/ClearPendingStateOp( 1615): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1615): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/ClearPendingStateOp( 1615): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1615): 	at com.google.android.gms.common.k.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1615): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/ClearPendingStateOp( 1615): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1615): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1615): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1615): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 1615): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1615): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1615): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1615): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1615): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1615): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1615): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
F/ClearPendingStateOp( 1615): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
F/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1615): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1615): 	at com.google.android.gms.common.k.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1615): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
F/ClearPendingStateOp( 1615): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1615): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1615): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1615): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 1615): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1615): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1615): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1615): 	at java.lang.Thread.run(Thread.java:818)
,I/Icing   ( 1615): doRemovePackageData com.test.thalitest
,E/SQLiteLog( 1615): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DropBoxManagerService(  733): Can't write: system_app_wtf
E/DropBoxManagerService(  733): java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  733): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  733): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  733): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  733): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  733): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  733): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  733): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  733): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  733): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  733): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  733): 	... 5 more
,W/FileUtils( 1615): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/Icing   ( 1615): Failed to open Apps corpus file.
,E/Icing   ( 1615): Failed to open Apps corpus file.
E/SharedPreferencesImpl( 1615): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak

```
