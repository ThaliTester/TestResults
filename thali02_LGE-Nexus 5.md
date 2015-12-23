#### Test 543122980a88295_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1686): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1686): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3306): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3306):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3306):   adb logcat -s GAv4
W/GAv4    ( 3306): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3306): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3306): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3306): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
E/SQLiteLog( 3306): (283) recovered 24 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal
D/Finsky  ( 2716): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3306): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3306): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 3306): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  734): Killing 2162:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/System  ( 3306): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3306): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  734): failed to open /acct/uid_10038/pid_2162/cgroup.procs: No such file or directory
V/GLSActivity( 1660): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1686): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1686): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1686): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1686): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3374): 
D/AndroidRuntime( 3374): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3374): CheckJNI is OFF
D/AndroidRuntime( 3374): Calling main entry com.android.commands.am.Am
I/ActivityManager(  734): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  734): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3388 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3374): Shutting down VM
V/ActivityManager(  734): Display changed displayId=0
I/ActivityManager(  734): Killing 2688:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
I/WebViewFactory( 3388): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
W/libprocessgroup(  734): failed to open /acct/uid_10069/pid_2688/cgroup.procs: No such file or directory
I/LibraryLoader( 3388): Time to load native libraries: 2 ms (timestamps 7407-7409)
I/LibraryLoader( 3388): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3388): Binding Chromium to main looper Looper (main, tid 1) {1cd86236}
I/LibraryLoader( 3388): Expected native library version number "",actual native library version number ""
I/chromium( 3388): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3388): Initializing chromium process, singleProcess=true
W/art     ( 3388): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3388): ApplicationContext is null in ApplicationStatus
W/chromium( 3388): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3388): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3388): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3388): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3db7436a:true
,W/art     ( 3388): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3388): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3388): CordovaWebView is running on device made by: LGE
,W/art     ( 3388): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3388): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3388): Render dirty regions requested: true
,D/Atlas   ( 3388): Validating map...
,W/chromium( 3388): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3388): Initialized EGL, version 1.4
D/OpenGLRenderer( 3388): Enabling debug mode 0
,I/Keyboard.Facilitator( 1085): onFinishInput()
,W/IInputConnectionWrapper( 3388): showStatusIcon on inactive InputConnection
,I/ActivityManager(  734): Displayed com.test.thalitest/.MainActivity: +413ms (total +56s283ms)
,W/BindingManager( 3388): Cannot call determinedVisibility() - never saw a connection for the pid: 3388
,D/JsMessageQueue( 3388): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3388): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258381056
D/JX-Cordova( 3388): jxcore cordova android initializing
,D/CAR.SERVICE( 3200): mConnectedToCar = false, abort
,E/ActivityThread( 3200): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3788a0ff that was originally bound here
E/ActivityThread( 3200): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3788a0ff that was originally bound here
E/ActivityThread( 3200): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3200): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3200): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3200): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3200): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3200): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3200): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3200): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3200): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3200): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3200): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3200): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3200): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3200): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3200): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3200): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3200): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3200): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3200): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3200): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3200): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3200): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3200): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3200): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1a5634f6 that was originally bound here
E/ActivityThread( 3200): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1a5634f6 that was originally bound here
E/ActivityThread( 3200): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3200): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3200): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3200): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3200): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3200): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3200): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3200): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3200): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3200): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3200): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3200): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3200): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3200): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3200): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3200): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3200): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3200): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3200): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3200): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3200): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3200): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  734): Unbind failed: could not find connection for android.os.BinderProxy@286cd3c3
,W/jxcore-log( 3388): Initializing JXcore engine
W/jxcore-log( 3388): JXcore engine is ready
,W/jxcore-log( 3388): Starting JXcore engine
,W/.test.thalitest( 3388): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7985]" dev="sockfs" ino=7985 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3388): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 3388): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8445]" dev="sockfs" ino=8445 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3388): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20533]" dev="sockfs" ino=20533 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3388): Platform android
W/jxcore-log( 3388): 
,W/jxcore-log( 3388): Process ARCH arm
W/jxcore-log( 3388): 
,I/jxcore-log( 3388): JXcore Cordova bridge is ready!
I/jxcore-log( 3388): 
W/jxcore-log( 3388): JXcore engine is started
I/Choreographer( 3388): Skipped 114 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3388): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3388): Toggling radios to true
I/jxcore-log( 3388): 
,D/BluetoothAdapter( 3388): enable(): BT is already enabled..!
,D/WifiService(  734): New client listening to asynchronous messages
,D/WifiService(  734): setWifiEnabled: true pid=3388, uid=10270
E/WifiService(  734): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3388): Radios toggled
I/jxcore-log( 3388): 
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3388): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3388): 
I/jxcore-log( 3388): Perf Test app loaded loaded
I/jxcore-log( 3388): 
I/wpa_supplicant(  984): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  734): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  734): do suspend true
,I/Choreographer( 3388): Skipped 58 frames!  The application may be doing too much work on its main thread.
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,I/jxcore-log( 3388): check test folder
I/jxcore-log( 3388): 
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 3388): found test : ./testFindPeers.js
I/jxcore-log( 3388): 
,E/WifiStateMachine(  734): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  984): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  734): do suspend true
,I/jxcore-log( 3388): found test : ./testSendData.js
I/jxcore-log( 3388): 
,V/NativeCrypto( 1660): Read error: ssl=0x9d36c000: I/O error during system call, Connection timed out
,V/NativeCrypto( 1660): SSL shutdown failed: ssl=0x9d36c000: I/O error during system call, Broken pipe
,D/ConnectivityService(  734): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  734): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  734): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/CSLegacyTypeTracker(  734): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=-7ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=-7ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1686): CM callback handler got msg 524292
,I/jxcore-log( 3388): found test : ./testSendData2.js
I/jxcore-log( 3388): 
D/ConnectivityService(  734): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  734): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/TelephonyNetworkFactory( 1236): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  734): NetworkAgent: NetworkAgent channel lost
,I/chromium( 3388): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/NetworkUtils( 1357): OkHttp exception
,W/EventLoggerService( 1357): Unable to send logs Error code: 262146
,I/wpa_supplicant(  984): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  984): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  984): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  984): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  734): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  734): Start Dhcp Watchdog 2
,E/native  (  734): do suspend false
,E/WifiStateMachine(  734): scanCount==0 - aborting
,I/dhcpcd  ( 3481): version 5.5.6 starting
E/dhcpcd  ( 3481): get_duid: Read-only file system
,I/dhcpcd  ( 3481): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3481): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3481): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  734): MasterInitialState.processMessage what=3
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  734): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2836): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  734): No APN found to select.
,E/GpsLocationProvider(  734): No APN found to select.
,I/SystemUpdateService( 1686): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1686): onCreate
,D/SystemUpdateService( 1686): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/SystemUpdateService( 1686): active receiver: enabled
,I/SystemUpdateService( 1686): showing system update notification
,I/iu.Environment( 1686): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1686): num queued entries: 0
I/iu.UploadsManager( 1686): num updated entries: 0
,I/iu.SyncManager( 1686): NEXT; no task
,I/Babel   ( 2021): connection state changed from CONNECTED to DISCONNECTED
,I/ValidateNoPeople(  734): skipping global notification
,V/SystemUpdateService( 1686): retry (wakeup: false) in 3599982 ms
,I/ActivityManager(  734): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3537 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1686): onDestroy
,E/native  (  734): do suspend true
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  734): Adding iface wlan0 to network 101
,E/WifiStateMachine(  734): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  734): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  734): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  734): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  734): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  734): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  734): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  734): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  734): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  734): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  734): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1686): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Dec 2015 01:26:18 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450833979021], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450833979002]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Validated
,D/ConnectivityService(  734): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  734): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1236): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1686): CM callback handler got msg 524290
,I/GAv4    ( 3537): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3537):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3537):   adb logcat -s GAv4
,W/GAv4    ( 3537): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3537): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3537): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/Nat464Xlat(  734): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  734): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1686): CM callback handler got msg 524295
,I/WebViewFactory( 3537): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3537): Time to load native libraries: 1 ms (timestamps 4465-4466)
I/LibraryLoader( 3537): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3537): Binding Chromium to main looper Looper (main, tid 1) {bdfabb8}
I/LibraryLoader( 3537): Expected native library version number "",actual native library version number ""
,I/chromium( 3537): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3537): Initializing chromium process, singleProcess=true
,W/art     ( 3537): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3537): ApplicationContext is null in ApplicationStatus
,W/chromium( 3537): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3537): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3537): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3537): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3537): Starting up...
,W/AudioManagerAndroid( 3537): Requires BLUETOOTH permission
,I/ActivityManager(  734): Killing 2637:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10045/pid_2637/cgroup.procs: No such file or directory
,V/MusicLeanback( 2836): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1686): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1686): onCreate
,D/SystemUpdateService( 1686): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1686): active receiver: enabled
,I/SystemUpdateService( 1686): showing system update notification
,I/iu.Environment( 1686): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1686): num queued entries: 0
I/iu.UploadsManager( 1686): num updated entries: 0
I/iu.SyncManager( 1686): NEXT; no task
,I/ValidateNoPeople(  734): skipping global notification
,V/SystemUpdateService( 1686): retry (wakeup: false) in 3599969 ms
,D/SystemUpdateService( 1686): onDestroy
,I/Babel   ( 2021): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  734): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3388): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3388): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3388): BLE supported!!
I/jxcore-log( 3388): 
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  734): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2836): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2836): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1686): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1686): onCreate
,D/SystemUpdateService( 1686): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1686): active receiver: enabled
I/SystemUpdateService( 1686): showing system update notification
,E/GpsLocationProvider(  734): No APN found to select.
,I/ValidateNoPeople(  734): skipping global notification
,V/SystemUpdateService( 1686): retry (wakeup: false) in 3599981 ms
,D/SystemUpdateService( 1686): onDestroy
,I/art     (  734): Explicit concurrent mark sweep GC freed 44289(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.210ms total 131.302ms
,D/Finsky  ( 2716): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2716): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1660): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1660): Vacuum at: now=1450833999276 tag=VacuumService
,I/PhenotypeConfigurator( 1660): Scheduling Phenotype for one-off execution 3558 seconds from now (1450833999609)
,D/GetConfigurationSnapshotOperation( 1660): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1660): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1660): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1660): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1660): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1085): run()
I/Keyboard.Facilitator( 1085): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1660): disconnect managed GoogleApiClient
,I/ActivityManager(  734): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3738 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3738): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3738):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3738):   adb logcat -s GAv4
,W/GAv4    ( 3738): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3738): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3738): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  734): Killing 2815:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10003/pid_2815/cgroup.procs: No such file or directory
,I/jxcore-log( 3388): Connected to the server!
I/jxcore-log( 3388): 
,I/chromium( 3388): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3388): --- start :testSendData2.js---
I/jxcore-log( 3388): 
,E/jxcore  ( 3388): Error!: self.tests[testData.testName] is not a constructor
E/jxcore  ( 3388): Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"146","_columnNumber":"24","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:146:24"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"254","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:254:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"212","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:212:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"301","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:301:3"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"}]
I/chromium( 3388): [INFO:CONSOLE(63)] "logCallback --- start :testSendData2.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3388): Connected to the server!
I/jxcore-log( 3388): 
,I/chromium( 3388): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3388): teardown
I/jxcore-log( 3388): 
,E/jxcore  ( 3388): Error!: self.currentTest is undefined
E/jxcore  ( 3388): Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"159","_columnNumber":"5","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:159:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"254","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:254:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"212","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:212:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"301","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:301:3"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:134:7"}]
I/chromium( 3388): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager(  734): Killing 2791:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  734): Client connection lost with reason: 4
,W/libprocessgroup(  734): failed to open /acct/uid_1000/pid_2791/cgroup.procs: No such file or directory
,I/jxcore-log( 3388): Connected to the server!
I/jxcore-log( 3388): 
,I/chromium( 3388): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-smp  ( 2190): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2190): Plain text(LSB ~ MSB) = 31 b9 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2190): Encrypted text(LSB ~ MSB) = 45 44 e0 8d 33 2a 0d 28 3d 6e e0 8c 97 6c cb 8a 
,W/bt-btm  ( 2190): Stopping oneshot timer
,I/ActivityManager(  734): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3783 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 3783): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3783): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3783): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 3783): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3783): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 3783): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 3829): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads303221320.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads303221320.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3829): dex2oat took 39.166ms (threads: 4)
,W/InstanceID/Rpc( 3783): Found 10008
,I/ActivityManager(  734): Killing 2659:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10070/pid_2659/cgroup.procs: No such file or directory
,I/UsageStatsService(  734): User[0] Flushing usage stats to disk
,I/ProcessStatsService(  734): Prepared write state in 43ms
,I/ProcessStatsService(  734): Prepared write state in 8ms
,W/bt-smp  ( 2190): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2190): Plain text(LSB ~ MSB) = c9 78 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2190): Encrypted text(LSB ~ MSB) = 9d e7 fb 59 c3 a7 ef f8 a5 99 20 de 8f 48 a2 b4 
W/bt-btm  ( 2190): Stopping oneshot timer
,I/EventLogService( 1686): Aggregate from 1450833436207 (log), 1450833436207 (data)
,I/ActivityManager(  734): Killing 2092:com.google.android.calendar/u0a31 (adj 15): empty for 1819s
,W/libprocessgroup(  734): failed to open /acct/uid_10031/pid_2092/cgroup.procs: No such file or directory
,V/GLSActivity( 1660): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1660): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  734): Killing 3152:com.android.defcontainer/u0a5 (adj 13): empty for 1807s
,I/ActivityManager(  734): Killing 2907:com.android.providers.calendar/u0a2 (adj 13): empty for 1808s
,I/ActivityManager(  734): Killing 3306:com.google.android.apps.docs/u0a40 (adj 13): empty for 1809s
,I/ActivityManager(  734): Killing 3200:com.google.android.gms:car/u0a8 (adj 13): empty for 1808s
,I/ActivityManager(  734): Killing 3264:com.android.musicfx/u0a15 (adj 15): empty for 1809s
,I/ActivityManager(  734): Killing 1493:com.google.android.partnersetup/u0a13 (adj 15): empty for 1810s
,W/libprocessgroup(  734): failed to open /acct/uid_10005/pid_3152/cgroup.procs: No such file or directory
,W/libprocessgroup(  734): failed to open /acct/uid_10002/pid_2907/cgroup.procs: No such file or directory
,W/libprocessgroup(  734): failed to open /acct/uid_10040/pid_3306/cgroup.procs: No such file or directory
,W/libprocessgroup(  734): failed to open /acct/uid_10008/pid_3200/cgroup.procs: No such file or directory
,W/libprocessgroup(  734): failed to open /acct/uid_10015/pid_3264/cgroup.procs: No such file or directory
,W/libprocessgroup(  734): failed to open /acct/uid_10013/pid_1493/cgroup.procs: No such file or directory
,TIME-OUT KILL (timeout was 1800000ms)
```
