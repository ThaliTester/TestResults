#### Test 54970261e0c50c1_thali02_LGE-Nexus 5 Logs


```
--------- beginning of system
W/ResourcesManager( 3122): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3122): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
--------- beginning of main
D/Finsky  ( 2634): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  760): Killing 2064:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 3122): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3122): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3122): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  760): failed to open /acct/uid_10038/pid_2064/cgroup.procs: No such file or directory
V/GLSActivity( 1598): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1634): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1634): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1634): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1634): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/CAR.SERVICE( 3008): mConnectedToCar = false, abort
E/ActivityThread( 3008): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@4a9b280 that was originally bound here
E/ActivityThread( 3008): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@4a9b280 that was originally bound here
E/ActivityThread( 3008): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3008): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3008): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3008): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3008): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3008): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3008): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3008): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3008): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3008): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3008): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3008): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3008): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3008): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3008): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3008): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3008): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3008): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3008): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3008): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3008): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3008): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3008): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/ActivityThread( 3008): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@f5d5f7b that was originally bound here
E/ActivityThread( 3008): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@f5d5f7b that was originally bound here
E/ActivityThread( 3008): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3008): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3008): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3008): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3008): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3008): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3008): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3008): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3008): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3008): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3008): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3008): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3008): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3008): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3008): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3008): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3008): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3008): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3008): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3008): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3008): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3008): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  760): Unbind failed: could not find connection for android.os.BinderProxy@14976a46
I/ActivityManager(  760): Killing 2599:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
D/AndroidRuntime( 3179): 
D/AndroidRuntime( 3179): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3179): CheckJNI is OFF
W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_2599/cgroup.procs: No such file or directory
D/AndroidRuntime( 3179): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3200 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3179): Shutting down VM
V/ActivityManager(  760): Display changed displayId=0
I/WebViewFactory( 3200): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3200): Time to load native libraries: 1 ms (timestamps 8950-8951)
I/LibraryLoader( 3200): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3200): Binding Chromium to main looper Looper (main, tid 1) {2043ffbb}
I/LibraryLoader( 3200): Expected native library version number "",actual native library version number ""
I/chromium( 3200): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3200): Initializing chromium process, singleProcess=true
W/art     ( 3200): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3200): ApplicationContext is null in ApplicationStatus
W/chromium( 3200): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3200): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3200): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3200): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32659a1b:true
,W/art     ( 3200): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3200): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3200): CordovaWebView is running on device made by: LGE
,W/art     ( 3200): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3200): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3200): Render dirty regions requested: true
,D/Atlas   ( 3200): Validating map...
,W/chromium( 3200): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3200): Initialized EGL, version 1.4
D/OpenGLRenderer( 3200): Enabling debug mode 0
,I/Keyboard.Facilitator( 1108): onFinishInput()
,W/IInputConnectionWrapper( 3200): showStatusIcon on inactive InputConnection
I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +412ms (total +57s127ms)
,W/BindingManager( 3200): Cannot call determinedVisibility() - never saw a connection for the pid: 3200
,D/JsMessageQueue( 3200): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3200): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258391936
D/JX-Cordova( 3200): jxcore cordova android initializing
,W/jxcore-log( 3200): Initializing JXcore engine
W/jxcore-log( 3200): JXcore engine is ready
W/jxcore-log( 3200): Starting JXcore engine
,W/.test.thalitest( 3200): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8164]" dev="sockfs" ino=8164 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3200): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3200): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8463]" dev="sockfs" ino=8463 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3200): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20663]" dev="sockfs" ino=20663 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3200): Platform android
W/jxcore-log( 3200): 
,W/jxcore-log( 3200): Process ARCH arm
W/jxcore-log( 3200): 
,I/jxcore-log( 3200): JXcore Cordova bridge is ready!
I/jxcore-log( 3200): 
,W/jxcore-log( 3200): JXcore engine is started
I/Choreographer( 3200): Skipped 106 frames!  The application may be doing too much work on its main thread.
I/chromium( 3200): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3200): Toggling radios to true
I/jxcore-log( 3200): 
,D/BluetoothAdapter( 3200): enable(): BT is already enabled..!
,D/WifiService(  760): New client listening to asynchronous messages
,D/WifiService(  760): setWifiEnabled: true pid=3200, uid=10270
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3200): Radios toggled
I/jxcore-log( 3200): 
,I/wpa_supplicant(  989): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
E/WifiStateMachine(  760): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  760): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1598): Read error: ssl=0xaf28be00: I/O error during system call, Connection timed out
V/NativeCrypto( 1598): SSL shutdown failed: ssl=0xaf28be00: I/O error during system call, Broken pipe
,D/ConnectivityService(  760): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiStateMachine(  760): Start Disconnecting Watchdog 1
I/wpa_supplicant(  989): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  760): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  760): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  760): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Disconnected - quitting
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  760): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1287): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  760): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/ConnectivityManager.CallbackHandler( 1634): CM callback handler got msg 524292
,D/WifiNetworkAgent(  760): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  989): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  989): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  989): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  989): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  760): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  179): Setting iface cfg
E/WifiStateMachine(  760): Start Dhcp Watchdog 2
,W/NetworkUtils( 1369): OkHttp exception
W/EventLoggerService( 1369): Unable to send logs Error code: 262146
,V/GLSActivity( 1598): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1598): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/native  (  760): do suspend false
,E/WifiStateMachine(  760): scanCount==0 - aborting
,I/dhcpcd  ( 3299): version 5.5.6 starting
E/dhcpcd  ( 3299): get_duid: Read-only file system
,I/dhcpcd  ( 3299): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3299): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3299): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
D/Tethering(  760): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2748): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1634): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1634): onCreate
,D/SystemUpdateService( 1634): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1634): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1634): num queued entries: 0
,I/iu.UploadsManager( 1634): num updated entries: 0
I/iu.SyncManager( 1634): NEXT; no task
,I/SystemUpdateService( 1634): active receiver: enabled
,E/GpsLocationProvider(  760): No APN found to select.
,I/SystemUpdateService( 1634): showing system update notification
,I/Babel   ( 1883): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  760): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3342 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/native  (  760): do suspend true
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  760): Adding iface wlan0 to network 101
E/WifiStateMachine(  760): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  760): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  760): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  760): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  760): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  760): Setting Dns servers for network 101 to [/192.168.1.1]
E/GpsLocationProvider(  760): No APN found to select.
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/CSLegacyTypeTracker(  760): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  760): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1634): CM callback handler got msg 524290
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1634): retry (wakeup: false) in 3599884 ms
,D/SystemUpdateService( 1634): onDestroy
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 17:33:56 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452274436661], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452274436649]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Validated
,D/ConnectivityService(  760): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1634): CM callback handler got msg 524290
I/GAv4    ( 3342): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3342):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3342):   adb logcat -s GAv4
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1287): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/GAv4    ( 3342): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3342): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3342): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3342): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3342): Time to load native libraries: 2 ms (timestamps 4917-4919)
I/LibraryLoader( 3342): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3342): Binding Chromium to main looper Looper (main, tid 1) {26ce1f75}
I/LibraryLoader( 3342): Expected native library version number "",actual native library version number ""
I/chromium( 3342): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3342): Initializing chromium process, singleProcess=true
,W/art     ( 3342): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3342): ApplicationContext is null in ApplicationStatus
,W/chromium( 3342): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3342): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3342): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3342): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3342): Requires BLUETOOTH permission
,I/NSApplication( 3342): Starting up...
,I/ActivityManager(  760): Killing 2554:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_2554/cgroup.procs: No such file or directory
,V/MusicLeanback( 2748): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1634): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1634): onCreate
D/SystemUpdateService( 1634): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/iu.Environment( 1634): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1634): num queued entries: 0
I/iu.UploadsManager( 1634): num updated entries: 0
I/iu.SyncManager( 1634): NEXT; no task
,I/SystemUpdateService( 1634): active receiver: enabled
I/SystemUpdateService( 1634): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1634): retry (wakeup: false) in 3599982 ms
,D/SystemUpdateService( 1634): onDestroy
,I/Babel   ( 1883): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  760): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3200): Test app app.js loaded
I/jxcore-log( 3200): 
,I/Choreographer( 3200): Skipped 378 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3200): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2748): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2748): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1634): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
E/GpsLocationProvider(  760): No APN found to select.
,D/SystemUpdateService( 1634): onCreate
,D/SystemUpdateService( 1634): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1634): active receiver: enabled
,I/SystemUpdateService( 1634): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1634): retry (wakeup: false) in 3599975 ms
,D/SystemUpdateService( 1634): onDestroy
,I/art     (  760): Explicit concurrent mark sweep GC freed 46191(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.301ms total 74.798ms
,D/Finsky  ( 2634): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2634): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1598): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1598): Vacuum at: now=1452274455586 tag=VacuumService
,I/PhenotypeConfigurator( 1598): Scheduling Phenotype for one-off execution 8662 seconds from now (1452274455908)
,D/GetConfigurationSnapshotOperation( 1598): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1598): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1598): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1598): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1598): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1108): run()
I/Keyboard.Facilitator( 1108): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1598): disconnect managed GoogleApiClient
,I/jxcore-log( 3200): ****TEST TOOK:  ms ****
I/jxcore-log( 3200): 
I/jxcore-log( 3200): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3200): 
,D/AndroidRuntime( 3527): 
D/AndroidRuntime( 3527): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3527): CheckJNI is OFF
,D/AndroidRuntime( 3527): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  760): Killing 3200:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  760): WIN DEATH: Window{225d400b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  760): Client connection lost with reason: 4
,W/PackageSettings(  760): Skipping PackageSetting{be7a49f com.example.hello/10278} due to missing metadata
,I/ActivityManager(  760):   Force finishing activity ActivityRecord{1efdc407 u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  760): Spurious death for ProcessRecord{7701a1 3200:com.test.thalitest/u0a270}, curProc for 3200: null
I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  760):   Force finishing activity ActivityRecord{1efdc407 u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  760): Duplicate finish request for ActivityRecord{1efdc407 u0 com.test.thalitest/.MainActivity t214 f}
,I/art     ( 1332): Explicit concurrent mark sweep GC freed 4018(297KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 226us total 15.993ms
,W/GeofencerStateMachine( 1598): Ignoring removeGeofence because network location is disabled.
I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1108): resetDictionaries() : en_US
,D/VoicemailCleanupService( 1392): Cleaning up data for package: com.test.thalitest
,I/Keyboard.Facilitator.DecoderInitializer( 1108): run()
,I/art     (  760): Explicit concurrent mark sweep GC freed 23126(1301KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.022ms total 91.111ms
,I/art     ( 1369): Explicit concurrent mark sweep GC freed 1975(129KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 367us total 111.964ms
,I/Decoder ( 1108): createOrResetDecoder
,I/art     (  760): WaitForGcToComplete blocked for 66.630ms for cause Explicit
I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  944): Initialized EGL, version 1.4
,D/OpenGLRenderer(  944): Enabling debug mode 0
,I/UpdateIcingCorporaServi( 1369): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/art     ( 1634): Explicit concurrent mark sweep GC freed 10674(515KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/30MB, paused 519us total 131.722ms
,W/Launcher( 1332): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3a810cd8 new=com.google.android.velvet.VelvetApplication@3a810cd8
,I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3569 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,W/InputMethodManagerService(  760): Got RemoteException sending setActive(false) notification to pid 3200 uid 10270
,I/Keyboard.Facilitator( 1108): onFinishInput()
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1108): run()
,D/TaskPersister(  760): removeObsoleteFile: deleting file=214_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1108): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1108): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1108): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1108): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1108): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1108): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1108): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1108): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1108): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1108): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1108): run()
I/StatsUtilsManager( 1108): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1108): shouldRecordStats() = Too Soon
,I/art     (  760): Explicit concurrent mark sweep GC freed 5663(303KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.327ms total 143.175ms
W/ContextImpl( 3569): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1634): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1634): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1634): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1634): Module APK com.google.android.play.games already loaded
W/IInputConnectionWrapper( 1332): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1108): onFinishInput()
E/DataBuffer( 1598): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3660119c)
I/art     ( 1598): Explicit concurrent mark sweep GC freed 95975(5MB) AllocSpace objects, 22(352KB) LOS objects, 40% free, 23MB/38MB, paused 844us total 51.049ms
,E/DataBuffer( 1598): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@893277a)
,E/DataBuffer( 1598): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3f0b2b2b)
E/DataBuffer( 1598): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@d2aab88)
,I/ActivityManager(  760): Killing 2722:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,E/DataBuffer( 1598): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@e9ea921)
,E/DataBuffer( 1598): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@19c4146)
E/DataBuffer( 1598): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@d8f4f07)
E/DataBuffer( 1598): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1682f834)
E/DataBuffer( 1598): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@299bb65d)
E/DataBuffer( 1598): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@11cb2bd2)
E/DataBuffer( 1598): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3147d4a3)
,D/AndroidRuntime( 3527): Shutting down VM
,W/libprocessgroup(  760): failed to open /acct/uid_10003/pid_2722/cgroup.procs: No such file or directory
,I/Launcher( 1332): Deferring update until onResume
,D/ChimeraCfgMgr( 1634): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1634): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1634): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1598): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1598): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/ResourcesManager( 1332): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  760): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/UpdateIcingCorporaServi( 1369): UpdateCorporaTask done [took 311 ms] updated apps [took 311 ms] 
I/ActivityManager(  760): Resuming delayed broadcast
,W/ResourcesManager( 1332): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1634): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1634): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1634): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1634): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1634): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1634): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1634): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/Launcher( 1332): Deferring update until onResume
D/gH_CompatibleDatabase( 1634): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1634): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1634): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1634): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1634): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1634): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  760): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3600 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,W/BaseAppContext( 1634): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1634): App measurement is starting up, version: 8489
I/GMPM-SVC( 1634): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1634): Using Auth Proxy for data requests.
,I/Icing   ( 1634): doRemovePackageData com.test.thalitest
,I/ActivityManager(  760): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3626 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 2698:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  760): Client connection lost with reason: 4
,W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_2698/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 2576:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2576/cgroup.procs: No such file or directory
,D/ExternalStorage( 3626): After updating volumes, found 1 active roots

```
