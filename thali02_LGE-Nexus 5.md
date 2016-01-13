#### Test 558877588826def_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1632): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1632): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3216): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3216):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3216):   adb logcat -s GAv4
W/GAv4    ( 3216): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3216): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3216): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/CAR.SERVICE( 3086): mConnectedToCar = false, abort
--------- beginning of system
E/ActivityThread( 3086): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2786ab33 that was originally bound here
E/ActivityThread( 3086): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2786ab33 that was originally bound here
E/ActivityThread( 3086): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3086): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3086): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3086): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3086): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3086): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3086): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3086): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3086): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3086): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3086): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3086): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3086): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3086): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3086): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3086): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3086): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3086): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3086): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3086): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3086): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3086): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3086): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/ActivityThread( 3086): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@5f43fa that was originally bound here
E/ActivityThread( 3086): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@5f43fa that was originally bound here
E/ActivityThread( 3086): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3086): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3086): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3086): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3086): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3086): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3086): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3086): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3086): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3086): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3086): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3086): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3086): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3086): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3086): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3086): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3086): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3086): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3086): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3086): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3086): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3086): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  735): Unbind failed: could not find connection for android.os.BinderProxy@12f51e36
W/AnalyticsTrackerProxyImpl( 3216): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2640): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  735): Killing 2098:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/ResourcesManager( 3216): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3216): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  735): failed to open /acct/uid_10038/pid_2098/cgroup.procs: No such file or directory
V/JNIHelp ( 3216): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3216): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3216): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1632): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1632): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1632): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1632): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/ActivityManager(  735): Killing 2612:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10069/pid_2612/cgroup.procs: No such file or directory
D/AndroidRuntime( 3291): 
D/AndroidRuntime( 3291): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3291): CheckJNI is OFF
D/AndroidRuntime( 3291): Calling main entry com.android.commands.am.Am
I/ActivityManager(  735): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  735): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3314 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3291): Shutting down VM
V/ActivityManager(  735): Display changed displayId=0
I/WebViewFactory( 3314): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3314): Time to load native libraries: 1 ms (timestamps 8731-8732)
I/LibraryLoader( 3314): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3314): Binding Chromium to main looper Looper (main, tid 1) {3afccd3a}
I/LibraryLoader( 3314): Expected native library version number "",actual native library version number ""
I/chromium( 3314): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3314): Initializing chromium process, singleProcess=true
W/art     ( 3314): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3314): ApplicationContext is null in ApplicationStatus
,W/chromium( 3314): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3314): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3314): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3314): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36693435:true
,W/art     ( 3314): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3314): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3314): CordovaWebView is running on device made by: LGE
,W/art     ( 3314): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3314): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3314): Render dirty regions requested: true
,D/Atlas   ( 3314): Validating map...
,W/chromium( 3314): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3314): Initialized EGL, version 1.4
D/OpenGLRenderer( 3314): Enabling debug mode 0
,I/Keyboard.Facilitator( 1087): onFinishInput()
,I/ActivityManager(  735): Displayed com.test.thalitest/.MainActivity: +457ms (total +58s703ms)
,W/IInputConnectionWrapper( 3314): showStatusIcon on inactive InputConnection
,W/BindingManager( 3314): Cannot call determinedVisibility() - never saw a connection for the pid: 3314
,D/JsMessageQueue( 3314): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3314): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257343360
D/JX-Cordova( 3314): jxcore cordova android initializing
,W/jxcore-log( 3314): Initializing JXcore engine
W/jxcore-log( 3314): JXcore engine is ready
,W/jxcore-log( 3314): Starting JXcore engine
,W/.test.thalitest( 3314): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9490]" dev="sockfs" ino=9490 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3314): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3314): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9532]" dev="sockfs" ino=9532 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3314): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20627]" dev="sockfs" ino=20627 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3314): Platform android
W/jxcore-log( 3314): 
,W/jxcore-log( 3314): Process ARCH arm
W/jxcore-log( 3314): 
,I/jxcore-log( 3314): JXcore Cordova bridge is ready!
I/jxcore-log( 3314): 
W/jxcore-log( 3314): JXcore engine is started
I/Choreographer( 3314): Skipped 113 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3314): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3314): Toggling radios to true
I/jxcore-log( 3314): 
,D/BluetoothAdapter( 3314): enable(): BT is already enabled..!
,D/WifiService(  735): New client listening to asynchronous messages
,D/WifiService(  735): setWifiEnabled: true pid=3314, uid=10270
E/WifiService(  735): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3314): Radios toggled
I/jxcore-log( 3314): 
I/wpa_supplicant(  983): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
I/jxcore-log( 3314): My device name is: LGE-Nexus 5
I/jxcore-log( 3314): 
,E/WifiStateMachine(  735): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  735): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1602): Read error: ssl=0xa4230200: I/O error during system call, Connection timed out
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,V/NativeCrypto( 1602): SSL shutdown failed: ssl=0xa4230200: I/O error during system call, Broken pipe
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  735): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): ValidatedState{ when=-8ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-8ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,E/WifiStateMachine(  735): Start Disconnecting Watchdog 1
,E/native  (  735): do suspend true
,W/EventLoggerService( 1340): Unable to send logs Read error: ssl=0xa43e0e00: I/O error during system call, Connection timed out
,I/wpa_supplicant(  983): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/CommandListener(  180): Clearing all IP addresses on wlan0
D/ConnectivityService(  735): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  735): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  735): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler( 1632): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Disconnected - quitting
,D/ConnectivityService(  735): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1235): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  735): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiNetworkAgent(  735): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  983): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  983): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  983): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  983): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  735): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
E/WifiStateMachine(  735): Start Dhcp Watchdog 2
,E/native  (  735): do suspend false
,E/WifiStateMachine(  735): scanCount==0 - aborting
,I/dhcpcd  ( 3392): version 5.5.6 starting
,E/dhcpcd  ( 3392): get_duid: Read-only file system
,I/dhcpcd  ( 3392): wlan0: rebinding lease of 192.168.1.114
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2779): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1632): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1632): onCreate
,D/SystemUpdateService( 1632): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1632): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1632): num queued entries: 0
I/iu.UploadsManager( 1632): num updated entries: 0
I/iu.SyncManager( 1632): NEXT; no task
,I/SystemUpdateService( 1632): active receiver: enabled
,I/ActivityManager(  735): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3409 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SystemUpdateService( 1632): showing system update notification
,I/Babel   ( 1940): connection state changed from CONNECTED to DISCONNECTED
,E/GpsLocationProvider(  735): No APN found to select.
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1632): retry (wakeup: false) in 3599935 ms
,D/SystemUpdateService( 1632): onDestroy
,E/GpsLocationProvider(  735): No APN found to select.
,I/dhcpcd  ( 3392): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/GAv4    ( 3409): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3409):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3409):   adb logcat -s GAv4
,I/dhcpcd  ( 3392): wlan0: leased 192.168.1.114 for 86400 seconds
,W/GAv4    ( 3409): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3409): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3409): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3409): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3409): Time to load native libraries: 1 ms (timestamps 4800-4801)
I/LibraryLoader( 3409): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3409): Binding Chromium to main looper Looper (main, tid 1) {16dba6ee}
I/LibraryLoader( 3409): Expected native library version number "",actual native library version number ""
I/chromium( 3409): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3409): Initializing chromium process, singleProcess=true
,W/art     ( 3409): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3409): ApplicationContext is null in ApplicationStatus
,W/chromium( 3409): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3409): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3409): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3409): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3409): Requires BLUETOOTH permission
,E/native  (  735): do suspend true
,I/NSApplication( 3409): Starting up...
,I/ActivityManager(  735): Killing 2567:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10045/pid_2567/cgroup.procs: No such file or directory
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  735): Adding iface wlan0 to network 101
,E/WifiStateMachine(  735): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  735): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  735): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  735): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  735): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  735): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  735): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  735): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/CSLegacyTypeTracker(  735): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  735): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1632): CM callback handler got msg 524290
,V/MusicLeanback( 2779): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1632): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1632): onCreate
,D/SystemUpdateService( 1632): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1632): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1632): num queued entries: 0
I/iu.UploadsManager( 1632): num updated entries: 0
,I/iu.SyncManager( 1632): NEXT; no task
,I/SystemUpdateService( 1632): active receiver: enabled
,I/SystemUpdateService( 1632): showing system update notification
,I/ValidateNoPeople(  735): skipping global notification
V/SystemUpdateService( 1632): retry (wakeup: false) in 3599980 ms
,D/SystemUpdateService( 1632): onDestroy
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 13 Jan 2016 12:37:36 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452688656439], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452688656422]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Validated
D/ConnectivityService(  735): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/TelephonyNetworkFactory( 1235): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1632): CM callback handler got msg 524290
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/Babel   ( 1940): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  735): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3314): Test app app.js loaded
I/jxcore-log( 3314): 
,I/Choreographer( 3314): Skipped 376 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3314): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2779): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2779): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1632): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1632): onCreate
D/SystemUpdateService( 1632): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1632): active receiver: enabled
,I/SystemUpdateService( 1632): showing system update notification
,I/ValidateNoPeople(  735): skipping global notification
V/SystemUpdateService( 1632): retry (wakeup: false) in 3599986 ms
D/SystemUpdateService( 1632): onDestroy
,I/art     (  735): Explicit concurrent mark sweep GC freed 44593(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.152ms total 77.933ms
,E/GpsLocationProvider(  735): No APN found to select.
,D/Finsky  ( 2640): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2640): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1602): Vacuum at: now=1452688673911 tag=VacuumService
,I/PhenotypeConfigurator( 1602): Scheduling Phenotype for one-off execution 880 seconds from now (1452688674294)
,D/GetConfigurationSnapshotOperation( 1602): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1602): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1602): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1087): run()
I/Keyboard.Facilitator( 1087): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1602): disconnect managed GoogleApiClient
,I/jxcore-log( 3314): --= Surplus to requirements =--
I/jxcore-log( 3314): 
I/jxcore-log( 3314): ****TEST TOOK:  ms ****
I/jxcore-log( 3314): 
I/jxcore-log( 3314): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3314): 
,D/AndroidRuntime( 3610): 
D/AndroidRuntime( 3610): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3610): CheckJNI is OFF
,D/AndroidRuntime( 3610): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  735): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  735): Killing 3314:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  735): WIN DEATH: Window{355094a5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  735): Client connection lost with reason: 4
,I/ActivityManager(  735):   Force finishing activity ActivityRecord{1b6ea341 u0 com.test.thalitest/.MainActivity t216}
,W/PackageSettings(  735): Skipping PackageSetting{2984782e com.example.hello/10278} due to missing metadata
,W/ActivityManager(  735): Spurious death for ProcessRecord{110ef789 3314:com.test.thalitest/u0a270}, curProc for 3314: null
,I/ActivityManager(  735): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1632): Explicit concurrent mark sweep GC freed 10659(515KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/30MB, paused 453us total 28.612ms
,I/art     ( 1340): Explicit concurrent mark sweep GC freed 12316(944KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 364us total 30.710ms
,W/GeofencerStateMachine( 1602): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  735): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1087): resetDictionaries() : en_US
,I/art     ( 1286): Explicit concurrent mark sweep GC freed 4005(296KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 7.764ms total 49.031ms
,I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  944): Initialized EGL, version 1.4
,I/Keyboard.Facilitator.DecoderInitializer( 1087): run()
,I/Decoder ( 1087): createOrResetDecoder
D/OpenGLRenderer(  944): Enabling debug mode 0
,D/VoicemailCleanupService( 1354): Cleaning up data for package: com.test.thalitest
,I/UpdateIcingCorporaServi( 1340): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1286): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@19073deb new=com.google.android.velvet.VelvetApplication@19073deb
,W/InputMethodManagerService(  735): Got RemoteException sending setActive(false) notification to pid 3314 uid 10270
I/art     (  735): Explicit concurrent mark sweep GC freed 24065(1359KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.672ms total 99.622ms
I/art     (  735): WaitForGcToComplete blocked for 38.194ms for cause Explicit
,I/Keyboard.Facilitator( 1087): onFinishInput()
,I/ActivityManager(  735): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3650 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1087): run()
,W/ContextImpl( 3650): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/UpdateIcingCorporaServi( 1340): UpdateCorporaTask done [took 109 ms] updated apps [took 109 ms] 
,D/PackageBroadcastService( 1632): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1632): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1632): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1632): Module APK com.google.android.play.games already loaded
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1087): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Loading LM = contacts
D/BackupManagerService(  735): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  735): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1087): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1087): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1087): run()
I/StatsUtilsManager( 1087): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1087): shouldRecordStats() = Too Soon
,I/ActivityManager(  735): Killing 2752:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
D/ChimeraCfgMgr( 1632): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1632): Module APK com.google.android.play.games already loaded
,I/art     (  735): Explicit concurrent mark sweep GC freed 6187(284KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.303ms total 135.844ms
,I/Keyboard.Facilitator( 1087): onFinishInput()
,W/IInputConnectionWrapper( 1286): showStatusIcon on inactive InputConnection
,W/libprocessgroup(  735): failed to open /acct/uid_10003/pid_2752/cgroup.procs: No such file or directory
,I/LocationSettingsChecker( 1632): Removing dialog suppression flag for package com.test.thalitest
,I/Launcher( 1286): Deferring update until onResume
,E/NetworkScheduler.SchedulerReceiver( 1602): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1602): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/TaskPersister(  735): removeObsoleteFile: deleting file=216_task.xml
,D/AndroidRuntime( 3610): Shutting down VM
,D/gH_CompatibleDatabase( 1632): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1632): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1632): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1632): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/ResourcesManager( 1286): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1632): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1632): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1632): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1632): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1632): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,W/ResourcesManager( 1286): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1632): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1632): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1632): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1632): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/Launcher( 1286): Deferring update until onResume
,I/ActivityManager(  735): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3684 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,W/BaseAppContext( 1632): Using Auth Proxy for data requests.
,W/BaseAppContext( 1632): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1632): App measurement is starting up, version: 8489
,I/GMPM-SVC( 1632): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/Icing   ( 1632): doRemovePackageData com.test.thalitest
,I/ActivityManager(  735): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3707 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  735): Killing 2728:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  735): Client connection lost with reason: 4
,W/libprocessgroup(  735): failed to open /acct/uid_1000/pid_2728/cgroup.procs: No such file or directory
,I/ActivityManager(  735): Killing 2586:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10070/pid_2586/cgroup.procs: No such file or directory
,D/ExternalStorage( 3707): After updating volumes, found 1 active roots
,W/ResourcesManager( 3216): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3216): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3684): Update found 7 roots in 263ms

```
