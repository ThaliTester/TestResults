#### Test 564496600f5d794_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
W/GAv4    ( 3213): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3213): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3213): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2704): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3213): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3213): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 3213): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  761): Killing 2156:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/System  ( 3213): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3213): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  761): failed to open /acct/uid_10038/pid_2156/cgroup.procs: No such file or directory
V/GLSActivity( 1608): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1654): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1654): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1654): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1654): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,I/ActivityManager(  761): Killing 2665:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
D/AndroidRuntime( 3280): 
D/AndroidRuntime( 3280): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3280): CheckJNI is OFF
W/libprocessgroup(  761): failed to open /acct/uid_10069/pid_2665/cgroup.procs: No such file or directory
D/CAR.SERVICE( 3093): mConnectedToCar = false, abort
E/ActivityThread( 3093): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@24edb035 that was originally bound here
E/ActivityThread( 3093): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@24edb035 that was originally bound here
E/ActivityThread( 3093): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3093): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3093): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3093): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3093): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3093): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3093): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3093): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3093): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3093): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3093): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3093): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3093): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3093): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3093): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3093): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3093): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3093): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3093): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3093): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3093): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3093): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3093): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/ActivityThread( 3093): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@196c0304 that was originally bound here
E/ActivityThread( 3093): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@196c0304 that was originally bound here
E/ActivityThread( 3093): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3093): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3093): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3093): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3093): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3093): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3093): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3093): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3093): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3093): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3093): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3093): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3093): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3093): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3093): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3093): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3093): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3093): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3093): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3093): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3093): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3093): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  761): Unbind failed: could not find connection for android.os.BinderProxy@267b1eeb
D/AndroidRuntime( 3280): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3308 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3280): Shutting down VM
V/ActivityManager(  761): Display changed displayId=0
I/WebViewFactory( 3308): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3308): Time to load native libraries: 2 ms (timestamps 8171-8173)
I/LibraryLoader( 3308): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3308): Binding Chromium to main looper Looper (main, tid 1) {21587244}
I/LibraryLoader( 3308): Expected native library version number "",actual native library version number ""
I/chromium( 3308): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3308): Initializing chromium process, singleProcess=true
W/art     ( 3308): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3308): ApplicationContext is null in ApplicationStatus
,W/chromium( 3308): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3308): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3308): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3308): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@294a068c:true
,W/art     ( 3308): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3308): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3308): CordovaWebView is running on device made by: LGE
,W/art     ( 3308): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3308): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3308): Render dirty regions requested: true
,D/Atlas   ( 3308): Validating map...
,W/chromium( 3308): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3308): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3308): Enabling debug mode 0
,W/BindingManager( 3308): Cannot call determinedVisibility() - never saw a connection for the pid: 3308
,W/IInputConnectionWrapper( 3308): showStatusIcon on inactive InputConnection
I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +445ms (total +56s501ms)
,D/JsMessageQueue( 3308): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3308): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257343360
,I/chromium( 3308): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3308): Initializing JXcore engine
W/jxcore-log( 3308): JXcore engine is ready
,W/Thread-301( 3360): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7706]" dev="sockfs" ino=7706 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-301( 3360): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-301( 3360): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6875]" dev="sockfs" ino=6875 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-301( 3360): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20058]" dev="sockfs" ino=20058 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3308): Starting JXcore engine
,W/jxcore-log( 3308): Platform android
W/jxcore-log( 3308): 
,W/jxcore-log( 3308): Process ARCH arm
W/jxcore-log( 3308): 
,I/jxcore-log( 3308): JXcore Cordova bridge is ready!
I/jxcore-log( 3308): 
,W/jxcore-log( 3308): JXcore engine is started
,I/jxcore-log( 3308): Toggling radios to true
I/jxcore-log( 3308): 
,D/BluetoothAdapter( 3308): enable(): BT is already enabled..!
,D/WifiService(  761): setWifiEnabled: true pid=3308, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  761): New client listening to asynchronous messages
,I/jxcore-log( 3308): Radios toggled
I/jxcore-log( 3308): 
I/jxcore-log( 3308): My device name is: LGE-Nexus 5
I/jxcore-log( 3308): 
I/wpa_supplicant(  984): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  761): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1608): Read error: ssl=0xb3c6ce00: I/O error during system call, Connection timed out
V/NativeCrypto( 1608): SSL shutdown failed: ssl=0xb3c6ce00: I/O error during system call, Broken pipe
D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiStateMachine(  761): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  984): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  761): do suspend true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/CommandListener(  179): Clearing all IP addresses on wlan0
D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524292
D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
,D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1279): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1654): CM callback handler got msg 524292
,D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  984): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  984): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  984): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  984): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  761): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  179): Setting iface cfg
E/WifiStateMachine(  761): Start Dhcp Watchdog 2
,E/native  (  761): do suspend false
,E/WifiStateMachine(  761): scanCount==0 - aborting
,I/dhcpcd  ( 3387): version 5.5.6 starting
E/dhcpcd  ( 3387): get_duid: Read-only file system
,I/dhcpcd  ( 3387): wlan0: rebinding lease of 192.168.1.114
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,D/Tethering(  761): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2820): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1654): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1654): onCreate
,D/SystemUpdateService( 1654): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1654): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,E/GpsLocationProvider(  761): No APN found to select.
,I/Babel   ( 1982): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 1654): num queued entries: 0
I/iu.UploadsManager( 1654): num updated entries: 0
I/iu.SyncManager( 1654): NEXT; no task
,I/SystemUpdateService( 1654): active receiver: enabled
,I/SystemUpdateService( 1654): showing system update notification
,I/ActivityManager(  761): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3399 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dhcpcd  ( 3387): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,E/GpsLocationProvider(  761): No APN found to select.
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1654): retry (wakeup: false) in 3599927 ms
,I/dhcpcd  ( 3387): wlan0: leased 192.168.1.114 for 86400 seconds
,D/SystemUpdateService( 1654): onDestroy
,I/GAv4    ( 3399): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3399):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3399):   adb logcat -s GAv4
,W/GAv4    ( 3399): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/native  (  761): do suspend true
,W/GAv4    ( 3399): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3399): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/WifiStateMachine(  761): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  761): Adding iface wlan0 to network 101
,E/ConnectivityService(  761): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  761): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  761): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  761): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  761): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/CSLegacyTypeTracker(  761): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1654): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 21 Jan 2016 10:02:08 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453370528591], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453370528576]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Validated
D/ConnectivityService(  761): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1654): CM callback handler got msg 524290
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1279): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WebViewFactory( 3399): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3399): Time to load native libraries: 2 ms (timestamps 4255-4257)
I/LibraryLoader( 3399): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3399): Binding Chromium to main looper Looper (main, tid 1) {2c317b96}
I/LibraryLoader( 3399): Expected native library version number "",actual native library version number ""
I/chromium( 3399): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3399): Initializing chromium process, singleProcess=true
W/art     ( 3399): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3399): ApplicationContext is null in ApplicationStatus
,W/chromium( 3399): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3399): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3399): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3399): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/jxcore-log( 3308): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3308): 
,W/AudioManagerAndroid( 3399): Requires BLUETOOTH permission
,I/NSApplication( 3399): Starting up...
,I/ActivityManager(  761): Killing 2609:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_2609/cgroup.procs: No such file or directory
,V/MusicLeanback( 2820): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1654): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1654): onCreate
,D/SystemUpdateService( 1654): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1654): active receiver: enabled
,I/iu.Environment( 1654): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1654): num queued entries: 0
I/iu.UploadsManager( 1654): num updated entries: 0
,I/SystemUpdateService( 1654): showing system update notification
,I/iu.SyncManager( 1654): NEXT; no task
,I/ValidateNoPeople(  761): skipping global notification
V/SystemUpdateService( 1654): retry (wakeup: false) in 3599965 ms
D/SystemUpdateService( 1654): onDestroy
,I/Babel   ( 1982): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3308): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3308): 
I/jxcore-log( 3308): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3308): 
,D/ConnectivityService(  761): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2820): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2820): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1654): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1654): onCreate
,D/SystemUpdateService( 1654): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1654): active receiver: enabled
,I/SystemUpdateService( 1654): showing system update notification
,E/GpsLocationProvider(  761): No APN found to select.
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1654): retry (wakeup: false) in 3599968 ms
,D/SystemUpdateService( 1654): onDestroy
,I/jxcore-log( 3308): Test app app.js loaded
I/jxcore-log( 3308): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 3308): BLE advertisement is supported
I/jxcore-log( 3308): 
I/chromium( 3308): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Finsky  ( 2704): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2704): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/art     (  761): Explicit concurrent mark sweep GC freed 44561(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.087ms total 64.016ms
,V/GLSActivity( 1608): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1608): Vacuum at: now=1453370547357 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1608): disconnect managed GoogleApiClient
,I/jxcore-log( 3308): TAP version 13
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # multiplex can send data
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 1 String should be length:200
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # basic
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 2 sane
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # another
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 3 sane
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 4 should be equal
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 5 null
I/jxcore-log( 3308): 
I/jxcore-log( 3308): ok 6 (unnamed assert)
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 7 should be equal
I/jxcore-log( 3308): 
I/jxcore-log( 3308): ok 8 should not throw
I/jxcore-log( 3308): 
I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 9 (unnamed assert)
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 10 (unnamed assert)
I/jxcore-log( 3308): 
I/jxcore-log( 3308): ok 11 should not throw
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 12 should be equal
I/jxcore-log( 3308): 
I/jxcore-log( 3308): ok 13 should be equal
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 14 should be equal
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # failed to get mobile documents path
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 15 should be equal
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 16 should be equal
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 17 should be equal
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 18 should be equal
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # #init should register the networkChanged event
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 19 should be equal
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # #startBroadcasting should throw on null device name
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown,
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 20 should throw
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 21 should throw
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 22 should throw
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 23 should throw
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # #startBroadcasting should throw on negative port
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 24 should throw
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # #startBroadcasting should throw on too large port
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 25 should throw
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 26 should be equal
I/jxcore-log( 3308): 
I/jxcore-log( 3308): ok 27 should be equal
I/jxcore-log( 3308): 
I/jxcore-log( 3308): ok 28 should be equal
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 29 should be equal
I/jxcore-log( 3308): 
I/jxcore-log( 3308): ok 30 should be equal
I/jxcore-log( 3308): 
I/jxcore-log( 3308): ok 31 should be equal
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 32 should be equal
I/jxcore-log( 3308): 
I/jxcore-log( 3308): ok 33 should be equal
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 34 should be equal
I/jxcore-log( 3308): 
I/jxcore-log( 3308): ok 35 should be equal
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 36 should be equal
I/jxcore-log( 3308): 
I/jxcore-log( 3308): ok 37 should be equal
I/jxcore-log( 3308): 
I/jxcore-log( 3308): ok 38 should be equal
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 39 should be equal
I/jxcore-log( 3308): 
I/jxcore-log( 3308): ok 40 should be equal
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 41 should be equal
I/jxcore-log( 3308): 
I/jxcore-log( 3308): ok 42 should be equal
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 43 should be equal
I/jxcore-log( 3308): 
I/jxcore-log( 3308): ok 44 should be equal
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748312.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748312.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3308): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: OK
I/io.jxcore.node.ConnectionHelper( 3308): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748312.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): createAdvertiseData: From: 1453370748312.3308 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3308): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748312.3308","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748312.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453370748312.3308","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_WIFI
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748312.3308
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/io.jxcore.node.ConnectionHelper( 3308): start: OK
I/jxcore-log( 3308): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 3308): 
,I/io.jxcore.node.ConnectionHelper( 3308): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3308): could not find callback wrapper
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: NOT_STARTED
I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/jxcore-log( 3308): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 3308): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748399.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748399.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3308): Service requests cleared successfully
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3308): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: OK
,I/io.jxcore.node.ConnectionHelper( 3308): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748399.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): createAdvertiseData: From: 1453370748399.3308 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3308): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748399.3308","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748399.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453370748399.3308","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_WIFI
I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748399.3308
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
,I/io.jxcore.node.ConnectionHelper( 3308): start: OK
,I/jxcore-log( 3308): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 3308): 
I/io.jxcore.node.ConnectionHelper( 3308): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stop: Stopping peer discovery...
D/BluetoothLeScanner( 3308): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): stop: Stopping P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3308): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3308): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 3308): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748427.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748427.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3308): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: RUNNING,
I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: OK
I/io.jxcore.node.ConnectionHelper( 3308): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748427.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): createAdvertiseData: From: 1453370748427.3308 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3308): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748427.3308","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748427.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453370748427.3308","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_WIFI
I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748427.3308
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_WIFI
,I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/jxcore-log( 3308): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 3308): 
I/wpa_supplicant(  984): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 3308): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
,D/BluetoothLeScanner( 3308): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): stop: Stopping P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3308): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3308): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 3308): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748454.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748454.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3308): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: OK
I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3308): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748454.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): createAdvertiseData: From: 1453370748454.3308 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3308): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748454.3308","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748454.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453370748454.3308","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748454.3308
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3308): start: OK
I/wpa_supplicant(  984): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
I/jxcore-log( 3308): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 3308): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3308): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): onServerStopped
,D/BluetoothLeScanner( 3308): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3308): Service requests cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3308): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 3308): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748478.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748478.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3308): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: OK
I/io.jxcore.node.ConnectionHelper( 3308): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: RUNNING
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748478.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Waiting for incoming connections...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): createAdvertiseData: From: 1453370748478.3308 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3308): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748478.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748478.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453370748478.3308","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3308): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748478.3308
I/jxcore-log( 3308): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 3308): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: OK
I/io.jxcore.node.ConnectionHelper( 3308): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local service added successfully
I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
D/BluetoothLeScanner( 3308): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: STARTED
I/wpa_supplicant(  984): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3308): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3308): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 3308): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748504.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748504.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3308): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: OK
,I/io.jxcore.node.ConnectionHelper( 3308): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748504.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): createAdvertiseData: From: 1453370748504.3308 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3308): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748504.3308","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748504.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453370748504.3308","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3308): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748504.3308
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: OK
I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local service added successfully
I/jxcore-log( 3308): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 3308): 
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3308): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): stop: Stopping Bluetooth...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: NOT_STARTED
I/wpa_supplicant(  984): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): onServerStopped
D/BluetoothLeScanner( 3308): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): stop: Stopping P2P device discovery...
D/org,.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3308): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3308): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 3308): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748523.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748523.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3308): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: OK
I/io.jxcore.node.ConnectionHelper( 3308): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748523.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): createAdvertiseData: From: 1453370748523.3308 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3308): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748523.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748523.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453370748523.3308","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748523.3308
I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: OK
I/io.jxcore.node.ConnectionHelper( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant(  984): P2P-FIND-STOPPED 
I/jxcore-log( 3308): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 3308): 
I/io.jxcore.node.ConnectionHelper( 3308): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): stop: Stopping Bluetooth...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothLeScanner( 3308): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): stop: Stopping P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3308): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3308): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 3308): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748544.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748544.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3308): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: OK
I/io.jxcore.node.ConnectionHelper( 3308): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748544.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): createAdvertiseData: From: 1453370748544.3308 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3308): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748544.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748544.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453370748544.3308","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): start: Starting P2P device discovery...
I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748544.3308
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3308): start: OK
I/wpa_supplicant(  984): P2P-FIND-STOPPED 
I/jxcore-log( 3308): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 3308): 
I/io.jxcore.node.ConnectionHelper( 3308): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): onServerStopped
I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
D/BluetoothLeScanner( 3308): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): stop: Stopping P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3308): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3308): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 3308): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748566.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748566.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3308): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: OK
I/io.jxcore.node.ConnectionHelper( 3308): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748566.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): createAdvertiseData: From: 1453370748566.3308 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3308): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748566.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748566.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453370748566.3308","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): start: Starting P2P device discovery...
I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748566.3308
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: OK
I/io.jxcore.node.ConnectionHelper( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/jxcore-log( 3308): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 3308): 
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/wpa_supplicant(  984): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 3308): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
D/BluetoothLeScanner( 3308): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local services cleared successfully
I/jxcore-log( 3308): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 3308): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3308): Service requests cleared successfully
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748586.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748586.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3308): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: OK
I/io.jxcore.node.ConnectionHelper( 3308): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748586.3308
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): createAdvertiseData: From: 1453370748586.3308 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3308): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748586.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453370748586.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453370748586.3308","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): start: Starting P2P device discovery...
I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370748586.3308
I/io.jxcore.node.ConnectionHelper( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery started successfully
I/jxcore-log( 3308): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 3308): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3308): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): stop: Stopping Bluetooth...
I/wpa_supplicant(  984): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
D/BluetoothLeScanner( 3308): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3308): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3308): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 3308): 
I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370751084.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370751084.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3308): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: OK
,I/io.jxcore.node.ConnectionHelper( 3308): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370751084.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): createAdvertiseData: From: 1453370751084.3308 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3308): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370751084.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453370751084.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453370751084.3308","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370751084.3308
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 3308): start: OK
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
,I/jxcore-log( 3308): ok 65 Should be able to call startBroadcasting without error
I/jxcore-log( 3308): 
I/jxcore-log( 3308): ok 66 Cannot call startBroadcasting twice
I/jxcore-log( 3308): 
I/io.jxcore.node.ConnectionHelper( 3308): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3308): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3308): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3308): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370751599.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370751599.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3308): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: OK
I/io.jxcore.node.ConnectionHelper( 3308): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370751599.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): createAdvertiseData: From: 1453370751599.3308 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3308): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370751599.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453370751599.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453370751599.3308","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): start: Starting P2P device discovery...
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370751599.3308
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3308): start: OK
I/jxcore-log( 3308): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 3308): 
I/io.jxcore.node.ConnectionHelper( 3308): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper( 3308): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
E/io.jxcore.node.ConnectionHelper( 3308): connect: Invalid Bluetooth address: foobar
I/jxcore-log( 3308): ok 69 Should not connect to a bad peer
I/jxcore-log( 3308): 
I/io.jxcore.node.ConnectionHelper( 3308): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3308): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3308): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3308): ok 70 Should be able to call stopBroadcasting without error
I/jxcore-log( 3308): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): onServerStopped
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370752080.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370752080.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3308): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): start: OK
I/io.jxcore.node.ConnectionHelper( 3308): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370752080.3308
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): createAdvertiseData: From: 1453370752080.3308 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3308): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3308): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3308): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3308): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453370752080.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453370752080.3308","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453370752080.3308","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): start: Starting P2P device discovery...
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453370752080.3308
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3308): start: OK
I/jxcore-log( 3308): ok 71 Should be able to call startBroadcasting without error
I/jxcore-log( 3308): 
D/io.jxcore.node.ConnectionHelper( 3308): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
E/io.jxcore.node.ConnectionHelper( 3308): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
D/io.jxcore.node.ConnectionHelper( 3308): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3308): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
I/jxcore-log( 3308): ok 72 Disconnect should fail to a non-existant peer 
I/jxcore-log( 3308): 
I/io.jxcore.node.ConnectionHelper( 3308): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3308): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3308): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3308): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3308): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3308): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3308): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3308): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3308): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3308): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3308): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3308): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3308): onServerStopped
,I/jxcore-log( 3308): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 74 host address should match
I/jxcore-log( 3308): 
I/jxcore-log( 3308): ok 75 port should match
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # #startUpdateAdvertisingAndListening should use different USN after every invocation
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 76 should not be equal
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # verify that Thali-specific messages are filtered correctly
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 77 irrelevant messages should be ignored
I/jxcore-log( 3308): 
I/jxcore-log( 3308): ok 78 relevant messages should not be ignored
I/jxcore-log( 3308): 
I/jxcore-log( 3308): ok 79 messages from this device should be ignored
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # #start should fail if called twice in a row
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 80 specific error should be received
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # #startUpdateAdvertisingAndListening should fail invalid router has been passed
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,E/jxcore-log( 3308): ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
E/jxcore-log( 3308): 
I/jxcore-log( 3308): ok 81 specific error should be received
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # #startUpdateAdvertisingAndListening should start hosting given router object
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 82 server should respond with code 200
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # setup
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): # #stop can be called multiple times in a row
I/jxcore-log( 3308): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): Start timer timeout, starting now...
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): start: Cannot start, because not initialized
,I/jxcore-log( 3308): # teardown
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 83 should be in stopped state
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): ok 84 should still be in stopped state
I/jxcore-log( 3308): 
,I/jxcore-log( 3308): Tests Complete
I/jxcore-log( 3308): 
,I/chromium( 3308): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3308): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3308): Total: 0	Passed: 0	Failed: 0
I/jxcore-log( 3308): 
I/jxcore-log( 3308): Toggling radios to false
I/jxcore-log( 3308): 
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  761): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@19652c mBinding = false
,D/BluetoothManagerService(  761): Message: 2
,D/BluetoothManagerService(  761): Sending off request.
,D/BluetoothAdapterState( 2184): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2184): Setting state to 13
I/BluetoothAdapterState( 2184): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 2184): onBluetoothDisable()
I/BluetoothAdapterState( 2184): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 2184): Scan Mode:20
,D/BluetoothAdapterState( 2184): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 2184): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2184): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2184): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2184): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2184): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2184): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2184): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2184): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 2184): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 2184): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2184): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,W/bt-l2cap( 2184): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2184): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  761): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 2184): onReceive
D/BluetoothMapService( 2184): STATE_TURNING_OFF
V/BluetoothMapService( 2184): Handler(): got msg=4
D/BluetoothMapService( 2184): MAP Service closeService in
D/BluetoothMapMasInstance( 2184): MAP Service shutdown
V/BluetoothMapService( 2184): MAP Service closeService out
,I/BtOppRfcommListener( 2184): stopping Accept Thread
,I/BtOppRfcommListener( 2184): BluetoothSocket listen thread finished
,D/WifiService(  761): setWifiEnabled: false pid=3308, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 2769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 2769): finishStartingService: stopping service
,I/jxcore-log( 3308): Radios toggled
I/jxcore-log( 3308): 
I/jxcore-log( 3308): ****TEST TOOK:  ms ****
I/jxcore-log( 3308): 
I/jxcore-log( 3308): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3308): 
E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): Start timer timeout, starting now...
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): start: Cannot start, because not initialized
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): Start timer timeout, starting now...
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3308): start: Cannot start, because not initialized
E/native  (  761): do suspend true
,D/AuthorizationBluetoothService( 1608): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothPbap( 2769): Proxy object disconnected
D/PbapServerProfile( 2769): Bluetooth service disconnected
D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1608): Read error: ssl=0xb3c6ce00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1608): SSL shutdown failed: ssl=0xb3c6ce00: I/O error during system call, Broken pipe
,D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/bt_userial( 2184): RX termination
W/bt_userial( 2184): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 2184): Leaving userial_read_thread()
,W/bt-btif ( 2184): ag scb idx 1 not allocated
E/bt-btif ( 2184): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2184): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2184): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2184): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2184): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2184): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 2184): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 2184): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2184): hw_epilog_process
I/bt_userial_vendor( 2184): device fd = 53 close
,I/GKI_LINUX( 2184): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2184): GKI_exit_task 0 done
I/GKI_LINUX( 2184): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 2184): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
I/jxcore-log( 3308): Toggling radios to false
I/jxcore-log( 3308): 
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  761): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@19652c mBinding = false
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/BluetoothManagerService(  761): Message: 2
D/BluetoothManagerService(  761): Sending off request.
D/HeadsetService( 2184): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2184): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a118f2d
,D/BluetoothHeadset( 1230): Proxy object disconnected
D/BluetoothHeadset( 1230): Proxy object disconnected
D/HeadsetStateMachine( 2184): Exit Disconnected: -1
,D/BluetoothHeadset( 1279): Proxy object disconnected
,E/WifiStateMachine(  761): scanCount==0 - aborting
D/BluetoothHeadset(  761): Proxy object disconnected
,D/WifiScanningService(  761): SCAN_AVAILABLE : 1
,D/WifiScanningService(  761): StartedState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  761): DefaultState
,D/RttService(  761): SCAN_AVAILABLE : 1
,D/RttService(  761): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/A2dpService( 2184): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2184): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a118f2d
,D/BluetoothHeadset( 2769): Proxy object disconnected
D/HeadsetProfile( 2769): Bluetooth service disconnected
D/A2dpStateMachine( 2184): Exit Disconnected: -1
D/BluetoothA2dp(  761): Proxy object disconnected
D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
E/native  (  761): do suspend true
,D/HidService( 2184): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2184): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a118f2d
,D/HeadsetStateMachine( 2184): Unbinding service...
,D/BluetoothA2dp( 2769): Proxy object disconnected
D/A2dpProfile( 2769): Bluetooth service disconnected
D/BluetoothInputDevice( 2769): Proxy object disconnected
,W/BluetoothHeadsetServiceJni( 2184): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2184): Cleaning up Bluetooth Handsfree callback object
D/HidProfile( 2769): Bluetooth service disconnected
,D/BluetoothAdapterState( 2184): Stopping profile services that were post enabled
D/BluetoothAdapterState( 2184): CURRENT_STATE=PENDING, MESSAGE = USER_TURN_ON, isTurningOn=false, isTurningOff=true
,I/BluetoothAdapterState( 2184): CURRENT_STATE=PENDING: Alreadying turning off bluetooth... Ignoring USER_TURN_OFF...
,D/WifiService(  761): setWifiEnabled: false pid=3308, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,D/HealthService( 2184): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2184): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a118f2d
I/jxcore-log( 3308): Radios toggled
I/jxcore-log( 3308): 
,I/GKI_LINUX( 2184): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2184): GKI_exit_task 2 done
I/GKI_LINUX( 2184): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 2184): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2184): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2184): Cleaning up Bluetooth GID callback object
,D/PanService( 2184): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2184): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a118f2d
,D/BluetoothPan( 2769): BluetoothPAN Proxy object disconnected
D/PanProfile( 2769): Bluetooth service disconnected
,D/BtGatt.DebugUtils( 2184): handleDebugAction() action=null
,D/BtGatt.GattService( 2184): Received stop request...Stopping profile...
D/BtGatt.GattService( 2184): stop()
D/BtGatt.AdvertiseManager( 2184): advertise clients cleared
,D/CommandListener(  179): Clearing all IP addresses on wlan0
D/BluetoothAdapterService( 2184): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a118f2d
,D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
D/BluetoothMapService( 2184): Received stop request...Stopping profile...
D/BluetoothMapService( 2184): stop()
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/BluetoothMapEmailAppObserver( 2184): deinitObservers()
D/BluetoothMapEmailAppObserver( 2184): removeReceiver()
D/BluetoothAdapterService( 2184): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a118f2d
D/BluetoothMap( 2769): Proxy object disconnected
D/MapProfile( 2769): Bluetooth service disconnected
W/BluetoothHealthServiceJni( 2184): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2184): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 2184): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2184): Cleaning up Bluetooth PAN callback object
V/BluetoothMapService( 2184): Handler(): got msg=4
D/BluetoothMapService( 2184): MAP Service closeService in
V/BluetoothMapService( 2184): MAP Service closeService out
D/BluetoothMapService( 2184): cleanup()
D/BluetoothMapService( 2184): MAP Service closeService in
V/BluetoothMapService( 2184): MAP Service closeService out
,D/BluetoothAdapterState( 2184): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2184): Setting state to 10
I/BluetoothAdapterState( 2184): Bluetooth adapter state changed: 13-> 10
I/BluetoothAdapterState( 2184): Entering OffState
D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1279): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  761): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/BluetoothHeadset(  761): onBluetoothStateChange: up=false
,D/ConnectivityManager.CallbackHandler( 1654): CM callback handler got msg 524292
,D/BluetoothMap( 2769): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 2769): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1230): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1230): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  761): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1279): onBluetoothStateChange: up=false
,D/BluetoothPbap( 2769): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 2769): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 2769): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  761): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  761): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothManagerService(  761): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@19652c mBinding = false
,D/BluetoothManagerService(  761): Sending unbind request.
D/BluetoothManagerService(  761): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  900): 410539302: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  900): 410539302: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter(  900): 410539302: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1608): 34830999: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1608): 34830999: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 2184): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2184): GKI_exit_task 1 done
I/GKI_LINUX( 2184): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2184): cleanupNative: return from cleanup
,I/art     ( 2184): System.exit called, status: 0
I/AndroidRuntime( 2184): VM exiting with result code 0, cleanup skipped.
,I/ActivityManager(  761): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3676 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/AndroidRuntime( 3661): 
D/AndroidRuntime( 3661): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3661): CheckJNI is OFF
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant(  984): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,I/ActivityManager(  761): Process com.android.bluetooth (pid 2184) has died
,D/AndroidRuntime( 3661): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
,I/ActivityManager(  761): Killing 3308:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  761): WIN DEATH: Window{23a22abc u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  761): Client connection lost with reason: 4
,W/PackageSettings(  761): Skipping PackageSetting{2e952098 com.example.hello/10278} due to missing metadata
,D/Tethering(  761): InitialState.processMessage what=4
I/wpa_supplicant(  984): wlan0: CTRL-EVENT-TERMINATING 
,E/libprocessgroup(  761): failed to kill 1 processes for processgroup 3308
,I/ActivityManager(  761):   Force finishing activity ActivityRecord{3a99f448 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  761): Spurious death for ProcessRecord{e8a64ad 3308:com.test.thalitest/u0a270}, curProc for 3308: null
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  761):   Force finishing activity ActivityRecord{3a99f448 u0 com.test.thalitest/.MainActivity t216 f}
W/ActivityManager(  761): Duplicate finish request for ActivityRecord{3a99f448 u0 com.test.thalitest/.MainActivity t216 f}
,D/Tethering(  761): sendTetherStateChangedBroadcast 0, 0, 0
,I/art     ( 1320): Explicit concurrent mark sweep GC freed 3940(293KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 1.540ms total 48.059ms
,I/Keyboard.Facilitator( 1096): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1608): Ignoring removeGeofence because network location is disabled.
,W/Settings( 1982): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1096): run()
,I/art     ( 1379): Explicit concurrent mark sweep GC freed 617(37KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 351us total 85.327ms
,I/Decoder ( 1096): createOrResetDecoder
,W/Settings( 1608): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Adreno-EGL(  947): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  947): Initialized EGL, version 1.4
,D/OpenGLRenderer(  947): Enabling debug mode 0
,I/art     ( 1654): Explicit concurrent mark sweep GC freed 10913(525KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 592us total 129.766ms
,I/art     (  761): Explicit concurrent mark sweep GC freed 39299(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.585ms total 105.605ms
,I/art     (  761): WaitForGcToComplete blocked for 94.459ms for cause Explicit
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1096): run()
,W/InputMethodManagerService(  761): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@3da753 (uid=10034 pid=947)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1096): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1096): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1096): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1096): run()
I/StatsUtilsManager( 1096): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1096): shouldRecordStats() = Too Soon
,D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
,I/PhenotypeConfigurator( 1608): Scheduling Phenotype for one-off execution 2474 seconds from now (1453370754559)
,D/TaskPersister(  761): removeObsoleteFile: deleting file=216_task.xml
,D/GetConfigurationSnapshotOperation( 1608): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/art     (  761): Explicit concurrent mark sweep GC freed 7925(427KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.467ms total 139.605ms
,I/PhenotypeFlagCommitter( 1608): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1608): Using platform SSLCertificateSocketFactory
,I/Launcher( 1320): Deferring update until onResume
,W/ContextImpl( 2769): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/ResourcesManager( 1320): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/AndroidRuntime( 3661): Shutting down VM
,I/ActivityManager(  761): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=3733 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
W/ResourcesManager( 1320): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/DockEventReceiver( 2769): finishStartingService: stopping service
,I/Launcher( 1320): Deferring update until onResume
,I/ActivityManager(  761): Killing 2794:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2794/cgroup.procs: No such file or directory
,W/ResourcesManager( 3733): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 3733): Adding HeadsetService
,D/AdapterServiceConfig( 3733): Adding A2dpService
D/AdapterServiceConfig( 3733): Adding HidService
D/AdapterServiceConfig( 3733): Adding HealthService
D/AdapterServiceConfig( 3733): Adding PanService
D/AdapterServiceConfig( 3733): Adding GattService
D/AdapterServiceConfig( 3733): Adding BluetoothMapService
,D/BluetoothAdapter( 2769): 317084550: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  761): Killing 2633:com.google.android.gm/u0a70 (adj 15): empty #17
,D/Uploader( 1608): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/AuthorizationBluetoothService( 1608): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2633/cgroup.procs: No such file or directory
,E/SQLiteLog( 1366): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/VoicemailCleanupService( 1366): Cleaning up data for package: com.test.thalitest
,D/Uploader( 1608): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,--------- beginning of crash
E/AndroidRuntime( 1366): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 1366): Process: android.process.acore, PID: 1366
E/AndroidRuntime( 1366): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1366): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1366): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1366): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1366): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1366): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1366): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1366): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:381)
E/AndroidRuntime( 1366): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:350)
E/AndroidRuntime( 1366): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1706)
E/AndroidRuntime( 1366): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 1366): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1366): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1366): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/UpdateIcingCorporaServi( 1379): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1320): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a118f2d new=com.google.android.velvet.VelvetApplication@a118f2d
,E/DropBoxManagerService(  761): Can't write: system_app_crash
E/DropBoxManagerService(  761): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  761): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  761): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  761): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  761): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  761): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  761): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  761): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  761): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  761): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  761): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  761): 	... 5 more
,I/Process ( 1366): Sending signal. PID: 1366 SIG: 9
,E/SQLiteLog( 1320): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,E/SQLiteLog( 1379): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error

```
