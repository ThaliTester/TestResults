#### Test 54970261ac9928f_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
W/AnalyticsTrackerProxyImpl( 3067): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,D/Finsky  ( 2597): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  758): Killing 2404:com.google.android.youtube/u0a80 (adj 15): empty #17
W/ResourcesManager( 3067): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3067): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  758): failed to open /acct/uid_10080/pid_2404/cgroup.procs: No such file or directory
V/JNIHelp ( 3067): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3067): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3067): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 3117): 
D/AndroidRuntime( 3117): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3117): CheckJNI is OFF
D/AndroidRuntime( 3117): Calling main entry com.android.commands.am.Am
I/ActivityManager(  758): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  758): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3148 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3117): Shutting down VM
I/Icing   ( 1637): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
V/ActivityManager(  758): Display changed displayId=0
I/Icing   ( 1637): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1637): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/WebViewFactory( 3148): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/Icing   ( 1637): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/LibraryLoader( 3148): Time to load native libraries: 1 ms (timestamps 6901-6902)
I/LibraryLoader( 3148): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3148): Binding Chromium to main looper Looper (main, tid 1) {1c83bd1b}
I/LibraryLoader( 3148): Expected native library version number "",actual native library version number ""
I/chromium( 3148): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3148): Initializing chromium process, singleProcess=true
W/art     ( 3148): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3148): ApplicationContext is null in ApplicationStatus
W/chromium( 3148): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3148): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3148): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3148): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@793c74d:true
W/art     ( 3148): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3148): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3148): CordovaWebView is running on device made by: LGE
W/art     ( 3148): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3148): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3148): Render dirty regions requested: true
D/Atlas   ( 3148): Validating map...
W/chromium( 3148): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3148): Initialized EGL, version 1.4
D/OpenGLRenderer( 3148): Enabling debug mode 0
I/Keyboard.Facilitator( 1087): onFinishInput()
W/IInputConnectionWrapper( 3148): showStatusIcon on inactive InputConnection
W/BindingManager( 3148): Cannot call determinedVisibility() - never saw a connection for the pid: 3148
I/ActivityManager(  758): Displayed com.test.thalitest/.MainActivity: +499ms (total +55s391ms)
D/JsMessageQueue( 3148): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3148): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257343360
D/JX-Cordova( 3148): jxcore cordova android initializing
D/CAR.SERVICE( 2953): mConnectedToCar = false, abort
E/ActivityThread( 2953): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@17aa9860 that was originally bound here
E/ActivityThread( 2953): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@17aa9860 that was originally bound here
E/ActivityThread( 2953): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2953): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2953): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2953): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2953): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2953): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2953): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2953): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2953): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2953): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 2953): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 2953): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 2953): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 2953): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 2953): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 2953): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 2953): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2953): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2953): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2953): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2953): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2953): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2953): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/ActivityThread( 2953): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@30497cdb that was originally bound here
E/ActivityThread( 2953): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@30497cdb that was originally bound here
E/ActivityThread( 2953): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2953): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2953): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2953): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2953): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2953): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 2953): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 2953): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 2953): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 2953): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 2953): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 2953): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 2953): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 2953): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 2953): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 2953): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2953): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2953): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 2953): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 2953): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 2953): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 2953): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  758): Unbind failed: could not find connection for android.os.BinderProxy@955d4fe
I/ActivityManager(  758): Killing 2061:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/libprocessgroup(  758): failed to open /acct/uid_10038/pid_2061/cgroup.procs: No such file or directory
,W/jxcore-log( 3148): Initializing JXcore engine
W/jxcore-log( 3148): JXcore engine is ready
,W/jxcore-log( 3148): Starting JXcore engine
,W/.test.thalitest( 3148): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9419]" dev="sockfs" ino=9419 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3148): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3148): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8640]" dev="sockfs" ino=8640 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3148): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18417]" dev="sockfs" ino=18417 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3148): Platform android
W/jxcore-log( 3148): 
W/jxcore-log( 3148): Process ARCH arm
W/jxcore-log( 3148): 
,I/jxcore-log( 3148): JXcore Cordova bridge is ready!
I/jxcore-log( 3148): 
,W/jxcore-log( 3148): JXcore engine is started
,I/Choreographer( 3148): Skipped 115 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3148): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3148): Toggling radios to true
I/jxcore-log( 3148): 
,D/BluetoothAdapter( 3148): enable(): BT is already enabled..!
,D/WifiService(  758): New client listening to asynchronous messages
,D/WifiService(  758): setWifiEnabled: true pid=3148, uid=10270
E/WifiService(  758): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3148): Radios toggled
I/jxcore-log( 3148): 
,I/wpa_supplicant(  982): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  758): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  758): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1607): Read error: ssl=0x9d342000: I/O error during system call, Connection timed out
V/NativeCrypto( 1607): SSL shutdown failed: ssl=0x9d342000: I/O error during system call, Broken pipe
D/ConnectivityService(  758): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  758): Start Disconnecting Watchdog 1
I/wpa_supplicant(  982): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  758): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  758): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  758): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  758): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1637): CM callback handler got msg 524292
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Disconnected - quitting
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524292
,D/ConnectivityService(  758): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1250): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  758): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiNetworkAgent(  758): NetworkAgent: NetworkAgent channel lost
,I/ActivityManager(  758): Killing 2500:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10045/pid_2500/cgroup.procs: No such file or directory
,I/wpa_supplicant(  982): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  982): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  982): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  982): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  758): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  178): Setting iface cfg
,E/WifiStateMachine(  758): Start Dhcp Watchdog 2
,E/native  (  758): do suspend false
,E/WifiStateMachine(  758): scanCount==0 - aborting
,I/dhcpcd  ( 3246): version 5.5.6 starting
,E/dhcpcd  ( 3246): get_duid: Read-only file system
,I/dhcpcd  ( 3246): wlan0: rebinding lease of 192.168.1.114
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dhcpcd  ( 3246): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3246): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  758): MasterInitialState.processMessage what=3
D/Tethering(  758): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2695): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/NetworkUtils( 1404): OkHttp exception
W/EventLoggerService( 1404): Unable to send logs Error code: 262146
,E/GpsLocationProvider(  758): No APN found to select.
,I/SystemUpdateService( 1637): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1637): onCreate
,E/GpsLocationProvider(  758): No APN found to select.
,D/SystemUpdateService( 1637): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1637): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1637): num queued entries: 0
I/iu.UploadsManager( 1637): num updated entries: 0
I/iu.SyncManager( 1637): NEXT; no task
,I/SystemUpdateService( 1637): active receiver: enabled
,I/SystemUpdateService( 1637): showing system update notification
,I/Babel   ( 1893): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  758): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3292 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/native  (  758): do suspend true
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  758): Adding iface wlan0 to network 101
E/WifiStateMachine(  758): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/ValidateNoPeople(  758): skipping global notification
,E/ConnectivityService(  758): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  758): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  758): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
V/SystemUpdateService( 1637): retry (wakeup: false) in 3599900 ms
,D/ConnectivityService(  758): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  758): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  758): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  758): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  758): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  758): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  758): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  758): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1637): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
,D/SystemUpdateService( 1637): onDestroy
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 16:12:17 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452269537793], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452269537781]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Validated
,D/ConnectivityService(  758): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  758): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1250): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1637): CM callback handler got msg 524290
,I/GAv4    ( 3292): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3292):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3292):   adb logcat -s GAv4
,W/GAv4    ( 3292): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3292): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3292): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3292): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3292): Time to load native libraries: 2 ms (timestamps 3186-3188)
I/LibraryLoader( 3292): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3292): Binding Chromium to main looper Looper (main, tid 1) {208be5d5}
I/LibraryLoader( 3292): Expected native library version number "",actual native library version number ""
I/chromium( 3292): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3292): Initializing chromium process, singleProcess=true
W/art     ( 3292): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3292): ApplicationContext is null in ApplicationStatus
,W/chromium( 3292): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3292): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3292): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3292): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3292): Starting up...
,I/ActivityManager(  758): Killing 2672:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/AudioManagerAndroid( 3292): Requires BLUETOOTH permission
,W/libprocessgroup(  758): failed to open /acct/uid_10003/pid_2672/cgroup.procs: No such file or directory
,V/MusicLeanback( 2695): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1637): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1637): onCreate
,D/SystemUpdateService( 1637): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1637): active receiver: enabled
,I/SystemUpdateService( 1637): showing system update notification
,I/iu.Environment( 1637): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1637): num queued entries: 0
I/iu.UploadsManager( 1637): num updated entries: 0
I/iu.SyncManager( 1637): NEXT; no task
,I/ValidateNoPeople(  758): skipping global notification
,V/SystemUpdateService( 1637): retry (wakeup: false) in 3599957 ms
,D/SystemUpdateService( 1637): onDestroy
,I/Babel   ( 1893): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  758): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  758): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2695): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2695): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/jxcore-log( 3148): Test app app.js loaded
I/jxcore-log( 3148): 
,E/GpsLocationProvider(  758): No APN found to select.
,I/chromium( 3148): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SystemUpdateService( 1637): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1637): onCreate
,D/SystemUpdateService( 1637): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1637): active receiver: enabled
,I/SystemUpdateService( 1637): showing system update notification
,I/ValidateNoPeople(  758): skipping global notification
,V/SystemUpdateService( 1637): retry (wakeup: false) in 3599983 ms
,D/SystemUpdateService( 1637): onDestroy
,I/art     (  758): Explicit concurrent mark sweep GC freed 44569(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.351ms total 91.669ms
,D/Finsky  ( 2597): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2597): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1607): Vacuum at: now=1452269557955 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1087): run()
I/Keyboard.Facilitator( 1087): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1607): disconnect managed GoogleApiClient
,I/ActivityManager(  758): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3448 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3448): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3448):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3448):   adb logcat -s GAv4
,W/GAv4    ( 3448): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3448): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3448): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  758): Killing 2647:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  758): Client connection lost with reason: 4
,W/libprocessgroup(  758): failed to open /acct/uid_1000/pid_2647/cgroup.procs: No such file or directory
,D/HeadsetStateMachine( 2086): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 2086): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 2086): Disconnected process message: 11, size: 0
,I/jxcore-log( 3148): TAP version 13
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # multiplex can send data
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 1 String should be length:200
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # basic
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 2 sane
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # another
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 3 sane
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 4 should be equal
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 5 null
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 6 (unnamed assert)
I/jxcore-log( 3148): 
I/jxcore-log( 3148): ok 7 should be equal
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 8 should not throw
I/jxcore-log( 3148): 
I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 9 (unnamed assert)
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 10 (unnamed assert)
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 11 should not throw
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 12 should be equal
I/jxcore-log( 3148): 
I/jxcore-log( 3148): ok 13 should be equal
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 14 should be equal
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # failed to get mobile documents path
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 15 should be equal
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 16 should be equal
I/jxcore-log( 3148): 
I/jxcore-log( 3148): ok 17 should be equal
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 18 should be equal
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # #init should register the networkChanged event
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 19 should be equal
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # #startBroadcasting should throw on null device name
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 20 should throw
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 21 should throw
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 22 should throw
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 23 should throw
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # #startBroadcasting should throw on negative port
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 24 should throw
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # #startBroadcasting should throw on too large port
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 25 should throw
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 26 should be equal
I/jxcore-log( 3148): 
I/jxcore-log( 3148): ok 27 should be equal
I/jxcore-log( 3148): 
I/jxcore-log( 3148): ok 28 should be equal
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 29 should be equal
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 30 should be equal
I/jxcore-log( 3148): 
I/jxcore-log( 3148): ok 31 should be equal
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 32 should be equal
I/jxcore-log( 3148): 
I/jxcore-log( 3148): ok 33 should be equal
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 34 should be equal
I/jxcore-log( 3148): 
I/jxcore-log( 3148): ok 35 should be equal
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 36 should be equal
I/jxcore-log( 3148): 
I/jxcore-log( 3148): ok 37 should be equal
I/jxcore-log( 3148): 
I/jxcore-log( 3148): ok 38 should be equal
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 39 should be equal
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 40 should be equal
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 41 should be equal
I/jxcore-log( 3148): 
I/jxcore-log( 3148): ok 42 should be equal
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): ok 43 should be equal
I/jxcore-log( 3148): 
I/jxcore-log( 3148): ok 44 should be equal
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # teardown
I/jxcore-log( 3148): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452269963276.3148
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): bind: Binding a new listener
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3148): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963276.3148","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3148): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): start: OK
I/io.jxcore.node.ConnectionHelper( 3148): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452269963276.3148
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3148): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963276.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3148): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3148): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963276.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452269963276.3148","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3148): start: OK
I/jxcore-log( 3148): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 3148): 
I/io.jxcore.node.ConnectionHelper( 3148): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3148): stop: Stopping services
,I/wpa_supplicant(  982): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  982): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3148): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setState: NOT_STARTED
,I/jxcore-log( 3148): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 3148): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452269963427.3148
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): bind: Binding a new listener
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3148): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963427.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3148): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): start: OK
I/io.jxcore.node.ConnectionHelper( 3148): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452269963427.3148
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3148): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963427.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3148): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3148): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963427.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452269963427.3148","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): start: Starting P2P device discovery...
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3148): start: OK
,I/jxcore-log( 3148): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 3148): 
I/io.jxcore.node.ConnectionHelper( 3148): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): shutdown
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3148): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  982): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3148): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setState: NOT_STARTED
I/jxcore-log( 3148): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 3148): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452269963453.3148
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): bind: Binding a new listener
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3148): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963453.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3148): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): start: OK
I/io.jxcore.node.ConnectionHelper( 3148): start: Using peer discovery mode: WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): onServerStopped
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452269963453.3148
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3148): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963453.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3148): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3148): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963453.3148","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452269963453.3148","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): start: Starting P2P device discovery...
,I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3148): start: OK
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): Waiting for incoming connections...
,I/jxcore-log( 3148): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 3148): 
,I/io.jxcore.node.ConnectionHelper( 3148): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3148): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: NOT_INITIALIZED
I/wpa_supplicant(  982): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3148): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setState: NOT_STARTED
,I/jxcore-log( 3148): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 3148): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452269963488.3148
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): bind: Binding a new listener
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3148): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963488.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3148): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): start: OK
I/io.jxcore.node.ConnectionHelper( 3148): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452269963488.3148
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3148): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963488.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3148): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3148): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963488.3148","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452269963488.3148","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3148): start: OK
I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3148): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 3148): 
I/io.jxcore.node.ConnectionHelper( 3148): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3148): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3148): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setState: NOT_STARTED
I/wpa_supplicant(  982): P2P-FIND-STOPPED 
I/jxcore-log( 3148): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 3148): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452269963519.3148
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): bind: Binding a new listener
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3148): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963519.3148","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3148): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): start: OK
I/io.jxcore.node.ConnectionHelper( 3148): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452269963519.3148
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): Waiting for incoming connections...
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3148): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963519.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3148): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3148): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963519.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452269963519.3148","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3148): start: OK
,I/jxcore-log( 3148): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 3148): 
I/io.jxcore.node.ConnectionHelper( 3148): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): setState: NOT_STARTED
I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3148): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3148): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setState: NOT_STARTED
I/jxcore-log( 3148): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 3148): 
I/wpa_supplicant(  982): P2P-FIND-STOPPED 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452269963537.3148
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): bind: Binding a new listener
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3148): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963537.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3148): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): start: OK
I/io.jxcore.node.ConnectionHelper( 3148): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452269963537.3148
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): Waiting for incoming connections...
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3148): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963537.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3148): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3148): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963537.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452269963537.3148","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3148): start: OK
I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3148): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 3148): 
I/io.jxcore.node.ConnectionHelper( 3148): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3148): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3148): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setState: NOT_STARTED
I/wpa_supplicant(  982): P2P-FIND-STOPPED 
I/jxcore-log( 3148): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 3148): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452269963554.3148
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): bind: Binding a new listener
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3148): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963554.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3148): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): start: OK
I/io.jxcore.node.ConnectionHelper( 3148): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452269963554.3148
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): Waiting for incoming connections...
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3148): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963554.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3148): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3148): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963554.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452269963554.3148","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3148): start: OK
I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3148): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 3148): 
I/io.jxcore.node.ConnectionHelper( 3148): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3148): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3148): release: No more listeners, de-initializing...
I/wpa_supplicant(  982): P2P-FIND-STOPPED 
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setState: NOT_STARTED
I/jxcore-log( 3148): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 3148): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452269963575.3148
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): bind: Binding a new listener
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3148): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963575.3148","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3148): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): start: OK
I/io.jxcore.node.ConnectionHelper( 3148): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452269963575.3148
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3148): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963575.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3148): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3148): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963575.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452269963575.3148","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3148): start: OK
I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3148): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 3148): 
,I/io.jxcore.node.ConnectionHelper( 3148): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3148): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3148): release: No more listeners, de-initializing...
I/wpa_supplicant(  982): P2P-FIND-STOPPED 
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setState: NOT_STARTED
,I/jxcore-log( 3148): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 3148): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452269963594.3148
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): bind: Binding a new listener
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3148): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963594.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3148): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): start: OK
I/io.jxcore.node.ConnectionHelper( 3148): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452269963594.3148
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): Waiting for incoming connections...
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3148): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963594.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3148): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3148): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963594.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452269963594.3148","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3148): start: OK
I/jxcore-log( 3148): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 3148): 
I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 3148): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3148): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3148): release: No more listeners, de-initializing...
,I/wpa_supplicant(  982): P2P-FIND-STOPPED 
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setState: NOT_STARTED
,I/jxcore-log( 3148): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 3148): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452269963615.3148
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): bind: Binding a new listener
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3148): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963615.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3148): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): start: OK
I/io.jxcore.node.ConnectionHelper( 3148): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452269963615.3148
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): Waiting for incoming connections...
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3148): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963615.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3148): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3148): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452269963615.3148","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452269963615.3148","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3148): start: OK
I/wpa_supplicant(  982): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3148): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 3148): 
I/io.jxcore.node.ConnectionHelper( 3148): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3148): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3148): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3148): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3148): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3148): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3148): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3148): setState: NOT_STARTED
,I/wpa_supplicant(  982): P2P-FIND-STOPPED 
,I/jxcore-log( 3148): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): # setup
I/jxcore-log( 3148): 
I/io.jxcore.node.ConnectionHelper( 3148): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3148): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3148): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3148): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3148): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3148): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3148): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3148): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3148): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3148): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3148): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3148): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3148): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3148): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3148): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3148): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3148): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3148): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 3148): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3148): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3148): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3148): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3148): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3148): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3148): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3148): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3148): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.w,ifi.WifiServiceAdvertiser( 3148): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3148): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 3148): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3148): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3148): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3148): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3148): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 3148): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3148): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3148): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3148): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3148): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 3148): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3148): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3148): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3148): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3148): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 3148): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3148): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3148): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3148): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3148): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3148): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3148): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3148): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3148): Service requests cleared successfully
,D/HeadsetStateMachine( 2086): Disconnected process message: 10, size: 0,
D/HeadsetPhoneState( 2086): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 2086): Disconnected process message: 11, size: 0
,W/bt-smp  ( 2086): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2086): Plain text(LSB ~ MSB) = 95 0e 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2086): Encrypted text(LSB ~ MSB) = 0b 4a 62 60 d1 ad 99 65 e5 92 86 77 83 37 24 96 
W/bt-btm  ( 2086): Stopping oneshot timer
,I/EventLogService( 1637): Aggregate from 1452267968127 (log), 1452267968127 (data)
,I/ActivityManager(  758): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3577 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 3577): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3577): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PhenotypeConfigurator( 1607): Scheduling Phenotype for one-off execution 13296 seconds from now (1452270438960)
,D/GetConfigurationSnapshotOperation( 1607): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,V/JNIHelp ( 3577): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/PhenotypeFlagCommitter( 1607): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1607): Using platform SSLCertificateSocketFactory
,W/System  ( 3577): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3577): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 3577): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 3624): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1230567554.jar --oat-fd=27 --oat-location=/data/data/com.google.android.youtube/cache/ads1230567554.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3624): dex2oat took 32.435ms (threads: 4)
,W/InstanceID/Rpc( 3577): Found 10008
,I/ActivityManager(  758): Killing 2520:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10070/pid_2520/cgroup.procs: No such file or directory
,I/UsageStatsService(  758): User[0] Flushing usage stats to disk
,I/ActivityManager(  758): Killing 2922:com.android.defcontainer/u0a5 (adj 13): empty for 1806s
,I/ActivityManager(  758): Killing 3067:com.google.android.apps.docs/u0a40 (adj 13): empty for 1808s
,I/ActivityManager(  758): Killing 2953:com.google.android.gms:car/u0a8 (adj 13): empty for 1807s
,I/ActivityManager(  758): Killing 3036:com.android.musicfx/u0a15 (adj 13): empty for 1808s
,I/ActivityManager(  758): Killing 1499:com.google.android.partnersetup/u0a13 (adj 15): empty for 1808s
,I/ActivityManager(  758): Killing 2020:com.android.providers.calendar/u0a2 (adj 15): empty for 1810s
,I/ActivityManager(  758): Killing 2000:com.google.android.calendar/u0a31 (adj 15): empty for 1840s
,W/libprocessgroup(  758): failed to open /acct/uid_10005/pid_2922/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10040/pid_3067/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10008/pid_2953/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10015/pid_3036/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10013/pid_1499/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10002/pid_2020/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10031/pid_2000/cgroup.procs: No such file or directory
,I/ProcessStatsService(  758): Prepared write state in 3ms
,I/ProcessStatsService(  758): Prepared write state in 3ms
,W/bt-smp  ( 2086): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2086): Plain text(LSB ~ MSB) = d0 13 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2086): Encrypted text(LSB ~ MSB) = 32 2b d7 d5 69 4a e9 d0 43 fb 07 84 e1 e4 4d eb 
W/bt-btm  ( 2086): Stopping oneshot timer
,I/ProcessStatsService(  758): Prepared write state in 6ms
,I/ProcessStatsService(  758): Prepared write state in 5ms
,I/ProcessStatsService(  758): Prepared write state in 7ms
,I/ProcessStatsService(  758): Prepared write state in 3ms
,I/ProcessStatsService(  758): Prepared write state in 3ms
,I/ProcessStatsService(  758): Prepared write state in 4ms
,I/ProcessStatsService(  758): Prepared write state in 3ms
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1607): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  758): Pruning old procstats: /data/system/procstats/state-2016-01-08-01-54-16.bin
,TIME-OUT KILL (timeout was 1800000ms)
```
