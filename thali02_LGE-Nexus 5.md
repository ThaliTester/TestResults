#### Test 58135655a685cd3_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1626): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1626): Module APK com.google.android.play.games already loaded
V/GLSActivity( 1575): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GAv4    ( 3063): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3063):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3063):   adb logcat -s GAv4
W/GAv4    ( 3063): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3063): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3063): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3063): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
--------- beginning of system
I/ActivityManager(  734): Killing 2405:com.google.android.youtube/u0a80 (adj 15): empty #17
W/ResourcesManager( 3063): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3063): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/qtaguid ( 2583): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2583): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2583): untagSocket(37) failed with errno -22
W/libprocessgroup(  734): failed to open /acct/uid_10080/pid_2405/cgroup.procs: No such file or directory
V/JNIHelp ( 3063): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3063): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3063): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1575): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2583): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2583): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 2583): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/Finsky  ( 2583): [1] DailyHygiene.access$600: Logging device features
I/Icing   ( 1626): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Finsky  ( 2583): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/DeviceConnectionService( 1575): client connected with version: 8296000
D/WearableService( 1575): callingUid 10008, callindPid: 1575
D/Finsky  ( 2583): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2583): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  734): Killing 2056:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/libprocessgroup(  734): failed to open /acct/uid_10038/pid_2056/cgroup.procs: No such file or directory
I/ActivityManager(  734): Killing 2556:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
E/MDM     ( 1575): [223] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/libprocessgroup(  734): failed to open /acct/uid_10069/pid_2556/cgroup.procs: No such file or directory
D/LocationInitializer( 1626): Restart initialization of location
D/AuthorizationBluetoothService( 1575): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/Icing   ( 1626): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1626): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
V/GLSActivity( 1575): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1575): No location to return for getLastLocation()
W/FusedLocationProvider( 1575): location=null
D/Finsky  ( 2583): [265] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1575): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1626): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3139): 
D/AndroidRuntime( 3139): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3139): CheckJNI is OFF
D/AndroidRuntime( 3139): Calling main entry com.android.commands.am.Am
I/ActivityManager(  734): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  734): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3160 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3139): Shutting down VM
V/ActivityManager(  734): Display changed displayId=0
I/WebViewFactory( 3160): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3160): Time to load native libraries: 2 ms (timestamps 8652-8654)
I/LibraryLoader( 3160): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3160): Binding Chromium to main looper Looper (main, tid 1) {26cd3c3d}
I/LibraryLoader( 3160): Expected native library version number "",actual native library version number ""
I/chromium( 3160): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3160): Initializing chromium process, singleProcess=true
W/art     ( 3160): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3160): ApplicationContext is null in ApplicationStatus
W/chromium( 3160): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3160): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3160): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3160): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b7b4214:true
,W/art     ( 3160): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3160): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3160): CordovaWebView is running on device made by: LGE
,W/art     ( 3160): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3160): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3160): Render dirty regions requested: true
,D/Atlas   ( 3160): Validating map...
,W/chromium( 3160): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3160): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3160): Enabling debug mode 0
,W/BindingManager( 3160): Cannot call determinedVisibility() - never saw a connection for the pid: 3160
,W/IInputConnectionWrapper( 3160): showStatusIcon on inactive InputConnection
,I/ActivityManager(  734): Displayed com.test.thalitest/.MainActivity: +433ms (total +48s16ms)
,D/JsMessageQueue( 3160): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3160): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342720
,I/chromium( 3160): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  734): Killing 2509:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10045/pid_2509/cgroup.procs: No such file or directory
,W/jxcore-log( 3160): Initializing JXcore engine
W/jxcore-log( 3160): JXcore engine is ready
,W/Thread-306( 3215): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6370]" dev="sockfs" ino=6370 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-306( 3215): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-306( 3215): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10288]" dev="sockfs" ino=10288 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-306( 3215): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19055]" dev="sockfs" ino=19055 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3160): Starting JXcore engine
,W/jxcore-log( 3160): Platform android
W/jxcore-log( 3160): 
W/jxcore-log( 3160): Process ARCH arm
W/jxcore-log( 3160): 
,I/jxcore-log( 3160): JXcore Cordova bridge is ready!
I/jxcore-log( 3160): 
,W/jxcore-log( 3160): JXcore engine is started
,I/jxcore-log( 3160): Toggling radios to true
I/jxcore-log( 3160): 
,D/BluetoothAdapter( 3160): enable(): BT is already enabled..!
,D/WifiService(  734): New client listening to asynchronous messages
,D/WifiService(  734): setWifiEnabled: true pid=3160, uid=10270
E/WifiService(  734): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3160): Radios toggled
I/jxcore-log( 3160): 
,I/jxcore-log( 3160): My device name is: LGE-Nexus 5
I/jxcore-log( 3160): 
,I/wpa_supplicant(  991): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  734): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  734): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1575): Read error: ssl=0xafdbbe00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1575): SSL shutdown failed: ssl=0xafdbbe00: I/O error during system call, Broken pipe
,D/ConnectivityService(  734): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  734): Start Disconnecting Watchdog 1
,E/native  (  734): do suspend true
,I/wpa_supplicant(  991): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  734): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
,D/Nat464Xlat(  734): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  734): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1626): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Disconnected - quitting
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  734): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1249): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  734): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiNetworkAgent(  734): NetworkAgent: NetworkAgent channel lost
,D/CAR.SERVICE( 3033): mConnectedToCar = false, abort
,E/ActivityThread( 3033): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3d13529a that was originally bound here
E/ActivityThread( 3033): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3d13529a that was originally bound here
E/ActivityThread( 3033): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3033): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3033): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3033): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3033): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3033): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3033): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3033): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3033): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3033): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3033): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3033): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3033): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3033): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3033): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3033): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3033): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3033): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3033): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3033): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3033): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3033): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3033): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3033): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@bb7edfd that was originally bound here
E/ActivityThread( 3033): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@bb7edfd that was originally bound here
E/ActivityThread( 3033): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3033): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3033): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3033): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3033): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3033): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3033): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3033): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3033): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3033): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3033): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3033): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3033): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3033): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3033): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3033): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3033): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3033): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3033): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3033): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3033): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3033): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  734): Unbind failed: could not find connection for android.os.BinderProxy@209fbf29
,I/wpa_supplicant(  991): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  991): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  991): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  991): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  734): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
,E/WifiStateMachine(  734): Start Dhcp Watchdog 2
,E/native  (  734): do suspend false
,E/WifiStateMachine(  734): scanCount==0 - aborting
,I/dhcpcd  ( 3261): version 5.5.6 starting
E/dhcpcd  ( 3261): get_duid: Read-only file system
,I/dhcpcd  ( 3261): wlan0: rebinding lease of 192.168.1.114
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  734): MasterInitialState.processMessage what=3
D/Tethering(  734): MasterInitialState.processMessage what=3
,I/dhcpcd  ( 3261): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,V/MusicLeanback( 2701): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1626): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1626): onCreate
,I/dhcpcd  ( 3261): wlan0: leased 192.168.1.114 for 86400 seconds
,I/art     (  734): Explicit concurrent mark sweep GC freed 38044(1820KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 1.495ms total 66.466ms
D/SystemUpdateService( 1626): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1626): active receiver: enabled
,E/GpsLocationProvider(  734): No APN found to select.
,E/GpsLocationProvider(  734): No APN found to select.
,I/iu.Environment( 1626): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1626): num queued entries: 0
,I/iu.UploadsManager( 1626): num updated entries: 0
,I/iu.SyncManager( 1626): NEXT; no task
,I/SystemUpdateService( 1626): showing system update notification
,I/Babel   ( 1925): connection state changed from CONNECTED to DISCONNECTED
,V/SystemUpdateService( 1626): retry (wakeup: false) in 3599938 ms
I/ValidateNoPeople(  734): skipping global notification
,I/ActivityManager(  734): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3303 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1626): onDestroy
,I/GAv4    ( 3303): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3303):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3303):   adb logcat -s GAv4
E/native  (  734): do suspend true
,W/GAv4    ( 3303): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  734): Adding iface wlan0 to network 101
,E/WifiStateMachine(  734): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,W/GAv4    ( 3303): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/ConnectivityService(  734): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  734): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  734): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  734): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  734): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  734): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  734): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  734): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  734): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  734): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  734): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1626): CM callback handler got msg 524290
,W/GAv4    ( 3303): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Feb 2016 13:04:36 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454591076541], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454591076528]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Validated
D/ConnectivityService(  734): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  734): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  734): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1626): CM callback handler got msg 524290
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1249): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WebViewFactory( 3303): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3303): Time to load native libraries: 2 ms (timestamps 4431-4433)
I/LibraryLoader( 3303): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3303): Binding Chromium to main looper Looper (main, tid 1) {1b5a95a7}
I/LibraryLoader( 3303): Expected native library version number "",actual native library version number ""
I/chromium( 3303): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3303): Initializing chromium process, singleProcess=true
W/art     ( 3303): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3303): ApplicationContext is null in ApplicationStatus
,W/chromium( 3303): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3303): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3303): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3303): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3303): Requires BLUETOOTH permission
I/NSApplication( 3303): Starting up...
,I/ActivityManager(  734): Killing 2673:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,I/jxcore-log( 3160): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3160): 
,W/libprocessgroup(  734): failed to open /acct/uid_10003/pid_2673/cgroup.procs: No such file or directory
,V/MusicLeanback( 2701): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1626): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1626): onCreate
,D/SystemUpdateService( 1626): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1626): active receiver: enabled
,I/SystemUpdateService( 1626): showing system update notification
,I/iu.Environment( 1626): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1626): num queued entries: 0
I/iu.UploadsManager( 1626): num updated entries: 0
I/iu.SyncManager( 1626): NEXT; no task
,I/ValidateNoPeople(  734): skipping global notification
,V/SystemUpdateService( 1626): retry (wakeup: false) in 3599956 ms
,D/SystemUpdateService( 1626): onDestroy
,I/Babel   ( 1925): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  734): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3160): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3160): 
,I/jxcore-log( 3160): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3160): 
,I/jxcore-log( 3160): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3160): 
,I/jxcore-log( 3160): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3160): 
,I/jxcore-log( 3160): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3160): 
,I/jxcore-log( 3160): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3160): 
,I/jxcore-log( 3160): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3160): 
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  734): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2701): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2701): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1626): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1626): onCreate
,E/GpsLocationProvider(  734): No APN found to select.
,D/SystemUpdateService( 1626): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1626): active receiver: enabled
,I/SystemUpdateService( 1626): showing system update notification
,I/ValidateNoPeople(  734): skipping global notification
,V/SystemUpdateService( 1626): retry (wakeup: false) in 3599953 ms
,D/SystemUpdateService( 1626): onDestroy
,I/jxcore-log( 3160): Test app app.js loaded
I/jxcore-log( 3160): 
,I/chromium( 3160): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3160): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3160): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3160): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3160): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3160): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3160): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3160): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3160): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3160): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3160): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26a31a32 added. We now have 1 listener(s)
,I/jxcore-log( 3160): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3160): 
,V/GLSActivity( 1575): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1575): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2583): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2583): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1575): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1575): Vacuum at: now=1454591098806 tag=VacuumService
,I/PhenotypeConfigurator( 1575): Scheduling Phenotype for one-off execution 5198 seconds from now (1454591099186)
,D/GetConfigurationSnapshotOperation( 1575): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1575): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1575): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1575): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1575): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ClearcutLoggerApiImpl( 1575): disconnect managed GoogleApiClient
,I/jxcore-log( 3160): --= Surplus to requirements =--
I/jxcore-log( 3160): 
I/jxcore-log( 3160): ****TEST TOOK:  ms ****
I/jxcore-log( 3160): 
I/jxcore-log( 3160): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3160): 
,D/AndroidRuntime( 3502): 
D/AndroidRuntime( 3502): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3502): CheckJNI is OFF
,D/AndroidRuntime( 3502): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  734): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg,
I/ActivityManager(  734): Killing 3160:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  734): WIN DEATH: Window{33fd5844 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  734): Client connection lost with reason: 4
,W/PackageSettings(  734): Skipping PackageSetting{209a5d01 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  734):   Force finishing activity ActivityRecord{2788ce50 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  734): Spurious death for ProcessRecord{38f52b93 3160:com.test.thalitest/u0a270}, curProc for 3160: null
,I/ActivityManager(  734): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1357): Explicit concurrent mark sweep GC freed 13341(948KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 325us total 20.861ms
,I/art     ( 1321): Explicit concurrent mark sweep GC freed 3885(289KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 919us total 33.145ms
,W/GeofencerStateMachine( 1575): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  734): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1096): resetDictionaries() : en_US
,I/art     ( 1626): Explicit concurrent mark sweep GC freed 5609(274KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/29MB, paused 475us total 82.420ms
,I/Keyboard.Facilitator.DecoderInitializer( 1096): run()
,D/VoicemailCleanupService( 2821): Cleaning up data for package: com.test.thalitest
,I/art     (  734): Explicit concurrent mark sweep GC freed 36807(1944KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 1.787ms total 90.179ms
,I/Decoder ( 1096): createOrResetDecoder
,I/Adreno-EGL(  942): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  942): Initialized EGL, version 1.4
,I/UpdateIcingCorporaServi( 1357): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1321): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@21eb6c32 new=com.google.android.velvet.VelvetApplication@21eb6c32
,D/OpenGLRenderer(  942): Enabling debug mode 0
,I/ActivityManager(  734): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3543 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ConfigService( 1575): onCreate
,D/BackupManagerService(  734): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  734): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  734): removeObsoleteFile: deleting file=216_task.xml
,W/InputMethodManagerService(  734): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@24e2a9ec (uid=10034 pid=942)
,W/ResourcesManager( 1321): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Launcher( 1321): Deferring update until onResume
I/Keyboard.Facilitator.MainLanguageModelLoader( 1096): run()
,I/art     (  734): Explicit concurrent mark sweep GC freed 7534(390KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.603ms total 145.957ms
,W/ResourcesManager( 1321): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ContextImpl( 3543): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1096): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1096): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1096): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1096): run()
I/StatsUtilsManager( 1096): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1096): shouldRecordStats() = Too Soon
D/ChimeraCfgMgr( 1626): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1626): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1626): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1626): Module APK com.google.android.play.games already loaded
I/ActivityManager(  734): Killing 2655:com.android.settings/1000 (adj 15): empty #17
I/Launcher( 1321): Deferring update until onResume
,I/UpdateIcingCorporaServi( 1357): UpdateCorporaTask done [took 175 ms] updated apps [took 175 ms] 
,D/PackageBroadcastService( 1626): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1626): Clearing selected account for com.test.thalitest
,D/WifiService(  734): Client connection lost with reason: 4
,D/AndroidRuntime( 3502): Shutting down VM
,W/libprocessgroup(  734): failed to open /acct/uid_1000/pid_2655/cgroup.procs: No such file or directory
,I/LocationSettingsChecker( 1626): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1575): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1575): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1626): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1626): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1626): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1626): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1626): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1626): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1626): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1626): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1626): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1626): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1626): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1626): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1626): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  734): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3576 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,W/BaseAppContext( 1626): Using Auth Proxy for data requests.
,W/BaseAppContext( 1626): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1626): App measurement is starting up, version: 8489
I/GMPM-SVC( 1626): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/Icing   ( 1626): doRemovePackageData com.test.thalitest
,I/ActivityManager(  734): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3601 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  734): Killing 2529:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10070/pid_2529/cgroup.procs: No such file or directory
,I/ActivityManager(  734): Killing 1994:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10031/pid_1994/cgroup.procs: No such file or directory
,D/ExternalStorage( 3601): After updating volumes, found 1 active roots

```
