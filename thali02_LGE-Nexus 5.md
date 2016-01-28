#### Test 573480789efee08_thali02_LGE-Nexus 5 Logs


```
--------- beginning of system
W/libprocessgroup(  756): failed to open /acct/uid_10080/pid_2489/cgroup.procs: No such file or directory
W/libprocessgroup(  756): failed to open /acct/uid_1000/pid_2401/cgroup.procs: No such file or directory
,--------- beginning of main
I/GAv4    ( 3163): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3163):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3163):   adb logcat -s GAv4
W/GAv4    ( 3163): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3163): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3163): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
W/GAv4    ( 3163): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/ChimeraCfgMgr( 1629): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1629): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 3196): 
D/AndroidRuntime( 3196): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3196): CheckJNI is OFF
D/Finsky  ( 2687): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
W/ResourcesManager( 3163): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3163): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AndroidRuntime( 3196): Calling main entry com.android.commands.am.Am
I/ActivityManager(  756): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  756): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3232 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3196): Shutting down VM
V/JNIHelp ( 3163): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/Finsky  ( 2687): [265] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/ActivityManager(  756): Display changed displayId=0
W/System  ( 3163): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3163): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1629): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/WebViewFactory( 3232): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/Icing   ( 1629): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/LibraryLoader( 3232): Time to load native libraries: 1 ms (timestamps 6132-6133)
I/LibraryLoader( 3232): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3232): Binding Chromium to main looper Looper (main, tid 1) {33359edd}
I/LibraryLoader( 3232): Expected native library version number "",actual native library version number ""
I/chromium( 3232): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3232): Initializing chromium process, singleProcess=true
W/art     ( 3232): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3232): ApplicationContext is null in ApplicationStatus
I/Icing   ( 1629): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
W/chromium( 3232): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3232): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3232): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3232): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/Icing   ( 1629): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/BluetoothManagerService(  756): Message: 20
D/BluetoothManagerService(  756): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@188c1a24:true
,W/art     ( 3232): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3232): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3232): CordovaWebView is running on device made by: LGE
,W/art     ( 3232): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3232): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3232): Render dirty regions requested: true
,D/Atlas   ( 3232): Validating map...
,W/chromium( 3232): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  756): Killing 2127:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10038/pid_2127/cgroup.procs: No such file or directory
I/OpenGLRenderer( 3232): Initialized EGL, version 1.4
D/OpenGLRenderer( 3232): Enabling debug mode 0
I/Keyboard.Facilitator( 1094): onFinishInput()
W/BindingManager( 3232): Cannot call determinedVisibility() - never saw a connection for the pid: 3232
I/ActivityManager(  756): Displayed com.test.thalitest/.MainActivity: +627ms (total +54s362ms)
W/IInputConnectionWrapper( 3232): showStatusIcon on inactive InputConnection
D/JsMessageQueue( 3232): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3232): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257343360
I/chromium( 3232): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/ActivityManager(  756): Killing 2653:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/libprocessgroup(  756): failed to open /acct/uid_10069/pid_2653/cgroup.procs: No such file or directory
,W/jxcore-log( 3232): Initializing JXcore engine
W/jxcore-log( 3232): JXcore engine is ready
,W/Thread-301( 3296): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8482]" dev="sockfs" ino=8482 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-301( 3296): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/Thread-301( 3296): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6594]" dev="sockfs" ino=6594 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-301( 3296): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19325]" dev="sockfs" ino=19325 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3232): Starting JXcore engine
,W/jxcore-log( 3232): Platform android
W/jxcore-log( 3232): 
W/jxcore-log( 3232): Process ARCH arm
W/jxcore-log( 3232): 
,I/jxcore-log( 3232): JXcore Cordova bridge is ready!
I/jxcore-log( 3232): 
,W/jxcore-log( 3232): JXcore engine is started
,I/jxcore-log( 3232): Toggling radios to true
I/jxcore-log( 3232): 
,D/BluetoothAdapter( 3232): enable(): BT is already enabled..!
,D/WifiService(  756): New client listening to asynchronous messages
,D/WifiService(  756): setWifiEnabled: true pid=3232, uid=10270
E/WifiService(  756): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3232): Radios toggled
I/jxcore-log( 3232): 
I/jxcore-log( 3232): My device name is: LGE-Nexus 5
I/jxcore-log( 3232): 
,I/wpa_supplicant(  990): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  756): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  756): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  756): Start Disconnecting Watchdog 1
,E/native  (  756): do suspend true
,V/NativeCrypto( 1602): Read error: ssl=0xb3e28e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1602): SSL shutdown failed: ssl=0xb3e28e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  756): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/wpa_supplicant(  990): wlan0: CTRL-EVENT-SCAN-STARTED 
,W/ProcessCpuTracker(  756): Skipping unknown process pid 3309
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  756): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  756): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  756): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Disconnected - quitting
,D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  756): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1221): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1629): CM callback handler got msg 524292
,D/WifiNetworkAgent(  756): NetworkAgent: NetworkAgent channel lost
,E/ConnectivityService(  756): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/CAR.SERVICE( 3076): mConnectedToCar = false, abort
,E/ActivityThread( 3076): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1b740cba that was originally bound here
E/ActivityThread( 3076): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1b740cba that was originally bound here
E/ActivityThread( 3076): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3076): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3076): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3076): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3076): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3076): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3076): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3076): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3076): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3076): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3076): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3076): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3076): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3076): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3076): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3076): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3076): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3076): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3076): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3076): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3076): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3076): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3076): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3076): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2893f09d that was originally bound here
E/ActivityThread( 3076): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2893f09d that was originally bound here
E/ActivityThread( 3076): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3076): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3076): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3076): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3076): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3076): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3076): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3076): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3076): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3076): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3076): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3076): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3076): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3076): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3076): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3076): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3076): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3076): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3076): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3076): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3076): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3076): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  756): Unbind failed: could not find connection for android.os.BinderProxy@1ba5ae3e
,I/wpa_supplicant(  990): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  990): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  990): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  990): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  756): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
,E/WifiStateMachine(  756): Start Dhcp Watchdog 2
,E/native  (  756): do suspend false
,E/WifiStateMachine(  756): scanCount==0 - aborting
,I/dhcpcd  ( 3353): version 5.5.6 starting
E/dhcpcd  ( 3353): get_duid: Read-only file system
,I/dhcpcd  ( 3353): wlan0: rebinding lease of 192.168.1.114
,D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/Tethering(  756): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2796): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/dhcpcd  ( 3353): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/SystemUpdateService( 1629): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1629): onCreate
,D/SystemUpdateService( 1629): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1629): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1629): num queued entries: 0
,I/Babel   ( 1984): connection state changed from CONNECTED to DISCONNECTED
,I/dhcpcd  ( 3353): wlan0: leased 192.168.1.114 for 86400 seconds
,I/iu.UploadsManager( 1629): num updated entries: 0
,I/iu.SyncManager( 1629): NEXT; no task
,I/SystemUpdateService( 1629): active receiver: enabled
,I/ActivityManager(  756): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3364 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  756): No APN found to select.
,I/SystemUpdateService( 1629): showing system update notification
,E/GpsLocationProvider(  756): No APN found to select.
,I/ValidateNoPeople(  756): skipping global notification
,V/SystemUpdateService( 1629): retry (wakeup: false) in 3599914 ms
,D/SystemUpdateService( 1629): onDestroy
,E/native  (  756): do suspend true
,D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  756): Adding iface wlan0 to network 101
,E/WifiStateMachine(  756): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
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
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  756): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  756): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  756): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1629): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,I/GAv4    ( 3364): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3364):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3364):   adb logcat -s GAv4
,W/GAv4    ( 3364): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3364): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3364): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jan 2016 11:46:18 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453981578603], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453981578584]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Validated
,D/ConnectivityService(  756): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  756): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1629): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1221): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WebViewFactory( 3364): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3364): Time to load native libraries: 2 ms (timestamps 2542-2544)
I/LibraryLoader( 3364): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3364): Binding Chromium to main looper Looper (main, tid 1) {3adfef47}
,I/LibraryLoader( 3364): Expected native library version number "",actual native library version number ""
,I/chromium( 3364): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3364): Initializing chromium process, singleProcess=true
,W/art     ( 3364): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3364): ApplicationContext is null in ApplicationStatus
,W/chromium( 3364): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3364): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3364): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3364): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3364): Requires BLUETOOTH permission
,I/NSApplication( 3364): Starting up...
,I/ActivityManager(  756): Killing 2602:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10045/pid_2602/cgroup.procs: No such file or directory
,V/MusicLeanback( 2796): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1629): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1629): onCreate
,D/SystemUpdateService( 1629): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1629): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1629): num queued entries: 0
I/SystemUpdateService( 1629): active receiver: enabled
I/iu.UploadsManager( 1629): num updated entries: 0
I/iu.SyncManager( 1629): NEXT; no task
,I/SystemUpdateService( 1629): showing system update notification
,I/art     (  756): Explicit concurrent mark sweep GC freed 42404(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 1.236ms total 63.015ms
,I/ValidateNoPeople(  756): skipping global notification
,V/SystemUpdateService( 1629): retry (wakeup: false) in 3599877 ms
,D/SystemUpdateService( 1629): onDestroy
,I/Babel   ( 1984): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3232): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3232): 
,D/ConnectivityService(  756): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3232): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3232): 
,I/jxcore-log( 3232): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3232): 
,I/jxcore-log( 3232): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3232): 
,I/jxcore-log( 3232): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3232): 
,I/jxcore-log( 3232): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3232): 
,I/jxcore-log( 3232): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3232): 
,I/jxcore-log( 3232): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3232): 
,D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  756): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2796): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2796): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1629): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1629): onCreate
,D/SystemUpdateService( 1629): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1629): active receiver: enabled
,E/GpsLocationProvider(  756): No APN found to select.
,I/SystemUpdateService( 1629): showing system update notification
,I/ValidateNoPeople(  756): skipping global notification
,V/SystemUpdateService( 1629): retry (wakeup: false) in 3599977 ms
,D/SystemUpdateService( 1629): onDestroy
,I/jxcore-log( 3232): Test app app.js loaded
I/jxcore-log( 3232): 
,I/chromium( 3232): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3232): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3232): BLE advertisement is supported
I/jxcore-log( 3232): 
,D/Finsky  ( 2687): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2687): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1602): Vacuum at: now=1453981600677 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1094): run()
I/Keyboard.Facilitator( 1094): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1602): disconnect managed GoogleApiClient
,I/jxcore-log( 3232): --= Surplus to requirements =--
I/jxcore-log( 3232): 
I/jxcore-log( 3232): ****TEST TOOK:  ms ****
I/jxcore-log( 3232): 
I/jxcore-log( 3232): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3232): 
,D/AndroidRuntime( 3565): 
D/AndroidRuntime( 3565): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3565): CheckJNI is OFF
,D/AndroidRuntime( 3565): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  756): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
,I/ActivityManager(  756): Killing 3232:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  756): WIN DEATH: Window{3a3c5454 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  756): Client connection lost with reason: 4
,W/PackageSettings(  756): Skipping PackageSetting{1fd5d5a1 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  756):   Force finishing activity ActivityRecord{3fdffcf u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  756): Spurious death for ProcessRecord{35bd4b44 3232:com.test.thalitest/u0a270}, curProc for 3232: null
,I/ActivityManager(  756): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1277): Explicit concurrent mark sweep GC freed 3995(296KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 3.001ms total 19.574ms
,W/GeofencerStateMachine( 1602): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1094): resetDictionaries() : en_US
,I/Adreno-EGL(  943): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  943): Initialized EGL, version 1.4
,I/art     (  756): Explicit concurrent mark sweep GC freed 23798(1355KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 1.318ms total 83.555ms
,I/art     (  756): WaitForGcToComplete blocked for 6.210ms for cause Explicit
,D/OpenGLRenderer(  943): Enabling debug mode 0
,I/Keyboard.Facilitator.DecoderInitializer( 1094): run()
,I/Decoder ( 1094): createOrResetDecoder
,I/art     ( 1629): Explicit concurrent mark sweep GC freed 7296(353KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 440us total 129.287ms
,D/VoicemailCleanupService( 1373): Cleaning up data for package: com.test.thalitest
I/art     ( 1404): Explicit concurrent mark sweep GC freed 5959(509KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 20MB/26MB, paused 6.852ms total 127.591ms
,W/InputMethodManagerService(  756): Got RemoteException sending setActive(false) notification to pid 3232 uid 10270
,I/UpdateIcingCorporaServi( 1404): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/Keyboard.Facilitator( 1094): onFinishInput()
,W/Launcher( 1277): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@202a2a52 new=com.google.android.velvet.VelvetApplication@202a2a52
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1094): run()
,I/ActivityManager(  756): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3606 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  756): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  756): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1094): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1094): run()
,W/ContextImpl( 3606): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1094): run() : Loading LM = contacts
,D/TaskPersister(  756): removeObsoleteFile: deleting file=216_task.xml
,I/Keyboard.Facilitator( 1094): onFinishInput()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1094): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1094): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1094): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1094): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1094): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1094): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1094): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1094): run()
I/StatsUtilsManager( 1094): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1094): shouldRecordStats() = Too Soon
,W/IInputConnectionWrapper( 1277): showStatusIcon on inactive InputConnection
,D/PackageBroadcastService( 1629): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1629): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1629): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1629): Module APK com.google.android.play.games already loaded
I/UpdateIcingCorporaServi( 1404): UpdateCorporaTask done [took 122 ms] updated apps [took 121 ms] 
,D/ChimeraCfgMgr( 1629): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1629): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  756): Killing 2775:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,I/art     (  756): Explicit concurrent mark sweep GC freed 7183(385KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.025ms total 200.775ms
,W/libprocessgroup(  756): failed to open /acct/uid_10003/pid_2775/cgroup.procs: No such file or directory
,E/NetworkScheduler.SchedulerReceiver( 1602): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1602): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/Launcher( 1277): Deferring update until onResume
,I/LocationSettingsChecker( 1629): Removing dialog suppression flag for package com.test.thalitest
,W/ResourcesManager( 1277): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1629): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1629): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1629): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1629): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/ResourcesManager( 1277): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1629): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1629): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1629): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/AndroidRuntime( 3565): Shutting down VM
,D/gH_CompatibleDatabase( 1629): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1629): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1629): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1629): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1629): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1629): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/Launcher( 1277): Deferring update until onResume
,I/ActivityManager(  756): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3638 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,W/BaseAppContext( 1629): Using Auth Proxy for data requests.
,W/BaseAppContext( 1629): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1629): App measurement is starting up, version: 8489
I/GMPM-SVC( 1629): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/Icing   ( 1629): doRemovePackageData com.test.thalitest
,I/ActivityManager(  756): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3663 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  756): Killing 2755:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  756): Client connection lost with reason: 4
,W/libprocessgroup(  756): failed to open /acct/uid_1000/pid_2755/cgroup.procs: No such file or directory
,I/ActivityManager(  756): Killing 2624:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10070/pid_2624/cgroup.procs: No such file or directory
,D/ExternalStorage( 3663): After updating volumes, found 1 active roots
,W/ResourcesManager( 3163): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3163): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3638): Update found 7 roots in 249ms
,D/Documents( 3638): Update found 7 roots in 112ms

```
