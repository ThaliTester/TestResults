#### Test 55902202f27eba5_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3140): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3140):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3140):   adb logcat -s GAv4
W/GAv4    ( 3140): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3140): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3140): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3140): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2621): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3140): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3140): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  733): Killing 2073:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 3140): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3140): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3140): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  733): failed to open /acct/uid_10038/pid_2073/cgroup.procs: No such file or directory
V/GLSActivity( 1598): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1625): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1625): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1625): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1625): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
D/CAR.SERVICE( 3010): mConnectedToCar = false, abort
E/ActivityThread( 3010): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3c541539 that was originally bound here
E/ActivityThread( 3010): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3c541539 that was originally bound here
E/ActivityThread( 3010): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3010): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3010): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3010): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3010): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3010): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3010): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3010): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3010): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3010): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3010): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3010): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3010): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3010): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3010): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3010): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3010): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3010): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3010): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3010): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3010): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3010): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3010): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/ActivityThread( 3010): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@17004818 that was originally bound here
E/ActivityThread( 3010): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@17004818 that was originally bound here
E/ActivityThread( 3010): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3010): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3010): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3010): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3010): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3010): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3010): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3010): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3010): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3010): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3010): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3010): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3010): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3010): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3010): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3010): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3010): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3010): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3010): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3010): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3010): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3010): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  733): Unbind failed: could not find connection for android.os.BinderProxy@384d834a
,D/AndroidRuntime( 3202): 
D/AndroidRuntime( 3202): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/ActivityManager(  733): Killing 2590:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
D/AndroidRuntime( 3202): CheckJNI is OFF
W/libprocessgroup(  733): failed to open /acct/uid_10069/pid_2590/cgroup.procs: No such file or directory
D/AndroidRuntime( 3202): Calling main entry com.android.commands.am.Am
I/ActivityManager(  733): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  733): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3226 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3202): Shutting down VM
V/ActivityManager(  733): Display changed displayId=0
,I/WebViewFactory( 3226): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3226): Time to load native libraries: 3 ms (timestamps 8249-8252)
,I/LibraryLoader( 3226): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3226): Binding Chromium to main looper Looper (main, tid 1) {14eb8358}
I/LibraryLoader( 3226): Expected native library version number "",actual native library version number ""
I/chromium( 3226): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3226): Initializing chromium process, singleProcess=true
,W/art     ( 3226): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3226): ApplicationContext is null in ApplicationStatus
,W/chromium( 3226): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3226): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3226): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3226): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  733): Message: 20
,D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@333cfa8f:true
,W/art     ( 3226): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3226): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3226): CordovaWebView is running on device made by: LGE
,W/art     ( 3226): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3226): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3226): Render dirty regions requested: true
,D/Atlas   ( 3226): Validating map...
,W/chromium( 3226): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3226): Initialized EGL, version 1.4
D/OpenGLRenderer( 3226): Enabling debug mode 0
,I/Keyboard.Facilitator( 1082): onFinishInput()
,W/IInputConnectionWrapper( 3226): showStatusIcon on inactive InputConnection
,I/ActivityManager(  733): Displayed com.test.thalitest/.MainActivity: +449ms (total +57s527ms)
,W/BindingManager( 3226): Cannot call determinedVisibility() - never saw a connection for the pid: 3226
,D/JsMessageQueue( 3226): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3226): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257343360
,D/JX-Cordova( 3226): jxcore cordova android initializing
,W/jxcore-log( 3226): Initializing JXcore engine
W/jxcore-log( 3226): JXcore engine is ready
,W/jxcore-log( 3226): Starting JXcore engine
,W/.test.thalitest( 3226): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8418]" dev="sockfs" ino=8418 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3226): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3226): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8484]" dev="sockfs" ino=8484 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3226): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19299]" dev="sockfs" ino=19299 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3226): Platform android
W/jxcore-log( 3226): 
W/jxcore-log( 3226): Process ARCH arm
W/jxcore-log( 3226): 
,I/jxcore-log( 3226): JXcore Cordova bridge is ready!
I/jxcore-log( 3226): 
,W/jxcore-log( 3226): JXcore engine is started
I/Choreographer( 3226): Skipped 115 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3226): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3226): Toggling radios to true
I/jxcore-log( 3226): 
,D/BluetoothAdapter( 3226): enable(): BT is already enabled..!
,D/WifiService(  733): New client listening to asynchronous messages
,D/WifiService(  733): setWifiEnabled: true pid=3226, uid=10270
E/WifiService(  733): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3226): Radios toggled
I/jxcore-log( 3226): 
,I/jxcore-log( 3226): My device name is: LGE-Nexus 5
I/jxcore-log( 3226): 
,I/wpa_supplicant(  977): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  733): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  733): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1598): Read error: ssl=0xb5068400: I/O error during system call, Connection timed out
,V/NativeCrypto( 1598): SSL shutdown failed: ssl=0xb5068400: I/O error during system call, Broken pipe
,D/ConnectivityService(  733): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  733): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  977): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  733): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
D/ConnectivityService(  733): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  733): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  733): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Disconnected - quitting
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524292
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  733): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1224): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  733): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/ConnectivityManager.CallbackHandler( 1625): CM callback handler got msg 524292
,D/WifiNetworkAgent(  733): NetworkAgent: NetworkAgent channel lost
,W/NetworkUtils( 1389): OkHttp exception
W/EventLoggerService( 1389): Unable to send logs Error code: 262146
,V/GLSActivity( 1598): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1598): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant(  977): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  977): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  977): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  977): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  733): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
,E/WifiStateMachine(  733): Start Dhcp Watchdog 2
,E/native  (  733): do suspend false
,E/WifiStateMachine(  733): scanCount==0 - aborting
,I/dhcpcd  ( 3311): version 5.5.6 starting
E/dhcpcd  ( 3311): get_duid: Read-only file system
,I/dhcpcd  ( 3311): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3311): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3311): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  733): MasterInitialState.processMessage what=3
D/Tethering(  733): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2748): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1625): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1625): onCreate
,D/SystemUpdateService( 1625): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1625): active receiver: enabled
,I/iu.Environment( 1625): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1625): num queued entries: 0
I/iu.UploadsManager( 1625): num updated entries: 0
I/iu.SyncManager( 1625): NEXT; no task
,I/SystemUpdateService( 1625): showing system update notification
,I/Babel   ( 1935): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  733): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3346 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/native  (  733): do suspend true
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  733): Adding iface wlan0 to network 101
,E/WifiStateMachine(  733): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  733): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  733): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  733): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  733): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  733): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  733): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  733): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733):    accepting network in place of null
D/CSLegacyTypeTracker(  733): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  733): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::5255:27ff:fef0:fd0b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  733): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1625): CM callback handler got msg 524290
,E/GpsLocationProvider(  733): No APN found to select.
,E/GpsLocationProvider(  733): No APN found to select.
,I/ValidateNoPeople(  733): skipping global notification
,V/SystemUpdateService( 1625): retry (wakeup: false) in 3599899 ms
,D/SystemUpdateService( 1625): onDestroy
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 13 Jan 2016 15:35:32 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452699332926], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452699332906]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Validated
D/ConnectivityService(  733): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  733): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1625): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1224): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/GAv4    ( 3346): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3346):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3346):   adb logcat -s GAv4
,W/GAv4    ( 3346): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3346): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3346): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3346): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3346): Time to load native libraries: 2 ms (timestamps 4384-4386)
I/LibraryLoader( 3346): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3346): Binding Chromium to main looper Looper (main, tid 1) {3f84ad8a}
,I/LibraryLoader( 3346): Expected native library version number "",actual native library version number ""
I/chromium( 3346): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3346): Initializing chromium process, singleProcess=true
W/art     ( 3346): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3346): ApplicationContext is null in ApplicationStatus
,W/chromium( 3346): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3346): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3346): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3346): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3346): Starting up...
,W/AudioManagerAndroid( 3346): Requires BLUETOOTH permission
,I/ActivityManager(  733): Killing 2528:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10045/pid_2528/cgroup.procs: No such file or directory
,V/MusicLeanback( 2748): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1625): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1625): onCreate
,D/SystemUpdateService( 1625): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1625): active receiver: enabled
,I/SystemUpdateService( 1625): showing system update notification
,I/iu.Environment( 1625): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1625): num queued entries: 0
I/iu.UploadsManager( 1625): num updated entries: 0
I/iu.SyncManager( 1625): NEXT; no task
,I/ValidateNoPeople(  733): skipping global notification
,V/SystemUpdateService( 1625): retry (wakeup: false) in 3599943 ms
,D/SystemUpdateService( 1625): onDestroy
,I/Babel   ( 1935): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  733): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  733): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2748): type=WIFI subType= reason=null isConnected=true
V/MusicLeanback( 2748): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1625): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1625): onCreate
D/SystemUpdateService( 1625): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1625): active receiver: enabled
,I/jxcore-log( 3226): Test app app.js loaded
I/jxcore-log( 3226): 
,I/Choreographer( 3226): Skipped 382 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3226): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SystemUpdateService( 1625): showing system update notification
,E/GpsLocationProvider(  733): No APN found to select.
,I/ValidateNoPeople(  733): skipping global notification
V/SystemUpdateService( 1625): retry (wakeup: false) in 3599974 ms
D/SystemUpdateService( 1625): onDestroy
,I/art     (  733): Explicit concurrent mark sweep GC freed 45381(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 919us total 65.967ms
,D/Finsky  ( 2621): [256] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2621): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1598): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1598): Vacuum at: now=1452699351317 tag=VacuumService
,I/PhenotypeConfigurator( 1598): Scheduling Phenotype for one-off execution 5724 seconds from now (1452699351667)
,D/GetConfigurationSnapshotOperation( 1598): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1598): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1598): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1598): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1598): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1082): run()
I/Keyboard.Facilitator( 1082): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1598): disconnect managed GoogleApiClient
,I/EventLogService( 1625): Aggregate from 1452697634694 (log), 1452697634694 (data)
,I/jxcore-log( 3226): --= Surplus to requirements =--
I/jxcore-log( 3226): 
I/jxcore-log( 3226): ****TEST TOOK:  ms ****
I/jxcore-log( 3226): 
I/jxcore-log( 3226): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3226): 
,D/AndroidRuntime( 3522): 
D/AndroidRuntime( 3522): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3522): CheckJNI is OFF
,D/AndroidRuntime( 3522): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  733): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  733): Killing 3226:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  733): WIN DEATH: Window{3897a57f u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  733): Client connection lost with reason: 4
,I/ActivityManager(  733):   Force finishing activity ActivityRecord{2c3da2bb u0 com.test.thalitest/.MainActivity t216}
,W/PackageSettings(  733): Skipping PackageSetting{1843c86c com.example.hello/10278} due to missing metadata
,W/ActivityManager(  733): Spurious death for ProcessRecord{1239eb1 3226:com.test.thalitest/u0a270}, curProc for 3226: null
,I/ActivityManager(  733): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1389): Explicit concurrent mark sweep GC freed 8861(572KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 318us total 18.781ms
,I/art     ( 1256): Explicit concurrent mark sweep GC freed 4023(297KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 463us total 33.813ms
I/art     ( 1625): Explicit concurrent mark sweep GC freed 12360(651KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 22MB/30MB, paused 972us total 78.098ms
,W/GeofencerStateMachine( 1598): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1082): resetDictionaries() : en_US
,I/InputReader(  733): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1082): run()
,I/Decoder ( 1082): createOrResetDecoder
,I/art     (  733): Explicit concurrent mark sweep GC freed 23723(1351KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.965ms total 76.748ms
,D/VoicemailCleanupService( 1331): Cleaning up data for package: com.test.thalitest
,I/UpdateIcingCorporaServi( 1389): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1256): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@185becb1 new=com.google.android.velvet.VelvetApplication@185becb1
,I/Adreno-EGL(  941): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  941): Initialized EGL, version 1.4
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1082): run()
D/OpenGLRenderer(  941): Enabling debug mode 0
,I/ActivityManager(  733): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3562 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  733): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  733): Receieved: android.intent.action.PACKAGE_REMOVED
W/InputMethodManagerService(  733): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@c6fe471 (uid=10034 pid=941)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1082): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1082): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1082): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1082): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1082): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1082): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1082): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1082): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1082): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1082): run()
,D/TaskPersister(  733): removeObsoleteFile: deleting file=216_task.xml
,I/UpdateIcingCorporaServi( 1389): UpdateCorporaTask done [took 119 ms] updated apps [took 119 ms] 
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1082): run()
I/StatsUtilsManager( 1082): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1082): shouldRecordStats() = Too Soon
,W/ContextImpl( 3562): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1625): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1625): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1625): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1625): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1625): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1625): Module APK com.google.android.play.games already loaded
,W/InputMethodManagerService(  733): Got RemoteException sending setActive(false) notification to pid 3226 uid 10270
,E/NetworkScheduler.SchedulerReceiver( 1598): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1598): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Keyboard.Facilitator( 1082): onFinishInput()
,I/art     (  733): Explicit concurrent mark sweep GC freed 7803(361KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.343ms total 170.088ms
,I/LocationSettingsChecker( 1625): Removing dialog suppression flag for package com.test.thalitest
,I/Launcher( 1256): Deferring update until onResume
,D/gH_CompatibleDatabase( 1625): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1625): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1625): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1625): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1625): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1625): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1625): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1625): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1625): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1625): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1625): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1625): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1625): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/ResourcesManager( 1256): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1256): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1256): Deferring update until onResume
,I/ActivityManager(  733): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3596 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,D/AndroidRuntime( 3522): Shutting down VM
,I/GMPM-SVC( 1625): App measurement is starting up, version: 8489
I/GMPM-SVC( 1625): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/BaseAppContext( 1625): Using Auth Proxy for data requests.
,W/BaseAppContext( 1625): Using Auth Proxy for data requests.
,I/ActivityManager(  733): Killing 2722:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10003/pid_2722/cgroup.procs: No such file or directory
,I/Icing   ( 1625): doRemovePackageData com.test.thalitest
,I/ActivityManager(  733): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3620 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  733): Killing 2696:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  733): Client connection lost with reason: 4
,W/libprocessgroup(  733): failed to open /acct/uid_1000/pid_2696/cgroup.procs: No such file or directory
,I/ActivityManager(  733): Killing 2561:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10070/pid_2561/cgroup.procs: No such file or directory
,D/ExternalStorage( 3620): After updating volumes, found 1 active roots
,W/ResourcesManager( 3140): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3140): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3596): Update found 7 roots in 196ms

```
