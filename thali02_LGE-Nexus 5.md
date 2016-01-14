#### Test 55613145b105d0b_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3219): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3219):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3219):   adb logcat -s GAv4
W/GAv4    ( 3219): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3219): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3219): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3219): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2697): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3219): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3219): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 2697): [270] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1654): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/JNIHelp ( 3219): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3219): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3219): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1654): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1684): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1684): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1684): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/ActivityManager(  761): Killing 2136:com.google.android.deskclock/u0a38 (adj 15): empty #17
I/Icing   ( 1684): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
W/libprocessgroup(  761): failed to open /acct/uid_10038/pid_2136/cgroup.procs: No such file or directory
,D/AndroidRuntime( 3290): 
D/AndroidRuntime( 3290): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3290): CheckJNI is OFF
D/AndroidRuntime( 3290): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3311 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3290): Shutting down VM
V/ActivityManager(  761): Display changed displayId=0
I/ActivityManager(  761): Killing 2654:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/libprocessgroup(  761): failed to open /acct/uid_10069/pid_2654/cgroup.procs: No such file or directory
I/WebViewFactory( 3311): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3311): Time to load native libraries: 1 ms (timestamps 9482-9483)
I/LibraryLoader( 3311): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3311): Binding Chromium to main looper Looper (main, tid 1) {221756ae}
I/LibraryLoader( 3311): Expected native library version number "",actual native library version number ""
I/chromium( 3311): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3311): Initializing chromium process, singleProcess=true
W/art     ( 3311): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3311): ApplicationContext is null in ApplicationStatus
,W/chromium( 3311): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3311): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3311): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3311): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@50e2a9b:true
,W/art     ( 3311): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3311): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3311): CordovaWebView is running on device made by: LGE
,W/art     ( 3311): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3311): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3311): Render dirty regions requested: true
,D/Atlas   ( 3311): Validating map...
,W/chromium( 3311): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3311): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3311): Enabling debug mode 0
,I/Keyboard.Facilitator( 1093): onFinishInput()
,W/IInputConnectionWrapper( 3311): showStatusIcon on inactive InputConnection
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +405ms (total +57s981ms)
,W/BindingManager( 3311): Cannot call determinedVisibility() - never saw a connection for the pid: 3311
,D/JsMessageQueue( 3311): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3311): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,D/JX-Cordova( 3311): jxcore cordova android initializing
,D/CAR.SERVICE( 3113): mConnectedToCar = false, abort
,E/ActivityThread( 3113): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@35f0b517 that was originally bound here
E/ActivityThread( 3113): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@35f0b517 that was originally bound here
E/ActivityThread( 3113): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3113): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3113): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3113): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3113): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3113): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3113): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3113): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3113): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3113): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3113): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3113): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3113): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3113): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3113): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3113): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3113): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3113): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3113): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3113): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3113): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3113): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3113): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3113): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1da616e that was originally bound here
E/ActivityThread( 3113): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1da616e that was originally bound here
E/ActivityThread( 3113): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3113): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3113): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3113): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3113): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3113): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3113): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3113): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3113): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3113): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3113): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3113): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3113): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3113): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3113): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3113): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3113): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3113): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3113): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3113): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3113): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3113): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  761): Unbind failed: could not find connection for android.os.BinderProxy@cd80014
W/jxcore-log( 3311): Initializing JXcore engine
W/jxcore-log( 3311): JXcore engine is ready
,W/jxcore-log( 3311): Starting JXcore engine
,W/.test.thalitest( 3311): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8021]" dev="sockfs" ino=8021 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3311): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 3311): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8497]" dev="sockfs" ino=8497 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3311): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20632]" dev="sockfs" ino=20632 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3311): Platform android
W/jxcore-log( 3311): 
W/jxcore-log( 3311): Process ARCH arm
W/jxcore-log( 3311): 
,I/jxcore-log( 3311): JXcore Cordova bridge is ready!
I/jxcore-log( 3311): 
,W/jxcore-log( 3311): JXcore engine is started
,I/Choreographer( 3311): Skipped 120 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3311): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3311): Toggling radios to true
I/jxcore-log( 3311): 
,D/BluetoothAdapter( 3311): enable(): BT is already enabled..!
,D/WifiService(  761): New client listening to asynchronous messages
,D/WifiService(  761): setWifiEnabled: true pid=3311, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3311): Radios toggled,
I/jxcore-log( 3311): 
I/jxcore-log( 3311): My device name is: LGE-Nexus 5
I/jxcore-log( 3311): 
,I/wpa_supplicant(  991): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  761): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiStateMachine(  761): Start Disconnecting Watchdog 1
,V/NativeCrypto( 1654): Read error: ssl=0xaff8ec00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1654): SSL shutdown failed: ssl=0xaff8ec00: I/O error during system call, Broken pipe
,I/wpa_supplicant(  991): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=-13ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-13ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,E/native  (  761): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1248): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1684): CM callback handler got msg 524292
,D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  991): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  991): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  991): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  991): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  761): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
E/WifiStateMachine(  761): Start Dhcp Watchdog 2
,E/native  (  761): do suspend false
,E/WifiStateMachine(  761): scanCount==0 - aborting
,I/dhcpcd  ( 3421): version 5.5.6 starting
E/dhcpcd  ( 3421): get_duid: Read-only file system
,I/dhcpcd  ( 3421): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3421): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3421): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,D/Tethering(  761): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2813): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1684): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1684): onCreate
,D/SystemUpdateService( 1684): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1684): active receiver: enabled
,E/GpsLocationProvider(  761): No APN found to select.
,I/iu.Environment( 1684): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1684): num queued entries: 0
,I/iu.UploadsManager( 1684): num updated entries: 0
I/iu.SyncManager( 1684): NEXT; no task
,I/SystemUpdateService( 1684): showing system update notification
,E/GpsLocationProvider(  761): No APN found to select.
,I/Babel   ( 1985): connection state changed from CONNECTED to DISCONNECTED
I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1684): retry (wakeup: false) in 3599978 ms
,E/native  (  761): do suspend true
,I/ActivityManager(  761): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3463 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  761): Adding iface wlan0 to network 101
,E/WifiStateMachine(  761): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  761): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  761): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  761): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  761): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  761): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/SystemUpdateService( 1684): onDestroy
,D/CSLegacyTypeTracker(  761): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1684): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 14 Jan 2016 09:32:03 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452763923725], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452763923712]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Validated
D/ConnectivityService(  761): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1684): CM callback handler got msg 524290
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1248): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
,I/GAv4    ( 3463): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3463):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3463):   adb logcat -s GAv4
,W/GAv4    ( 3463): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3463): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3463): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3463): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3463): Time to load native libraries: 2 ms (timestamps 5689-5691)
,I/LibraryLoader( 3463): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3463): Binding Chromium to main looper Looper (main, tid 1) {1b6b3570}
,I/LibraryLoader( 3463): Expected native library version number "",actual native library version number ""
,I/chromium( 3463): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3463): Initializing chromium process, singleProcess=true
,W/art     ( 3463): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3463): ApplicationContext is null in ApplicationStatus
,W/chromium( 3463): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3463): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3463): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3463): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3463): Requires BLUETOOTH permission
,I/NSApplication( 3463): Starting up...
,I/ActivityManager(  761): Killing 2603:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_2603/cgroup.procs: No such file or directory
,V/MusicLeanback( 2813): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1684): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1684): onCreate
,D/SystemUpdateService( 1684): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1684): active receiver: enabled
,I/SystemUpdateService( 1684): showing system update notification
,I/iu.Environment( 1684): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1684): num queued entries: 0
I/iu.UploadsManager( 1684): num updated entries: 0
I/iu.SyncManager( 1684): NEXT; no task
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1684): retry (wakeup: false) in 3599979 ms
,D/SystemUpdateService( 1684): onDestroy
,I/Babel   ( 1985): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  761): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2813): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2813): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/jxcore-log( 3311): Test app app.js loaded
I/jxcore-log( 3311): 
,I/chromium( 3311): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/art     (  761): Explicit concurrent mark sweep GC freed 45254(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 982us total 70.147ms
,E/GpsLocationProvider(  761): No APN found to select.
,I/SystemUpdateService( 1684): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1684): onCreate
,D/SystemUpdateService( 1684): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1684): active receiver: enabled
,I/SystemUpdateService( 1684): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1684): retry (wakeup: false) in 3599987 ms
,D/SystemUpdateService( 1684): onDestroy
,D/Finsky  ( 2697): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2697): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1654): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1654): Vacuum at: now=1452763944682 tag=VacuumService
,I/PhenotypeConfigurator( 1654): Scheduling Phenotype for one-off execution 13827 seconds from now (1452763945045)
,D/GetConfigurationSnapshotOperation( 1654): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1654): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1654): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1654): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1654): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1093): run()
I/Keyboard.Facilitator( 1093): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1654): disconnect managed GoogleApiClient
,I/jxcore-log( 3311): --= Surplus to requirements =--
I/jxcore-log( 3311): 
I/jxcore-log( 3311): ****TEST TOOK:  ms ****
I/jxcore-log( 3311): 
I/jxcore-log( 3311): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3311): 
,D/AndroidRuntime( 3637): 
D/AndroidRuntime( 3637): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3637): CheckJNI is OFF
,D/AndroidRuntime( 3637): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 3311:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  761): WIN DEATH: Window{328af08b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  761): Client connection lost with reason: 4
,W/PackageSettings(  761): Skipping PackageSetting{2dffd262 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  761):   Force finishing activity ActivityRecord{182fbc87 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  761): Spurious death for ProcessRecord{1e79720f 3311:com.test.thalitest/u0a270}, curProc for 3311: null
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  761):   Force finishing activity ActivityRecord{182fbc87 u0 com.test.thalitest/.MainActivity t216 f}
W/ActivityManager(  761): Duplicate finish request for ActivityRecord{182fbc87 u0 com.test.thalitest/.MainActivity t216 f}
,I/art     ( 1684): Explicit concurrent mark sweep GC freed 8839(427KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/30MB, paused 446us total 30.082ms
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1654): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1093): resetDictionaries() : en_US
,D/NetworkChangeNotifierAutoDetect(  949): Network connectivity changed, type is: 2
,I/Keyboard.Facilitator.DecoderInitializer( 1093): run()
,I/LibraryLoader( 1522): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
,I/art     ( 1402): Explicit concurrent mark sweep GC freed 441(29KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 727us total 105.768ms
,I/art     ( 1309): Explicit concurrent mark sweep GC freed 3948(293KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 1.362ms total 73.679ms
,I/Decoder ( 1093): createOrResetDecoder
,D/VoicemailCleanupService( 1374): Cleaning up data for package: com.test.thalitest
,I/art     (  761): Explicit concurrent mark sweep GC freed 23848(1334KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.217ms total 109.422ms
I/art     (  761): WaitForGcToComplete blocked for 29.822ms for cause Explicit
I/UpdateIcingCorporaServi( 1402): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1309): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@18ed1c4f new=com.google.android.velvet.VelvetApplication@18ed1c4f
,I/OpenGLRenderer(  949): Initialized EGL, version 1.4
,D/OpenGLRenderer(  949): Enabling debug mode 0
,I/LibraryLoader( 1522): Time to load native libraries: 68 ms (timestamps 8801-8869)
I/LibraryLoader( 1522): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
,I/chromium( 1522): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 1522): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1522): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3677 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,W/art     (  949): Attempt to remove local handle scope entry from IRT, ignoring
,D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1093): run()
,D/TaskPersister(  761): removeObsoleteFile: deleting file=216_task.xml
,W/InputMethodManagerService(  761): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@190ea619 (uid=10034 pid=949)
,I/art     (  761): Explicit concurrent mark sweep GC freed 4936(271KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.448ms total 135.696ms
,W/ContextImpl( 3677): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1093): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1093): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1093): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1093): run()
I/StatsUtilsManager( 1093): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1093): shouldRecordStats() = Too Soon
,D/PackageBroadcastService( 1684): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1684): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1684): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1684): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1684): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1684): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1654): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1654): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1684): Removing dialog suppression flag for package com.test.thalitest
,W/InputMethodManagerService(  761): Got RemoteException sending setActive(false) notification to pid 3311 uid 10270
,I/Keyboard.Facilitator( 1093): onFinishInput()
,I/ActivityManager(  761): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/ActivityManager(  761): Resuming delayed broadcast
,I/UpdateIcingCorporaServi( 1402): UpdateCorporaTask done [took 253 ms] updated apps [took 253 ms] 
I/ActivityManager(  761): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3717 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,D/gH_CompatibleDatabase( 1684): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1684): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1684): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1684): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1684): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1684): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1684): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1684): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1684): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1684): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1684): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1684): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1684): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/AndroidRuntime( 3637): Shutting down VM
,I/ActivityManager(  761): Killing 2784:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2784/cgroup.procs: No such file or directory
,I/Launcher( 1309): Deferring update until onResume
,W/BaseAppContext( 1684): Using Auth Proxy for data requests.
I/GMPM-SVC( 1684): App measurement is starting up, version: 8489
I/GMPM-SVC( 1684): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1684): Using Auth Proxy for data requests.
,W/ResourcesManager( 1309): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Icing   ( 1684): doRemovePackageData com.test.thalitest
W/ResourcesManager( 1309): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1309): Deferring update until onResume
,I/ActivityManager(  761): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3742 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 2764:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  761): Client connection lost with reason: 4
,W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2764/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Killing 2625:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2625/cgroup.procs: No such file or directory
,D/ExternalStorage( 3742): After updating volumes, found 1 active roots
,W/ResourcesManager( 3219): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3219): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3717): Update found 7 roots in 212ms
,D/Documents( 3717): Update found 7 roots in 68ms

```
