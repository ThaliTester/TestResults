#### Test 561517803567b2a_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3205): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3205):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3205):   adb logcat -s GAv4
W/GAv4    ( 3205): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3205): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3205): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3205): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
I/qtaguid ( 2637): Failed write_ctrl(u 42) res=-1 errno=22
I/qtaguid ( 2637): Untagging socket 42 failed errno=-22
W/NetworkManagementSocketTagger( 2637): untagSocket(42) failed with errno -22
--------- beginning of system
I/ActivityManager(  736): Killing 2371:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
W/libprocessgroup(  736): failed to open /acct/uid_1000/pid_2371/cgroup.procs: No such file or directory
V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2637): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
W/ResourcesManager( 3205): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3205): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 3205): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3205): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3205): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/qtaguid ( 2637): Failed write_ctrl(u 42) res=-1 errno=22
I/qtaguid ( 2637): Untagging socket 42 failed errno=-22
W/NetworkManagementSocketTagger( 2637): untagSocket(42) failed with errno -22
I/Icing   ( 1643): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1643): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1643): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
W/ResourcesManager( 2637): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2637): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/Icing   ( 1643): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
W/ResourcesManager( 2637): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/Finsky  ( 2637): [1] DailyHygiene.access$600: Logging device features
D/DeviceConnectionService( 1604): client connected with version: 8296000
D/Finsky  ( 2637): [265] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2637): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2637): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  736): Killing 2604:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
I/ActivityManager(  736): Killing 2454:com.google.android.youtube/u0a80 (adj 15): empty #18
W/libprocessgroup(  736): failed to open /acct/uid_10069/pid_2604/cgroup.procs: No such file or directory
W/libprocessgroup(  736): failed to open /acct/uid_10080/pid_2454/cgroup.procs: No such file or directory
,I/ActivityManager(  736): Killing 2557:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
W/libprocessgroup(  736): failed to open /acct/uid_10045/pid_2557/cgroup.procs: No such file or directory
D/AndroidRuntime( 3276): 
D/AndroidRuntime( 3276): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3276): CheckJNI is OFF
D/AndroidRuntime( 3276): Calling main entry com.android.commands.am.Am
I/ActivityManager(  736): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  736): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3300 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3276): Shutting down VM
I/art     (  196): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 746us total 11.944ms
I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.816ms
I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.395ms
V/ActivityManager(  736): Display changed displayId=0
I/WebViewFactory( 3300): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3300): Time to load native libraries: 2 ms (timestamps 215-217)
I/LibraryLoader( 3300): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3300): Binding Chromium to main looper Looper (main, tid 1) {16f6474c}
I/LibraryLoader( 3300): Expected native library version number "",actual native library version number ""
I/chromium( 3300): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3300): Initializing chromium process, singleProcess=true
,W/art     ( 3300): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3300): ApplicationContext is null in ApplicationStatus
,W/chromium( 3300): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3300): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3300): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3300): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  736): Message: 20
D/BluetoothManagerService(  736): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@107db1b7:true
,W/art     ( 3300): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3300): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3300): CordovaWebView is running on device made by: LGE
,W/art     ( 3300): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3300): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3300): Render dirty regions requested: true
,D/Atlas   ( 3300): Validating map...
,W/chromium( 3300): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3300): Initialized EGL, version 1.4
D/OpenGLRenderer( 3300): Enabling debug mode 0
,D/CAR.SERVICE( 3083): mConnectedToCar = false, abort
,W/IInputConnectionWrapper( 3300): showStatusIcon on inactive InputConnection
,E/ActivityThread( 3083): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3363f79d that was originally bound here
E/ActivityThread( 3083): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3363f79d that was originally bound here
E/ActivityThread( 3083): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3083): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3083): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3083): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3083): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3083): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3083): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3083): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3083): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3083): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3083): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3083): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3083): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3083): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3083): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3083): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3083): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3083): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3083): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3083): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3083): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3083): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3083): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3083): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3b6a200c that was originally bound here
E/ActivityThread( 3083): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3b6a200c that was originally bound here
E/ActivityThread( 3083): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3083): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3083): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3083): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3083): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3083): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3083): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3083): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3083): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3083): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3083): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3083): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3083): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3083): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3083): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3083): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3083): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3083): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3083): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3083): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3083): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3083): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  736): Unbind failed: could not find connection for android.os.BinderProxy@19b4d4c0
,I/ActivityManager(  736): Displayed com.test.thalitest/.MainActivity: +464ms (total +59s814ms)
,W/BindingManager( 3300): Cannot call determinedVisibility() - never saw a connection for the pid: 3300
,D/JsMessageQueue( 3300): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3300): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,I/chromium( 3300): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3300): Initializing JXcore engine
W/jxcore-log( 3300): JXcore engine is ready
,W/Thread-296( 3358): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9388]" dev="sockfs" ino=9388 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-296( 3358): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3097 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-296( 3358): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10355]" dev="sockfs" ino=10355 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-296( 3358): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19767]" dev="sockfs" ino=19767 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3300): Starting JXcore engine
,W/jxcore-log( 3300): Platform android
W/jxcore-log( 3300): 
,W/jxcore-log( 3300): Process ARCH arm
W/jxcore-log( 3300): 
,I/jxcore-log( 3300): JXcore Cordova bridge is ready!
I/jxcore-log( 3300): 
W/jxcore-log( 3300): JXcore engine is started
,I/jxcore-log( 3300): Toggling radios to true
I/jxcore-log( 3300): 
,D/BluetoothAdapter( 3300): enable(): BT is already enabled..!
,D/WifiService(  736): New client listening to asynchronous messages
,D/WifiService(  736): setWifiEnabled: true pid=3300, uid=10270
E/WifiService(  736): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3300): Radios toggled
I/jxcore-log( 3300): 
I/jxcore-log( 3300): My device name is: LGE-Nexus 5
I/jxcore-log( 3300): 
,I/wpa_supplicant(  990): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  736): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  736): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1604): Read error: ssl=0xb3b28e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1604): SSL shutdown failed: ssl=0xb3b28e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  736): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  736): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  736): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  736): Start Disconnecting Watchdog 1
I/wpa_supplicant(  990): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  736): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  736): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  736): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  736): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Disconnected - quitting
,D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1643): CM callback handler got msg 524292
,D/ConnectivityService(  736): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  736): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/TelephonyNetworkFactory( 1255): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  736): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  990): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  990): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  990): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  990): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  736): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  736): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
E/WifiStateMachine(  736): Start Dhcp Watchdog 2
,E/native  (  736): do suspend false
,E/WifiStateMachine(  736): scanCount==0 - aborting
,I/dhcpcd  ( 3392): version 5.5.6 starting
E/dhcpcd  ( 3392): get_duid: Read-only file system
,I/dhcpcd  ( 3392): wlan0: rebinding lease of 192.168.1.114
,D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  736): MasterInitialState.processMessage what=3
,D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  736): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2759): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/dhcpcd  ( 3392): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/SystemUpdateService( 1643): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1643): onCreate
,E/GpsLocationProvider(  736): No APN found to select.
,D/SystemUpdateService( 1643): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/GpsLocationProvider(  736): No APN found to select.
,I/iu.Environment( 1643): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1643): num queued entries: 0
I/iu.UploadsManager( 1643): num updated entries: 0
,I/dhcpcd  ( 3392): wlan0: leased 192.168.1.114 for 86400 seconds
,I/SystemUpdateService( 1643): active receiver: enabled
,I/iu.SyncManager( 1643): NEXT; no task
,I/SystemUpdateService( 1643): showing system update notification
,I/Babel   ( 1926): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  736): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3405 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ValidateNoPeople(  736): skipping global notification
,V/SystemUpdateService( 1643): retry (wakeup: false) in 3599917 ms
,D/SystemUpdateService( 1643): onDestroy
,I/GAv4    ( 3405): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3405):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3405):   adb logcat -s GAv4
,W/GAv4    ( 3405): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3405): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3405): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/native  (  736): do suspend true
,D/ConnectivityService(  736): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  736): Adding iface wlan0 to network 101
E/WifiStateMachine(  736): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  736): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  736): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  736): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  736): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  736): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  736): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  736): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  736): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  736): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  736):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  736): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  736): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  736): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1643): CM callback handler got msg 524290
,I/WebViewFactory( 3405): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3405): Time to load native libraries: 1 ms (timestamps 6663-6664)
,I/LibraryLoader( 3405): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3405): Binding Chromium to main looper Looper (main, tid 1) {e3285e0}
I/LibraryLoader( 3405): Expected native library version number "",actual native library version number ""
,I/chromium( 3405): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jan 2016 11:00:28 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452855628178], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452855628158]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Validated
D/ConnectivityService(  736): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  736): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  736): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  736): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1643): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1255): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/BrowserStartupController( 3405): Initializing chromium process, singleProcess=true
W/art     ( 3405): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3405): ApplicationContext is null in ApplicationStatus
,W/chromium( 3405): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3405): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3405): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3405): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3405): Requires BLUETOOTH permission
,I/NSApplication( 3405): Starting up...
,I/ActivityManager(  736): Killing 2734:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10003/pid_2734/cgroup.procs: No such file or directory
,V/MusicLeanback( 2759): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1643): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1643): onCreate
,I/art     (  736): Explicit concurrent mark sweep GC freed 43863(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 996us total 73.797ms
,D/SystemUpdateService( 1643): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1643): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1643): num queued entries: 0
I/iu.UploadsManager( 1643): num updated entries: 0
,I/SystemUpdateService( 1643): active receiver: enabled
,I/iu.SyncManager( 1643): NEXT; no task
,I/SystemUpdateService( 1643): showing system update notification
,I/ValidateNoPeople(  736): skipping global notification
,V/SystemUpdateService( 1643): retry (wakeup: false) in 3599972 ms
,D/SystemUpdateService( 1643): onDestroy
,I/Babel   ( 1926): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  736): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  736): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2759): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2759): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1643): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1643): onCreate
,D/SystemUpdateService( 1643): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/GpsLocationProvider(  736): No APN found to select.
,I/SystemUpdateService( 1643): active receiver: enabled
,I/SystemUpdateService( 1643): showing system update notification
,I/ValidateNoPeople(  736): skipping global notification
,V/SystemUpdateService( 1643): retry (wakeup: false) in 3599987 ms
,D/SystemUpdateService( 1643): onDestroy
,D/Finsky  ( 2637): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2637): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 3300): Test app app.js loaded
I/jxcore-log( 3300): 
,I/chromium( 3300): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1604): Vacuum at: now=1452855647274 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1604): disconnect managed GoogleApiClient
,I/jxcore-log( 3300): TAP version 13
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # multiplex can send data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 1 String should be length:200
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # basic
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 2 sane
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # another
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 3 sane
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 4 should be equal
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 5 null
I/jxcore-log( 3300): 
I/jxcore-log( 3300): ok 6 (unnamed assert)
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 7 should be equal
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 8 should not throw
I/jxcore-log( 3300): 
I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 9 (unnamed assert)
I/jxcore-log( 3300): 
I/jxcore-log( 3300): ok 10 (unnamed assert)
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 11 should not throw
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 12 should be equal
I/jxcore-log( 3300): 
I/jxcore-log( 3300): ok 13 should be equal
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 14 should be equal
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # failed to get mobile documents path
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 15 should be equal
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 16 should be equal
I/jxcore-log( 3300): 
I/jxcore-log( 3300): ok 17 should be equal
I/jxcore-log( 3300): 
I/jxcore-log( 3300): ok 18 should be equal
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # #init should register the networkChanged event
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 19 should be equal
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # #startBroadcasting should throw on null device name
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 20 should throw
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 21 should throw
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 22 should throw
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 23 should throw
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # #startBroadcasting should throw on negative port
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 24 should throw
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # #startBroadcasting should throw on too large port
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 25 should throw
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 26 should be equal
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 27 should be equal
I/jxcore-log( 3300): 
I/jxcore-log( 3300): ok 28 should be equal
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 29 should be equal
I/jxcore-log( 3300): 
I/jxcore-log( 3300): ok 30 should be equal
I/jxcore-log( 3300): 
I/jxcore-log( 3300): ok 31 should be equal
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 32 should be equal
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 33 should be equal
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 34 should be equal
I/jxcore-log( 3300): 
I/jxcore-log( 3300): ok 35 should be equal
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 36 should be equal
I/jxcore-log( 3300): 
I/jxcore-log( 3300): ok 37 should be equal
I/jxcore-log( 3300): 
I/jxcore-log( 3300): ok 38 should be equal
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 39 should be equal
I/jxcore-log( 3300): 
I/jxcore-log( 3300): ok 40 should be equal
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 41 should be equal
I/jxcore-log( 3300): 
I/jxcore-log( 3300): ok 42 should be equal
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 43 should be equal
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 44 should be equal
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843022.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843022.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: OK
I/io.jxcore.node.ConnectionHelper( 3300): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843022.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): createAdvertiseData: From: 1452855843022.3300 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3300): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843022.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843022.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452855843022.3300","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: true
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843022.3300
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 3300): start: OK
,I/jxcore-log( 3300): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 3300): 
,I/io.jxcore.node.ConnectionHelper( 3300): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3300): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3300): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843117.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843117.3300","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: OK
I/io.jxcore.node.ConnectionHelper( 3300): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843117.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): createAdvertiseData: From: 1452855843117.3300 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3300): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843117.3300","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843117.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452855843117.3300","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): start: Starting P2P device discovery...
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843117.3300
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3300): start: OK
I/jxcore-log( 3300): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stop: Stopping peer discovery...
D/BluetoothLeScanner( 3300): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3300): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843158.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843158.3300","ra":"34:FC:EF:11:AE:67"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: OK
I/io.jxcore.node.ConnectionHelper( 3300): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843158.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): createAdvertiseData: From: 1452855843158.3300 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3300): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843158.3300","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843158.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452855843158.3300","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): start: Starting P2P device discovery...
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843158.3300
,I/io.jxcore.node.ConnectionHelper( 3300): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/jxcore-log( 3300): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/io.jxcore.node.ConnectionHelper( 3300): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
D/BluetoothLeScanner( 3300): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3300): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843196.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843196.3300","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: OK
I/io.jxcore.node.ConnectionHelper( 3300): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843196.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): createAdvertiseData: From: 1452855843196.3300 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3300): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843196.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843196.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452855843196.3300","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): start: Starting P2P device discovery...
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843196.3300
,I/io.jxcore.node.ConnectionHelper( 3300): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
I/jxcore-log( 3300): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 3300): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant(  990): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3300): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,D/BluetoothLeScanner( 3300): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): stop: Stopping services
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service requests cleared successfully
,I/jxcore-log( 3300): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843228.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843228.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: OK
I/io.jxcore.node.ConnectionHelper( 3300): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843228.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): createAdvertiseData: From: 1452855843228.3300 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3300): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843228.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843228.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452855843228.3300","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): start: Starting P2P device discovery...
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3300): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843228.3300
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: OK
I/jxcore-log( 3300): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 3300): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3300): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: NOT_STARTED
I/wpa_supplicant(  990): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onServerStopped
D/BluetoothLeScanner( 3300): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): stop: Stopping services
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): stop: Stopping P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3300): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 3300): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843253.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843253.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: OK
I/io.jxcore.node.ConnectionHelper( 3300): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843253.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): createAdvertiseData: From: 1452855843253.3300 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3300): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843253.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843253.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452855843253.3300","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843253.3300
I/io.jxcore.node.ConnectionHelper( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: OK
I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/jxcore-log( 3300): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 3300): 
I/wpa_supplicant(  990): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 3300): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothLeScanner( 3300): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
I/jxcore-log( 3300): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 3300): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843280.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843280.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: OK
I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3300): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843280.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): createAdvertiseData: From: 1452855843280.3300 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3300): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843280.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843280.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452855843280.3300","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): start: Starting P2P device discovery...
I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3300): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843280.3300
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: OK
I/jxcore-log( 3300): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/BluetoothLeScanner( 3300): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): release: No more listeners, de-initializing...
I/wpa_supplicant(  990): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
I/jxcore-log( 3300): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 3300): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service requests cleared successfully
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843305.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843305.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: OK
I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3300): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843305.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): createAdvertiseData: From: 1452855843305.3300 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3300): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843305.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843305.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452855843305.3300","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3300): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843305.3300
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local service added successfully
I/jxcore-log( 3300): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 3300): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3300): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onServerStopped
I/wpa_supplicant(  990): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
D/BluetoothLeScanner( 3300): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
I/jxcore-log( 3300): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 3300): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843330.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843330.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: OK
I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3300): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843330.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): createAdvertiseData: From: 1452855843330.3300 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3300): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843330.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843330.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452855843330.3300","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3300): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843330.3300
I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3300): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 3300): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3300): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): stop: Stopping Bluetooth...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): Shutting down...
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: NOT_STARTED
I/wpa_supplicant(  990): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Exiting thread
D/BluetoothLeScanner( 3300): could not find callback wrapper
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): stop: Stopping P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3300): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 3300): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843356.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843356.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: OK
I/io.jxcore.node.ConnectionHelper( 3300): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843356.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): createAdvertiseData: From: 1452855843356.3300 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3300): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843356.3300","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843356.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452855843356.3300","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: INITIALIZED,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3300): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843356.3300
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3300): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 3300): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: OK
I/io.jxcore.node.ConnectionHelper( 3300): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
,I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/wpa_supplicant(  990): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,D/BluetoothLeScanner( 3300): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service requests cleared successfully
I/jxcore-log( 3300): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # ThaliEmitter calls startBroadcasting twice with error,
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843864.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843864.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: OK
I/io.jxcore.node.ConnectionHelper( 3300): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843864.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): createAdvertiseData: From: 1452855843864.3300 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3300): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843864.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452855843864.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452855843864.3300","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): start: Starting P2P device discovery...
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855843864.3300
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3300): start: OK
I/jxcore-log( 3300): ok 65 Should be able to call startBroadcasting without error
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 66 Cannot call startBroadcasting twice
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3300): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3300): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855844352.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855844352.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: OK
I/io.jxcore.node.ConnectionHelper( 3300): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855844352.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): createAdvertiseData: From: 1452855844352.3300 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3300): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855844352.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452855844352.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452855844352.3300","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): start: Starting P2P device discovery...
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855844352.3300
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3300): start: OK
I/jxcore-log( 3300): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper( 3300): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
E/io.jxcore.node.ConnectionHelper( 3300): connect: Invalid Bluetooth address: foobar
I/jxcore-log( 3300): ok 69 Should not connect to a bad peer
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3300): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3300): ok 70 Should be able to call stopBroadcasting without error
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855844745.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855844745.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: OK
I/io.jxcore.node.ConnectionHelper( 3300): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855844745.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): createAdvertiseData: From: 1452855844745.3300 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3300): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855844745.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452855844745.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452855844745.3300","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): start: Starting P2P device discovery...
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855844745.3300
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3300): start: OK
I/jxcore-log( 3300): ok 71 Should be able to call startBroadcasting without error
I/jxcore-log( 3300): 
D/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
I/jxcore-log( 3300): ok 72 Disconnect should fail to a non-existant peer 
I/jxcore-log( 3300): 
,I/io.jxcore.node.ConnectionHelper( 3300): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3300): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3300): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # ThaliEmitter can discover and connect to peers
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855844976.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855844976.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: OK
I/io.jxcore.node.ConnectionHelper( 3300): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855844976.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): createAdvertiseData: From: 1452855844976.3300 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3300): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855844976.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452855844976.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452855844976.3300","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): start: Starting P2P device discovery...
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855844976.3300
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3300): start: OK
I/jxcore-log( 3300): ok 74 Should be able to call startBroadcasting without error
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): start: Cannot start, because not initialized
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): start: Cannot start, because not initialized
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): start: Cannot start, because not initialized
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): start: Cannot start, because not initialized
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,W/bt-btif ( 2102): info:x10
,D/        ( 2102): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 2102): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2102): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2102): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2102): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2102): Entering PendingCommandState State
,W/BluetoothEventManager( 2711): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2711): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 2102): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2102): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2102): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,W/BluetoothEventManager( 2711): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2711): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 2102): StableState(): Entering Off State
,W/bt-btif ( 2102): new conn_srvc id:26, app_id:255
W/bt-btif ( 2102): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2102): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Incoming connection initialized (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Entering thread (ID: 313)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): onBytesRead: Read 77 bytes successfully (thread ID: 313)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Got valid identity from [F8:95:C7:87:85:54 1452855844979.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): onBytesWritten: 77 bytes successfully written (thread ID: 313)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): removeThreadFromList: Removing thread with ID 313
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Handshake thread disposed (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onIncomingConnectionConnected: [F8:95:C7:87:85:54 1452855844979.6230]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnected: [F8:95:C7:87:85:54 1452855844979.6230]
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Incoming connection to peer [F8:95:C7:87:85:54 1452855844979.6230]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 1452855844979.6230] is available
,I/io.jxcore.node.ConnectionHelper( 3300): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): connect: [F8:95:C7:87:85:54 1452855844979.6230]
,I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Incoming socket thread, for peer [F8:95:C7:87:85:54 1452855844979.6230], created successfully
D/io.jxcore.node.ConnectionHelper( 3300): onConnected: The total number of connections is now 1
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Exiting thread (ID: 313)
D/io.jxcore.node.IncomingSocketThread( 3300): Entering thread (ID: 314)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Trying to start connecting to G3s-1 in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setInsecureRfcommSocketPortNumber: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnecting: G3s-1 F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Started connecting to G3s-1 in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3300): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 315)
E/io.jxcore.node.IncomingSocketThread( 3300): Failed to create the local streams: failed to connect to localhost/127.0.0.1 (port 5001): connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 3300): java.net.ConnectException: failed to connect to localhost/127.0.0.1 (port 5001): connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 3300): 	at libcore.io.IoBridge.connect(IoBridge.java:124)
E/io.jxcore.node.IncomingSocketThread( 3300): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
E/io.jxcore.node.IncomingSocketThread( 3300): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:163)
E/io.jxcore.node.IncomingSocketThread( 3300): 	at java.net.Socket.startupSocket(Socket.java:590)
E/io.jxcore.node.IncomingSocketThread( 3300): 	at java.net.Socket.<init>(Socket.java:226)
E/io.jxcore.node.IncomingSocketThread( 3300): 	at io.jxcore.node.IncomingSocketThread.run(IncomingSocketThread.java:52)
E/io.jxcore.node.IncomingSocketThread( 3300): Caused by: android.system.ErrnoException: connect failed: ECONNREFUSED (Connection refused)
E/io.jxcore.node.IncomingSocketThread( 3300): 	at libcore.io.Posix.connect(Native Method)
E/io.jxcore.node.IncomingSocketThread( 3300): 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:111)
E/io.jxcore.node.IncomingSocketThread( 3300): 	at libcore.io.IoBridge.connectErrno(IoBridge.java:137)
E/io.jxcore.node.IncomingSocketThread( 3300): 	at libcore.io.IoBridge.connect(IoBridge.java:122)
E/io.jxcore.node.IncomingSocketThread( 3300): 	... 5 more
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3300): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 1452855844979.6230] disconnected: Failed to create the local streams: failed to connect to localhost/127.0.0.1 (port 5001): connect failed: ECONNREFUSED (Connection refused)
,I/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 314
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Nothing to close
I/io.jxcore.node.IncomingSocketThread( 3300): closeBluetoothSocketAndStreams
D/BTIF_SOCK( 2102): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.IncomingSocketThread( 3300): Exiting thread (ID: 314)
,W/bt-btif ( 2102): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
E/bt-btif ( 2102): bta_jv_port_mgmt_sr_cback, p_cb:0x0, p_cb->p_cback0x0
,W/bt-sdp  ( 2102): process_service_search_attr_rsp
,W/bt-btif ( 2102): new conn_srvc id:26, app_id:1
W/bt-btif ( 2102): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2102): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onSocketConnected: [F8:95:C7:87:85:54 1452855844979.6230] (thread ID: 315)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 315)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesWritten: 77 bytes successfully written (thread ID: 316)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Outgoing connection initialized (*handshake* thread ID: 316)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Exiting thread (thread ID: 315)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Entering thread (ID: 316)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesRead: Read 77 bytes successfully (thread ID: 316)
,W/bt-btif ( 2102): invalid rfc slot id: 19
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Handshake succeeded with [F8:95:C7:87:85:54 1452855844979.6230]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onHandshakeSucceeded: [F8:95:C7:87:85:54 1452855844979.6230] (thread ID: 315)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnected: [F8:95:C7:87:85:54 1452855844979.6230]
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing connection to peer [F8:95:C7:87:85:54 1452855844979.6230]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 1452855844979.6230] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:85:54 1452855844979.6230], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3300): setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): setConnectionTimeout: 15000
D/io.jxcore.node.ConnectionHelper( 3300): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Exiting thread (ID: 316)
,D/io.jxcore.node.OutgoingSocketThread( 3300): Entering thread (ID: 317)
,D/io.jxcore.node.OutgoingSocketThread( 3300): Server socket local port: 33481
,I/io.jxcore.node.OutgoingSocketThread( 3300): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3300): onListeningForIncomingConnections: Outgoing connection is using port 33481 (peer ID: F8:95:C7:87:85:54)
,I/jxcore-log( 3300): ok 75 Should be able to connect without error
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ok 76 Port should be within range
I/jxcore-log( 3300): 
,D/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:85:54
I/io.jxcore.node.OutgoingSocketThread( 3300): close
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Nothing to close
I/io.jxcore.node.OutgoingSocketThread( 3300): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 3300): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3300): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3300): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3300): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3300): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3300): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3300): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3300): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:74)
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 1452855844979.6230] disconnected: Failed to create local streams: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3300): Exiting thread (ID: 317)
,D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:85:54
,E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/jxcore-log( 3300): ok 77 Should be able to disconnect without error
I/jxcore-log( 3300): 
I/jxcore-log( 3300): setting stopBroadcasting callback and ending test.
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # setup
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): calling stopBroadcasting
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3300): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3300): stopBroadcasting returned undefined
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # ThaliEmitter can discover and connect to peers and then fail on double connect
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): # teardown
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855856615.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855856615.3300","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: OK
I/io.jxcore.node.ConnectionHelper( 3300): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855856615.3300
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): createAdvertiseData: From: 1452855856615.3300 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3300): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3300): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3300): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452855856615.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452855856615.3300","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452855856615.3300","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452855856615.3300
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 3300): start: OK
,I/jxcore-log( 3300): ok 78 Should be able to call startBroadcasting without error
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local services cleared successfully
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,E/bt-btm  ( 2102): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2102): onReceive
,D/BluetoothManagerService(  736): Message: 20
,D/BluetoothManagerService(  736): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23ad3b92:true
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: G3s-1
,D/btif_config_util( 2102): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding a new peer: [F8:95:C7:87:85:54 1452855856614.6230]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 1452855856614.6230] already in the list, will not add again
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED ,
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  736): Killing 2575:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10070/pid_2575/cgroup.procs: No such file or directory
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED ,
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  736): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3682 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 3682): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3682): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PhenotypeConfigurator( 1604): Scheduling Phenotype for one-off execution 10765 seconds from now (1452856529106)
,V/JNIHelp ( 3682): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/GetConfigurationSnapshotOperation( 1604): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1604): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1604): Using platform SSLCertificateSocketFactory
,W/System  ( 3682): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3682): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 3682): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 3740): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-20386788.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads-20386788.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3740): dex2oat took 33.972ms (threads: 4)
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/InstanceID/Rpc( 3682): Found 10008
,I/ActivityManager(  736): Killing 1997:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10031/pid_1997/cgroup.procs: No such file or directory
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED ,
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED ,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-smp  ( 2102): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2102): Plain text(LSB ~ MSB) = 12 a1 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2102): Encrypted text(LSB ~ MSB) = 22 76 3e ba e4 c3 ae 7f d2 be f3 7f b9 0d ba 55 
,W/bt-btm  ( 2102): Stopping oneshot timer
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/UsageStatsService(  736): User[0] Flushing usage stats to disk
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/HeadsetStateMachine( 2102): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 2102): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 2102): Disconnected process message: 11, size: 0
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED ,
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/ProcessStatsService(  736): Prepared write state in 30ms
,I/ProcessStatsService(  736): Prepared write state in 5ms
,I/ProcessStatsService(  736): Pruning old procstats: /data/system/procstats/state-2016-01-14-13-16-04.bin
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/art     (  736): Explicit concurrent mark sweep GC freed 166061(7MB) AllocSpace objects, 9(222KB) LOS objects, 33% free, 31MB/47MB, paused 1.065ms total 116.407ms
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/art     ( 1604): Explicit concurrent mark sweep GC freed 111475(6MB) AllocSpace objects, 26(439KB) LOS objects, 40% free, 23MB/39MB, paused 942us total 83.976ms
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"1452855856614.6230","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 1452855856614.6230]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 1452855856614.6230]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 1452855856614.6230], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 1452855856614.6230]
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,TIME-OUT KILL (timeout was 1800000ms),I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
D/AndroidRuntime( 3890): 
D/AndroidRuntime( 3890): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3890): CheckJNI is OFF
D/AndroidRuntime( 3890): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  736): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  736): Killing 3300:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
I/WindowState(  736): WIN DEATH: Window{192876a7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  736): Client connection lost with reason: 4
W/PackageSettings(  736): Skipping PackageSetting{170b520 com.example.hello/10278} due to missing metadata
I/ActivityManager(  736): Killing 2759:com.google.android.music:main/u0a60 (adj 13): empty for 1804s
I/ActivityManager(  736): Killing 3057:com.android.defcontainer/u0a5 (adj 13): empty for 1814s
I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
I/ActivityManager(  736): Killing 3083:com.google.android.gms:car/u0a8 (adj 13): empty for 1814s
I/ActivityManager(  736): Killing 3205:com.google.android.apps.docs/u0a40 (adj 13): empty for 1815s
I/ActivityManager(  736): Killing 3172:com.android.musicfx/u0a15 (adj 15): empty for 1816s
I/ActivityManager(  736): Killing 1484:com.google.android.partnersetup/u0a13 (adj 15): empty for 1816s
I/ActivityManager(  736): Killing 2017:com.android.providers.calendar/u0a2 (adj 15): empty for 1818s
I/ActivityManager(  736):   Force finishing activity ActivityRecord{ee16a63 u0 com.test.thalitest/.MainActivity t216}
W/ActivityManager(  736): Spurious death for ProcessRecord{3bd8ec95 3300:com.test.thalitest/u0a270}, curProc for 3300: null
W/libprocessgroup(  736): failed to open /acct/uid_10060/pid_2759/cgroup.procs: No such file or directory
W/libprocessgroup(  736): failed to open /acct/uid_10005/pid_3057/cgroup.procs: No such file or directory
W/libprocessgroup(  736): failed to open /acct/uid_10008/pid_3083/cgroup.procs: No such file or directory
W/libprocessgroup(  736): failed to open /acct/uid_10040/pid_3205/cgroup.procs: No such file or directory
W/libprocessgroup(  736): failed to open /acct/uid_10015/pid_3172/cgroup.procs: No such file or directory
W/libprocessgroup(  736): failed to open /acct/uid_10013/pid_1484/cgroup.procs: No such file or directory
W/libprocessgroup(  736): failed to open /acct/uid_10002/pid_2017/cgroup.procs: No such file or directory
I/ActivityManager(  736): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  944): Initialized EGL, version 1.4
D/OpenGLRenderer(  944): Enabling debug mode 0
W/InputMethodManagerService(  736): Got RemoteException sending setActive(false) notification to pid 3300 uid 10270
I/Keyboard.Facilitator( 1107): onFinishInput()
I/art     ( 1643): Explicit concurrent mark sweep GC freed 12030(594KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/30MB, paused 491us total 91.321ms
I/InputReader(  736): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1604): Ignoring removeGeofence because network location is disabled.
I/art     ( 1290): Explicit concurrent mark sweep GC freed 3989(295KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 492us total 55.787ms
I/art     ( 1380): Explicit concurrent mark sweep GC freed 4690(207KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 19MB/25MB, paused 323us total 73.085ms
D/VoicemailCleanupService( 1345): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator( 1107): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1107): run()
I/Decoder ( 1107): createOrResetDecoder
I/ActivityManager(  736): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=3935 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
I/art     (  736): Explicit concurrent mark sweep GC freed 89831(4MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.210ms total 80.999ms
I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
I/Keyboard.Facilitator.MainLanguageModelLoader( 1107): run()
D/BackupManagerService(  736): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  736): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.MainLanguageModelLoader( 1107): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loading LM = contacts
I/UpdateIcingCorporaServi( 1380): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loading LM = user
W/Launcher( 1290): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@15db395 new=com.google.android.velvet.VelvetApplication@15db395
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1107): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1107): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1107): run()
I/StatsUtilsManager( 1107): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1107): shouldRecordStats() = Too Soon
I/art     (  736): Explicit concurrent mark sweep GC freed 6431(340KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.316ms total 120.067ms
I/ActivityManager(  736): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3962 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  736): Killing 1926:com.google.android.talk/u0a54 (adj 15): empty for 1804s
D/AndroidRuntime( 3890): Shutting down VM
D/TaskPersister(  736): removeObsoleteFile: deleting file=216_task.xml
W/libprocessgroup(  736): failed to open /acct/uid_10054/pid_1926/cgroup.procs: No such file or directory
I/Launcher( 1290): Deferring update until onResume
W/ContextImpl( 3962): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/UpdateIcingCorporaServi( 1380): UpdateCorporaTask done [took 146 ms] updated apps [took 146 ms] 
D/PackageBroadcastService( 1643): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1643): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1643): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1643): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1643): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1643): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1643): Removing dialog suppression flag for package com.test.thalitest
W/ResourcesManager( 1290): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/NetworkScheduler.SchedulerReceiver( 1604): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1604): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
W/ResourcesManager( 1290): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/gH_CompatibleDatabase( 1643): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1643): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1643): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1643): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1643): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1643): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1643): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/Launcher( 1290): Deferring update until onResume
I/ActivityManager(  736): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3990 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
D/gH_CompatibleDatabase( 1643): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1643): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1643): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1643): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1643): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1643): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/BaseAppContext( 1643): Using Auth Proxy for data requests.
W/BaseAppContext( 1643): Using Auth Proxy for data requests.
I/GMPM-SVC( 1643): App measurement is starting up, version: 8489
I/GMPM-SVC( 1643): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/Icing   ( 1643): doRemovePackageData com.test.thalitest
I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
I/GAv4    ( 3990): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3990):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3990):   adb logcat -s GAv4
W/GAv4    ( 3990): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3990): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 3990): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3990): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 3990): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 3990): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak

```
