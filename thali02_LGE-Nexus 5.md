#### Test 55311151a2306df_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3126): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3126):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3126):   adb logcat -s GAv4
W/GAv4    ( 3126): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3126): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3126): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3126): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
--------- beginning of system
W/ResourcesManager( 3126): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3126): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 2639): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  735): Killing 2096:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 3126): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3126): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3126): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  735): failed to open /acct/uid_10038/pid_2096/cgroup.procs: No such file or directory
V/GLSActivity( 1612): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1649): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1649): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1649): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1649): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3191): 
D/AndroidRuntime( 3191): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3191): CheckJNI is OFF
I/ActivityManager(  735): Killing 2603:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
D/AndroidRuntime( 3191): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  735): failed to open /acct/uid_10069/pid_2603/cgroup.procs: No such file or directory
I/ActivityManager(  735): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  735): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3215 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3191): Shutting down VM
I/art     (  196): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 190us total 8.769ms
I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.530ms
V/ActivityManager(  735): Display changed displayId=0
I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 166us total 8.436ms
D/CAR.SERVICE( 3025): mConnectedToCar = false, abort
E/ActivityThread( 3025): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@c5db767 that was originally bound here
E/ActivityThread( 3025): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@c5db767 that was originally bound here
E/ActivityThread( 3025): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3025): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3025): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3025): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3025): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3025): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3025): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3025): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3025): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3025): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3025): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3025): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3025): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3025): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3025): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3025): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3025): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3025): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3025): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3025): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3025): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3025): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3025): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/ActivityThread( 3025): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@344b5cfe that was originally bound here
E/ActivityThread( 3025): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@344b5cfe that was originally bound here
E/ActivityThread( 3025): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3025): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3025): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3025): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3025): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3025): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3025): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3025): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3025): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3025): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3025): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3025): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3025): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3025): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3025): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3025): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3025): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3025): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3025): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3025): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3025): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3025): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  735): Unbind failed: could not find connection for android.os.BinderProxy@2a76a5d0
I/WebViewFactory( 3215): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3215): Time to load native libraries: 2 ms (timestamps 6949-6951)
I/LibraryLoader( 3215): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3215): Binding Chromium to main looper Looper (main, tid 1) {31ea423e}
,I/LibraryLoader( 3215): Expected native library version number "",actual native library version number ""
,I/chromium( 3215): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3215): Initializing chromium process, singleProcess=true
,W/art     ( 3215): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3215): ApplicationContext is null in ApplicationStatus
,W/chromium( 3215): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3215): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3215): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3215): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  735): Message: 20
,D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3dfb93a6:true
,W/art     ( 3215): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3215): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3215): CordovaWebView is running on device made by: LGE
,W/art     ( 3215): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3215): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3215): Render dirty regions requested: true
,D/Atlas   ( 3215): Validating map...
,W/chromium( 3215): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3215): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3215): Enabling debug mode 0
,I/ActivityManager(  735): Displayed com.test.thalitest/.MainActivity: +493ms (total +56s972ms)
,W/IInputConnectionWrapper( 3215): showStatusIcon on inactive InputConnection
,W/BindingManager( 3215): Cannot call determinedVisibility() - never saw a connection for the pid: 3215
,D/JsMessageQueue( 3215): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3215): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258381056
D/JX-Cordova( 3215): jxcore cordova android initializing
,W/jxcore-log( 3215): Initializing JXcore engine
W/jxcore-log( 3215): JXcore engine is ready
,W/jxcore-log( 3215): Starting JXcore engine
,W/.test.thalitest( 3215): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8054]" dev="sockfs" ino=8054 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3215): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3215): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8121]" dev="sockfs" ino=8121 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3215): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20521]" dev="sockfs" ino=20521 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3215): Platform android
W/jxcore-log( 3215): 
,W/jxcore-log( 3215): Process ARCH arm
W/jxcore-log( 3215): 
,I/jxcore-log( 3215): JXcore Cordova bridge is ready!
I/jxcore-log( 3215): 
W/jxcore-log( 3215): JXcore engine is started
,I/Choreographer( 3215): Skipped 111 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3215): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3215): Toggling radios to true
I/jxcore-log( 3215): 
,D/BluetoothAdapter( 3215): enable(): BT is already enabled..!
,D/WifiService(  735): New client listening to asynchronous messages
,D/WifiService(  735): setWifiEnabled: true pid=3215, uid=10270
E/WifiService(  735): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3215): Radios toggled
I/jxcore-log( 3215): 
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3215): Received device characteristics:
I/jxcore-log( 3215): Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3215): Bluetooth name: Nexus 5
I/jxcore-log( 3215): Device name: LGE-Nexus 5
I/jxcore-log( 3215): 
I/jxcore-log( 3215): Perf Test app loaded loaded
I/jxcore-log( 3215): 
I/wpa_supplicant(  985): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  735): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  735): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,I/chromium( 3215): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/Choreographer( 3215): Skipped 57 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 3215): check test folder
I/jxcore-log( 3215): 
I/jxcore-log( 3215): found test : ./testFindPeers.js
I/jxcore-log( 3215): 
,V/NativeCrypto( 1612): Read error: ssl=0xb3e2ae00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1612): SSL shutdown failed: ssl=0xb3e2ae00: I/O error during system call, Broken pipe
,D/ConnectivityService(  735): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/jxcore-log( 3215): found test : ./testSendData.js
I/jxcore-log( 3215): 
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  735): Start Disconnecting Watchdog 1
I/wpa_supplicant(  985): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  735): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/ConnectivityService(  735): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
D/Nat464Xlat(  735): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  735): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Disconnected - quitting
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1649): CM callback handler got msg 524292
D/ConnectivityService(  735): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1246): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  735): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiNetworkAgent(  735): NetworkAgent: NetworkAgent channel lost
,W/NetworkUtils( 1392): OkHttp exception
W/EventLoggerService( 1392): Unable to send logs Error code: 262146
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1800000, pollInterval: 10000
,I/wpa_supplicant(  985): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  985): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  985): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  985): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  735): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  735): Start Dhcp Watchdog 2
,E/native  (  735): do suspend false
,E/WifiStateMachine(  735): scanCount==0 - aborting
,I/dhcpcd  ( 3335): version 5.5.6 starting
E/dhcpcd  ( 3335): get_duid: Read-only file system
,I/dhcpcd  ( 3335): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3335): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3335): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
D/Tethering(  735): MasterInitialState.processMessage what=3
,E/GpsLocationProvider(  735): No APN found to select.
,V/MusicLeanback( 2747): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  735): No APN found to select.
,I/SystemUpdateService( 1649): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1649): onCreate
,D/SystemUpdateService( 1649): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1649): active receiver: enabled
,I/SystemUpdateService( 1649): showing system update notification
,I/iu.Environment( 1649): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1649): num queued entries: 0
,I/iu.UploadsManager( 1649): num updated entries: 0
I/iu.SyncManager( 1649): NEXT; no task
,I/Babel   ( 1960): connection state changed from CONNECTED to DISCONNECTED
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1649): retry (wakeup: false) in 3599983 ms
,I/ActivityManager(  735): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3393 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/native  (  735): do suspend true
D/SystemUpdateService( 1649): onDestroy
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  735): Adding iface wlan0 to network 101
,E/WifiStateMachine(  735): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  735): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  735): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  735): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  735): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  735): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  735): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  735): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/CSLegacyTypeTracker(  735): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  735): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1649): CM callback handler got msg 524290
,I/GAv4    ( 3393): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3393):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3393):   adb logcat -s GAv4
,W/GAv4    ( 3393): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 07 Jan 2016 08:37:53 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452155873657], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452155873639]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Validated
D/ConnectivityService(  735): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1246): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1649): CM callback handler got msg 524290
,W/GAv4    ( 3393): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3393): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3393): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3393): Time to load native libraries: 3 ms (timestamps 4044-4047)
I/LibraryLoader( 3393): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3393): Binding Chromium to main looper Looper (main, tid 1) {5b4280}
,I/LibraryLoader( 3393): Expected native library version number "",actual native library version number ""
I/chromium( 3393): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3393): Initializing chromium process, singleProcess=true
,W/art     ( 3393): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3393): ApplicationContext is null in ApplicationStatus
,W/chromium( 3393): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3393): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3393): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3393): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3393): Requires BLUETOOTH permission
,I/NSApplication( 3393): Starting up...
,I/ActivityManager(  735): Killing 2556:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10045/pid_2556/cgroup.procs: No such file or directory
,V/MusicLeanback( 2747): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1649): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1649): onCreate
,D/SystemUpdateService( 1649): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1649): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1649): active receiver: enabled
,I/iu.UploadsManager( 1649): num queued entries: 0
,I/iu.UploadsManager( 1649): num updated entries: 0
,I/iu.SyncManager( 1649): NEXT; no task
,I/SystemUpdateService( 1649): showing system update notification
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1649): retry (wakeup: false) in 3599957 ms
,D/SystemUpdateService( 1649): onDestroy
,I/Babel   ( 1960): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  735): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3215): BLE is supported
I/jxcore-log( 3215): 
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2747): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2747): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1649): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1649): onCreate
,D/SystemUpdateService( 1649): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1649): active receiver: enabled
,I/SystemUpdateService( 1649): showing system update notification
,E/GpsLocationProvider(  735): No APN found to select.
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1649): retry (wakeup: false) in 3599976 ms
,D/SystemUpdateService( 1649): onDestroy
,I/art     (  735): Explicit concurrent mark sweep GC freed 46736(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.160ms total 67.922ms
,D/Finsky  ( 2639): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2639): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1789993, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1779985, pollInterval: 10000
,V/GLSActivity( 1612): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1612): Vacuum at: now=1452155891810 tag=VacuumService
,I/PhenotypeConfigurator( 1612): Scheduling Phenotype for one-off execution 2708 seconds from now (1452155892231)
,D/GetConfigurationSnapshotOperation( 1612): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1612): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1612): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1612): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1612): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1769975, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1759966, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1749958, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1739931, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1729923, pollInterval: 10000
,I/ClearcutLoggerApiImpl( 1612): disconnect managed GoogleApiClient
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1719915, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1709902, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1699889, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1689880, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1679835, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1669826, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1659815, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1649806, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1639791, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1629783, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1619774, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1609763, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1599716, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1589695, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1579686, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1569676, pollInterval: 10000
,I/jxcore-log( 3215): Connected to the server!
I/jxcore-log( 3215): 
,I/chromium( 3215): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1559667, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1549657, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1539649, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1529640, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1519633, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1509623, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1499614, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1489607, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1479600, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1469591, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1459583, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1449574, pollInterval: 10000
,I/jxcore-log( 3215): --- start :testFindPeers.js---
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): testFindPeers created [object Object]
I/jxcore-log( 3215): 
I/jxcore-log( 3215): serverPort is 8876
I/jxcore-log( 3215): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3215): bind: Binding a new listener
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3215): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3215): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3215): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): start: OK
I/io.jxcore.node.ConnectionHelper( 3215): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3215): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3215): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): start: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3215): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3215): start: OK
I/jxcore-log( 3215): StartBroadcasting started ok
I/jxcore-log( 3215): 
I/chromium( 3215): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3215): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3215): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3215): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pManager( 3215): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): Service request added successfully
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): Service discovery started successfully
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1439567, pollInterval: 10000
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1429526, pollInterval: 10000
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): restart: Restarting...
,D/WifiP2pManager( 3215): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): Service request added successfully
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): Service discovery started successfully
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1419517, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1409509, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1399500, pollInterval: 10000
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): setState: RESTARTING
,I/wpa_supplicant(  985): P2P-FIND-STOPPED 
,I/wpa_supplicant(  985): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  985): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  985): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  985): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): P2P device discovery started successfully
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  985): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3215): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): Service request added successfully
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1389492, pollInterval: 10000
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): Service discovery started successfully
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  985): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3215): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 3215): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 G3-1] is available
I/jxcore-log( 3215): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"G3-1","peerAvailable":true}]
I/jxcore-log( 3215): 
I/jxcore-log( 3215): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log( 3215): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 3215): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3215): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
I/jxcore-log( 3215): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"A3-1","peerAvailable":true}]
I/jxcore-log( 3215): 
I/jxcore-log( 3215): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 3215): 
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1379479, pollInterval: 10000
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): restart: Restarting...
,D/WifiP2pManager( 3215): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): Service request added successfully
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1]
I/io.jxcore.node.ConnectionHelper( 3215): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 3215): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 Note4-1] is available
I/jxcore-log( 3215): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"Note4-1","peerAvailable":true}]
I/jxcore-log( 3215): 
I/jxcore-log( 3215): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 3215): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 3215): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3215): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 3215): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3215): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 3215): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3215): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
,I/jxcore-log( 3215): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"G4-1","peerAvailable":true}]
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 3215): 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1369472, pollInterval: 10000
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1359459, pollInterval: 10000
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1349452, pollInterval: 10000
,I/jxcore-log( 3215): timeout now
I/jxcore-log( 3215): 
I/jxcore-log( 3215): weAreDoneNow
I/jxcore-log( 3215): 
I/jxcore-log( 3215): done, now sending data to server
I/jxcore-log( 3215): 
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1339444, pollInterval: 10000
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): setState: RESTARTING
,I/wpa_supplicant(  985): P2P-FIND-STOPPED 
,I/wpa_supplicant(  985): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  985): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  985): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  985): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): Start timer timeout, starting now...
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  985): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3215): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): Service request added successfully
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): Service discovery started successfully
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 3215): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 3215): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1329397, pollInterval: 10000
,I/jxcore-log( 3215): teardown
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): testFindPeers stopped
I/jxcore-log( 3215): 
,I/io.jxcore.node.ConnectionHelper( 3215): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3215): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  985): P2P-FIND-STOPPED 
,I/wpa_supplicant(  985): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  985): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  985): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/wpa_supplicant(  985): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3215): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3215): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3215): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): setState: NOT_STARTED
,I/jxcore-log( 3215): StopBroadcasting went ok
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): --- start :testSendData.js---
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":13}bt-address length : 12
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): daya100000
I/jxcore-log( 3215): 
I/jxcore-log( 3215): check server
I/jxcore-log( 3215): 
I/jxcore-log( 3215): serverPort is 43872
I/jxcore-log( 3215): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3215): bind: Binding a new listener
D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3215): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3215): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3215): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): start: OK
I/io.jxcore.node.ConnectionHelper( 3215): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3215): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3215): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): start: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3215): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3215): start: OK
I/jxcore-log( 3215): StartBroadcasting started ok
I/jxcore-log( 3215): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): Waiting for incoming connections...
,I/jxcore-log( 3215): [ { address: '44:80:EB:7B:5A:05', tryCount: 0 },
I/jxcore-log( 3215):   { address: '58:3F:54:73:64:C0', tryCount: 0 },
I/jxcore-log( 3215):   { address: '08:EC:A9:50:75:41', tryCount: 0 },
I/jxcore-log( 3215):   { address: 'F8:95:C7:87:3C:51', tryCount: 0 },
I/jxcore-log( 3215):   { address: '7C:F9:0E:51:18:22', tryCount: 0 },
I/jxcore-log( 3215):   { address: 'E0:DB:10:14:E2:C0', tryCount: 0 },
I/jxcore-log( 3215):   { address: '7C:F9:0E:37:96:AB', tryCount: 0 },
I/jxcore-log( 3215):   { address: '7C:F9:0E:34:8A:A0', tryCount: 0 },
I/jxcore-log( 3215):   { address: 'B0:C5:59:3F:75:69', tryCount: 0 },
I/jxcore-log( 3215):   { address: '00:F4:6F:30:E0:6C', tryCount: 0 },
I/jxcore-log( 3215):   { address: '90:E7:C4:F6:69:77', tryCount: 0 },
I/jxcore-log( 3215):   { address: '08:EC:A9:50:76:27', tryCount: 0 } ]
I/jxcore-log( 3215): 
I/jxcore-log( 3215): startWithNextDevice
I/jxcore-log( 3215): 
I/jxcore-log( 3215): do fake peer & start
I/jxcore-log( 3215): 
I/jxcore-log( 3215): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:45:46.283Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:45:46.283Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:45:46.283Z SendDataConnector.js: do connect now
I/jxcore-log( 3215): 
I/io.jxcore.node.ConnectionHelper( 3215): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3215): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
W/io.jxcore.node.ConnectionHelper( 3215): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): connect: [44:80:EB:7B:5A:05 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): connect: Trying to start connecting to null in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): onConnecting: null 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): connect: Started connecting to null in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 3215): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
I/jxcore-log( 3215): 2016-01-07T08:45:46.288Z SendDataTCPServer.js: TCP/IP server is bound to port: 43872
I/jxcore-log( 3215): 
I/chromium( 3215): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3215): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3215): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3215): onDiscoveryManagerStateChanged: NOT_STARTED
I/chromium( 3215): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3215): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3215): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): setState: RESTARTING
I/wpa_supplicant(  985): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3215): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 299)
W/BluetoothAdapter( 3215): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): Start timer timeout, starting now...
,I/wpa_supplicant(  985): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,W/bt-sdp  ( 2119): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2119): DISCOVERY_COMP_EVT slot id:6, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2119): invalid rfc slot id: 6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 299)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Maximum number of allowed retries (0) reached, giving up... (thread ID: 299)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Exiting thread (thread ID: 299)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [44:80:EB:7B:5A:05 44:80:EB:7B:5A:05]
,I/jxcore-log( 3215): 2016-01-07T08:45:51.434Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [44:80:EB:7B:5A:05 44:80:EB:7B:5A:05] failed
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:45:51.434Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [44:80:EB:7B:5A:05 44:80:EB:7B:5A:05] failed
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:45:51.435Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3215): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): shutdown (thread ID: 299)
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1319354, pollInterval: 10000
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3215): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): Service request added successfully
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): Service discovery started successfully
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  985): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  985): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,W/bt-btif ( 2119): info:x10
,D/        ( 2119): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2119): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3215): 2016-01-07T08:45:56.436Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:56.440Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3215): 
,I/BluetoothBondStateMachine( 2119): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 2119): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2119): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2119): Entering PendingCommandState State
,W/BluetoothEventManager( 2706): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2706): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 2119): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2119): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2119): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,W/BluetoothEventManager( 2706): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2706): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 2119): StableState(): Entering Off State
,W/bt-btif ( 2119): new conn_srvc id:26, app_id:255
W/bt-btif ( 2119): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): Incoming connection initialized (thread ID: 301)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3215): Entering thread (ID: 301)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): onBytesRead: Read 63 bytes successfully (thread ID: 301)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): Got valid identity from [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): onBytesWritten: 66 bytes successfully written (thread ID: 301)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): removeThreadFromList: Removing thread with ID 301
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): Handshake thread disposed (thread ID: 301)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): onIncomingConnectionConnected: [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3215): Exiting thread (ID: 301)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): onConnected: [08:EC:A9:50:75:41 A3-1]
,I/io.jxcore.node.ConnectionHelper( 3215): onConnected: Incoming connection to peer [08:EC:A9:50:75:41 A3-1],
D/io.jxcore.node.ConnectionHelper( 3215): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 3215): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3215): onConnected: Incoming socket thread, for peer [08:EC:A9:50:75:41 A3-1], created successfully
D/io.jxcore.node.ConnectionHelper( 3215): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3215): Entering thread (ID: 302)
,I/jxcore-log( 3215): 2016-01-07T08:45:57.007Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3215): 
,I/io.jxcore.node.IncomingSocketThread( 3215): Local host address: localhost/127.0.0.1, port: 43872
,D/io.jxcore.node.IncomingSocketThread( 3215): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 3215): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3215): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3215): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3215): Exiting thread (ID: 302)
,D/io.jxcore.node.StreamCopyingThread( 3215): Entering thread (ID: 304, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3215): Entering thread (ID: 303, name: Sender)
,I/jxcore-log( 3215): 2016-01-07T08:45:58.161Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.171Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.238Z SendDataTCPServer.js: TCP/IP server has received 2970 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.251Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.260Z SendDataTCPServer.js: TCP/IP server has received 4950 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.270Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.285Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.296Z SendDataTCPServer.js: TCP/IP server has received 9182 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.305Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.320Z SendDataTCPServer.js: TCP/IP server has received 11162 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.374Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.409Z SendDataTCPServer.js: TCP/IP server has received 13142 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.462Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.534Z SendDataTCPServer.js: TCP/IP server has received 15122 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.574Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.576Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.594Z SendDataTCPServer.js: TCP/IP server has received 19354 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.600Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.613Z SendDataTCPServer.js: TCP/IP server has received 21334 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.641Z SendDataTCPServer.js: TCP/IP server has received 27274 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.645Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.681Z SendDataTCPServer.js: TCP/IP server has received 29254 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.699Z SendDataTCPServer.js: TCP/IP server has received 31234 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.709Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.732Z SendDataTCPServer.js: TCP/IP server has received 33214 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.769Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.791Z SendDataTCPServer.js: TCP/IP server has received 35194 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.829Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.835Z SendDataTCPServer.js: TCP/IP server has received 37174 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.844Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.851Z SendDataTCPServer.js: TCP/IP server has received 39154 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.859Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.867Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.899Z SendDataTCPServer.js: TCP/IP server has received 43114 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.935Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:58.994Z SendDataTCPServer.js: TCP/IP server has received 45094 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.000Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.010Z SendDataTCPServer.js: TCP/IP server has received 47074 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.016Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.025Z SendDataTCPServer.js: TCP/IP server has received 49054 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.032Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.067Z SendDataTCPServer.js: TCP/IP server has received 51034 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.097Z SendDataTCPServer.js: TCP/IP server has received 53014 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.107Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.113Z SendDataTCPServer.js: TCP/IP server has received 54994 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.120Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.125Z SendDataTCPServer.js: TCP/IP server has received 56974 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.131Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.141Z SendDataTCPServer.js: TCP/IP server has received 58954 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.149Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.159Z SendDataTCPServer.js: TCP/IP server has received 60934 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.166Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.198Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.218Z SendDataTCPServer.js: TCP/IP server has received 64894 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.273Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.372Z SendDataTCPServer.js: TCP/IP server has received 66874 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.378Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.390Z SendDataTCPServer.js: TCP/IP server has received 68854 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.408Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.451Z SendDataTCPServer.js: TCP/IP server has received 70834 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.482Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.521Z SendDataTCPServer.js: TCP/IP server has received 72814 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.575Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.604Z SendDataTCPServer.js: TCP/IP server has received 74794 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.636Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.704Z SendDataTCPServer.js: TCP/IP server has received 76774 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.714Z SendDataTCPServer.js: TCP/IP server has received 78754 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.744Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.773Z SendDataTCPServer.js: TCP/IP server has received 80734 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.779Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.817Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.867Z SendDataTCPServer.js: TCP/IP server has received 86674 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.946Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.952Z SendDataTCPServer.js: TCP/IP server has received 88654 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.961Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.965Z SendDataTCPServer.js: TCP/IP server has received 90634 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:45:59.973Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:00.012Z SendDataTCPServer.js: TCP/IP server has received 96574 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:00.063Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:00.098Z SendDataTCPServer.js: TCP/IP server has received 98554 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:00.119Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3215): 
,W/bt-btif ( 2119): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 3215): Either failed to read from the output stream or write to the input stream (thread ID: 304, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3215): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3215): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 A3-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 302
D/io.jxcore.node.IncomingSocketThread( 3215): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3215): doStop: Thread ID: 304
D/io.jxcore.node.IncomingSocketThread( 3215): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3215): doStop: Thread ID: 303
D/io.jxcore.node.IncomingSocketThread( 3215): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3215): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3215): Either failed to read from the output stream or write to the input stream (thread ID: 303, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3215): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3215): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 A3-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3215): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3215): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3215): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3215): Exiting thread (ID: 303, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3215): Exiting thread (ID: 304, name: Receiver)
,I/jxcore-log( 3215): 2016-01-07T08:46:00.216Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3215): 
,W/bt-rfcomm( 2119): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 2119): RFCOMM_DisconnectInd LCID:0x42
,D/io.jxcore.node.ConnectionHelper( 3215): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
E/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3215): disconnectOutgoingConnection: Failed to disconnect (peer ID: 44:80:EB:7B:5A:05), either no such connection or failed to close the connection
,I/jxcore-log( 3215): 2016-01-07T08:46:01.454Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:01.455Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:01.456Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:01.457Z SendDataConnector.js: do connect now
I/jxcore-log( 3215): 
,I/io.jxcore.node.ConnectionHelper( 3215): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3215): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
W/io.jxcore.node.ConnectionHelper( 3215): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): connect: [44:80:EB:7B:5A:05 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): connect: Trying to start connecting to null in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): onConnecting: null 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): connect: Started connecting to null in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 3215): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 305)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3215): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3215): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1309317, pollInterval: 10000
,D/btif_config_util( 2119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2119): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=1
W/bt-btif ( 2119): bta_dm_check_av:0
,W/bt-btif ( 2119): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2119): onReceive
,D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a723481:true
,I/BTConnectionReceiver( 1392): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1392): Bluetooth Device Name: A3-1
,W/bt-btif ( 2119): info:x10
,D/        ( 2119): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2119): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1299309, pollInterval: 10000
,W/bt-sdp  ( 2119): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2119): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 2119): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2119): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2119): Entering PendingCommandState State
,W/BluetoothEventManager( 2706): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2706): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/BluetoothBondStateMachine( 2119): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2119): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 2119): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2119): StableState(): Entering Off State
,W/BluetoothEventManager( 2706): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2706): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,W/bt-btif ( 2119): new conn_srvc id:26, app_id:1
W/bt-btif ( 2119): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): onSocketConnected: [44:80:EB:7B:5A:05 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 305)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): onBytesWritten: 66 bytes successfully written (thread ID: 306)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Outgoing connection initialized (*handshake* thread ID: 306)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Exiting thread (thread ID: 305)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3215): Entering thread (ID: 306)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): onBytesRead: Read 65 bytes successfully (thread ID: 306)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Handshake succeeded with [44:80:EB:7B:5A:05 XT1072]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): onHandshakeSucceeded: [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3215): Exiting thread (ID: 306)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): onConnected: [44:80:EB:7B:5A:05 XT1072]
I/io.jxcore.node.ConnectionHelper( 3215): onConnected: Outgoing connection to peer [44:80:EB:7B:5A:05 XT1072]
D/io.jxcore.node.ConnectionHelper( 3215): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3215): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 XT1072] is available
,I/io.jxcore.node.ConnectionHelper( 3215): onConnected: Outgoing socket thread, for peer [44:80:EB:7B:5A:05 XT1072], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3215): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3215): Entering thread (ID: 307)
,D/io.jxcore.node.OutgoingSocketThread( 3215): Server socket local port: 32992
I/io.jxcore.node.OutgoingSocketThread( 3215): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3215): onListeningForIncomingConnections: Outgoing connection is using port 32992 (peer ID: 44:80:EB:7B:5A:05)
I/jxcore-log( 3215): 2016-01-07T08:46:13.914Z SendDataConnector.js: CLIENT connected to 32992, error: null
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:13.915Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3215): 
,I/io.jxcore.node.OutgoingSocketThread( 3215): Incoming data from address: /127.0.0.1, port: 32992
D/io.jxcore.node.OutgoingSocketThread( 3215): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3215): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3215): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3215): 2016-01-07T08:46:13.945Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3215): 
,I/io.jxcore.node.OutgoingSocketThread( 3215): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3215): Exiting thread (ID: 307)
,D/io.jxcore.node.StreamCopyingThread( 3215): Entering thread (ID: 308, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3215): Entering thread (ID: 309, name: Receiver)
,D/        ( 2119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:72020
,I/jxcore-log( 3215): 2016-01-07T08:46:14.885Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3215): 
,D/        ( 2119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:62826
,I/jxcore-log( 3215): 2016-01-07T08:46:14.930Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3215): 
,D/        ( 2119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:52926
,I/jxcore-log( 3215): 2016-01-07T08:46:14.982Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3215): 
,D/        ( 2119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:42036
,I/jxcore-log( 3215): 2016-01-07T08:46:15.065Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3215): 
,D/        ( 2119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:33126
,D/        ( 2119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:25206
,I/jxcore-log( 3215): 2016-01-07T08:46:15.142Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3215): 
,D/        ( 2119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13326
,I/jxcore-log( 3215): 2016-01-07T08:46:15.272Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3215): 
,D/        ( 2119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:6396
,I/jxcore-log( 3215): 2016-01-07T08:46:15.316Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:15.398Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:15.447Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:15.507Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:15.509Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3215): 
I/jxcore-log( 3215): oneRoundDownNow
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:15.514Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:15.514Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3215): 
D/io.jxcore.node.ConnectionHelper( 3215): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
,I/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 44:80:EB:7B:5A:05
I/io.jxcore.node.OutgoingSocketThread( 3215): close
D/io.jxcore.node.OutgoingSocketThread( 3215): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 3215): doStop: Thread ID: 309
D/io.jxcore.node.OutgoingSocketThread( 3215): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3215): doStop: Thread ID: 308
D/io.jxcore.node.OutgoingSocketThread( 3215): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3215): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3215): Either failed to read from the output stream or write to the input stream (thread ID: 308, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3215): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3215): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 XT1072] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3215): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3215): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3215): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3215): Either failed to read from the output stream or write to the input stream (thread ID: 309, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3215): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3215): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 XT1072] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3215): disconnectOutgoingConnection: Successfully disconnected (peer ID: 44:80:EB:7B:5A:05
,E/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3215): Exiting thread (ID: 309, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3215): Exiting thread (ID: 308, name: Sender)
,I/jxcore-log( 3215): 2016-01-07T08:46:15.562Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3215): 
I/jxcore-log( 3215): ---- round done--------
I/jxcore-log( 3215): 
I/jxcore-log( 3215): startWithNextDevice
I/jxcore-log( 3215): 
I/jxcore-log( 3215): do fake peer & start
I/jxcore-log( 3215): 
I/jxcore-log( 3215): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:15.563Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:15.563Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:15.563Z SendDataConnector.js: do connect now
I/jxcore-log( 3215): 
I/io.jxcore.node.ConnectionHelper( 3215): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3215): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): connect: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): onConnecting: null 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): connect: Started connecting to null in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3215): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 310)
W/BluetoothAdapter( 3215): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2119): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,D/btif_config_util( 2119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2119): onReceive
,I/BTConnectionReceiver( 1392): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1392): Bluetooth Device Name: XT1072
,W/bt-sdp  ( 2119): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 2119): DISCOVERY_COMP_EVT slot id:9, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2119): invalid rfc slot id: 9
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 310)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Maximum number of allowed retries (0) reached, giving up... (thread ID: 310)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Exiting thread (thread ID: 310)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [58:3F:54:73:64:C0 G3-1]
,I/jxcore-log( 3215): 2016-01-07T08:46:20.714Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [58:3F:54:73:64:C0 G3-1] failed
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:20.715Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [58:3F:54:73:64:C0 G3-1] failed
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:20.715Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3215): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): shutdown (thread ID: 310)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1289299, pollInterval: 10000
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): setState: RESTARTING
,I/wpa_supplicant(  985): P2P-FIND-STOPPED 
,I/wpa_supplicant(  985): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  985): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,I/wpa_supplicant(  985): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  985): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  985): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 0 device(s) discovered
,I/jxcore-log( 3215): 2016-01-07T08:46:25.717Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:25.717Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3215): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): P2P device discovery started successfully
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/io.jxcore.node.ConnectionHelper( 3215): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
E/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3215): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:3F:54:73:64:C0), either no such connection or failed to close the connection
I/jxcore-log( 3215): 2016-01-07T08:46:30.722Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:30.723Z SendDataConnector.js: Connect (retry count 1) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:30.723Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:30.724Z SendDataConnector.js: do connect now
I/jxcore-log( 3215): 
I/io.jxcore.node.ConnectionHelper( 3215): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3215): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): connect: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): onConnecting: null 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): connect: Started connecting to null in address 58:3F:54:73:64:C0
,I/io.jxcore.node.ConnectionHelper( 3215): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 312)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3215): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3215): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2119): info:x10
,D/        ( 2119): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2119): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2119): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2119): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 2119): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2119): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2119): Entering PendingCommandState State
,W/BluetoothEventManager( 2706): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2706): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2119): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2119): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 2119): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2119): StableState(): Entering Off State
,W/BluetoothEventManager( 2706): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2706): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,W/bt-btif ( 2119): new conn_srvc id:26, app_id:1
W/bt-btif ( 2119): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): onSocketConnected: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 312)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): onBytesWritten: 66 bytes successfully written (thread ID: 313)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Outgoing connection initialized (*handshake* thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Exiting thread (thread ID: 312)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3215): Entering thread (ID: 313)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): onBytesRead: Read 63 bytes successfully (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Handshake succeeded with [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): onHandshakeSucceeded: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3215): Exiting thread (ID: 313)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): onConnected: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 3215): onConnected: Outgoing connection to peer [58:3F:54:73:64:C0 G3-1]
D/io.jxcore.node.ConnectionHelper( 3215): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper( 3215): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3215): onConnected: Outgoing socket thread, for peer [58:3F:54:73:64:C0 G3-1], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3215): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3215): Entering thread (ID: 314)
D/io.jxcore.node.OutgoingSocketThread( 3215): Server socket local port: 38608
I/io.jxcore.node.OutgoingSocketThread( 3215): Now accepting connections...
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1279292, pollInterval: 10000
,I/io.jxcore.node.ConnectionHelper( 3215): onListeningForIncomingConnections: Outgoing connection is using port 38608 (peer ID: 58:3F:54:73:64:C0)
I/jxcore-log( 3215): 2016-01-07T08:46:31.748Z SendDataConnector.js: CLIENT connected to 38608, error: null
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:31.748Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3215): 
,I/io.jxcore.node.OutgoingSocketThread( 3215): Incoming data from address: /127.0.0.1, port: 38608
D/io.jxcore.node.OutgoingSocketThread( 3215): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3215): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3215): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3215): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3215): Exiting thread (ID: 314)
,I/jxcore-log( 3215): 2016-01-07T08:46:31.772Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3215): 
,D/io.jxcore.node.StreamCopyingThread( 3215): Entering thread (ID: 316, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3215): Entering thread (ID: 315, name: Sender)
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): restart: Restarting...
,D/WifiP2pManager( 3215): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): Service request added successfully
,D/        ( 2119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:72020
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3215): 2016-01-07T08:46:33.274Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3215): 
,D/        ( 2119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:62826
,I/jxcore-log( 3215): 2016-01-07T08:46:33.314Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3215): 
,D/        ( 2119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:50946
,I/jxcore-log( 3215): 2016-01-07T08:46:33.569Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3215): 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:43026
,I/jxcore-log( 3215): 2016-01-07T08:46:33.746Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3215): 
,I/wpa_supplicant(  985): p2p0: P2P: Reject scan trigger since one is already pending
,D/        ( 2119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:31146
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): Service discovery started successfully
,I/jxcore-log( 3215): 2016-01-07T08:46:33.803Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3215): 
,D/        ( 2119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23226
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 3215): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3215): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3215): 2016-01-07T08:46:34.079Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3215): 
,D/        ( 2119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11346
,I/jxcore-log( 3215): 2016-01-07T08:46:34.257Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3215): 
,W/bt-btif ( 2119): info:x10
,D/        ( 2119): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2119): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2119): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 2119): bta_dm_check_av:0
,W/bt-btif ( 2119): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2119): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
E/bt-btif ( 2119): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2119): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2119): Entering PendingCommandState State
,W/BluetoothEventManager( 2706): CachedBluetoothDevice for device 90:E7:C4:F6:69:77 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2706): Got bonding state changed for 90:E7:C4:F6:69:77, but we have no record of that device.
,I/BluetoothBondStateMachine( 2119): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
,D/BluetoothAdapterProperties( 2119): Failed to remove device: 90:E7:C4:F6:69:77
,I/BluetoothBondStateMachine( 2119): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2119): StableState(): Entering Off State
,W/BluetoothEventManager( 2706): CachedBluetoothDevice for device 90:E7:C4:F6:69:77 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2706): Got bonding state changed for 90:E7:C4:F6:69:77, but we have no record of that device.
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 2119): bta_dm_check_av:0
,W/bt-btif ( 2119): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2119): new conn_srvc id:26, app_id:255
W/bt-btif ( 2119): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2119): bta_dm_pm_ssr:2, lat:1200
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): Incoming connection initialized (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3215): Entering thread (ID: 317)
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): onBytesRead: Read 70 bytes successfully (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): Got valid identity from [90:E7:C4:F6:69:77 HTC One M8s]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): onBytesWritten: 66 bytes successfully written (thread ID: 317)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): removeThreadFromList: Removing thread with ID 317
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): Handshake thread disposed (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): onIncomingConnectionConnected: [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3215): Exiting thread (ID: 317)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): onConnected: [90:E7:C4:F6:69:77 HTC One M8s]
,I/io.jxcore.node.ConnectionHelper( 3215): onConnected: Incoming connection to peer [90:E7:C4:F6:69:77 HTC One M8s]
D/io.jxcore.node.ConnectionHelper( 3215): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
,D/io.jxcore.node.ConnectionHelper( 3215): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC One M8s] is available
,I/io.jxcore.node.ConnectionHelper( 3215): onConnected: Incoming socket thread, for peer [90:E7:C4:F6:69:77 HTC One M8s], created successfully
,D/io.jxcore.node.ConnectionHelper( 3215): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 3215): Entering thread (ID: 318)
,I/io.jxcore.node.IncomingSocketThread( 3215): Local host address: localhost/127.0.0.1, port: 43872
D/io.jxcore.node.IncomingSocketThread( 3215): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3215): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3215): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3215): startStreamCopyingThreads: OK
,I/jxcore-log( 3215): 2016-01-07T08:46:36.914Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3215): 
,D/io.jxcore.node.IncomingSocketThread( 3215): Exiting thread (ID: 318)
,D/io.jxcore.node.StreamCopyingThread( 3215): Entering thread (ID: 320, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3215): Entering thread (ID: 319, name: Sender)
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
,I/jxcore-log( 3215): 2016-01-07T08:46:38.000Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:38.008Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:38.160Z SendDataTCPServer.js: TCP/IP server has received 2970 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:38.248Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:38.372Z SendDataTCPServer.js: TCP/IP server has received 4950 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:38.379Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:38.407Z SendDataTCPServer.js: TCP/IP server has received 6930 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:38.414Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:38.581Z SendDataTCPServer.js: TCP/IP server has received 8910 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:38.699Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:38.863Z SendDataTCPServer.js: TCP/IP server has received 10890 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:38.926Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:38.960Z SendDataTCPServer.js: TCP/IP server has received 12870 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:38.967Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:39.037Z SendDataTCPServer.js: TCP/IP server has received 14850 bytes of data
I/jxcore-log( 3215): 
,W/bt-btif ( 2119): dm_pm_timer expires
W/bt-btif ( 2119): dm_pm_timer expires 0
W/bt-btif ( 2119): proc dm_pm_timer expires
,I/jxcore-log( 3215): 2016-01-07T08:46:39.229Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:39.300Z SendDataTCPServer.js: TCP/IP server has received 16830 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:39.308Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:39.395Z SendDataTCPServer.js: TCP/IP server has received 18810 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:39.469Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:39.566Z SendDataTCPServer.js: TCP/IP server has received 20790 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:39.580Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:39.609Z SendDataTCPServer.js: TCP/IP server has received 22770 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:39.710Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:39.752Z SendDataTCPServer.js: TCP/IP server has received 24750 bytes of data
I/jxcore-log( 3215): 
,E/bt-btm  ( 2119): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
E/bt-btm  ( 2119): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2119): bta_dm_check_av:0
,W/bt-btif ( 2119): btif_dm_cback : unhandled event (14)
,W/io.jxcore.node.StreamCopyingThread( 3215): Either failed to read from the output stream or write to the input stream (thread ID: 316, thread name: Receiver): Connection reset by peer
E/io.jxcore.node.IncomingSocketThread( 3215): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: Connection reset by peer", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3215): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 G3-1] disconnected: Either failed to read from the output stream or write to the input stream: Connection reset by peer
I/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 58:3F:54:73:64:C0
I/io.jxcore.node.IncomingSocketThread( 3215): close
D/io.jxcore.node.IncomingSocketThread( 3215): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3215): doStop: Thread ID: 316
D/io.jxcore.node.IncomingSocketThread( 3215): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3215): doStop: Thread ID: 315
D/io.jxcore.node.IncomingSocketThread( 3215): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3215): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3215): Either failed to read from the output stream or write to the input stream (thread ID: 315, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3215): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3215): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 G3-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3215): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3215): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 3215): closeBluetoothSocketAndStreams
,D/BluetoothMapService( 2119): onReceive
,D/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3215): Exiting thread (ID: 315, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3215): Exiting thread (ID: 316, name: Receiver)
,I/jxcore-log( 3215): 2016-01-07T08:46:39.867Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3215): 
,I/BTConnectionReceiver( 1392): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1392): Bluetooth Device Name: G3-1
,D/btif_config_util( 2119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 2119): bta_dm_check_av:0
,W/bt-btif ( 2119): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3215): 2016-01-07T08:46:40.030Z SendDataTCPServer.js: TCP/IP server has received 26730 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.036Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.081Z SendDataTCPServer.js: TCP/IP server has received 28710 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.086Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.105Z SendDataTCPServer.js: TCP/IP server has received 30690 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.112Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.149Z SendDataTCPServer.js: TCP/IP server has received 32670 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.153Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.165Z SendDataTCPServer.js: TCP/IP server has received 34650 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.175Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.185Z SendDataTCPServer.js: TCP/IP server has received 36630 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.241Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.247Z SendDataTCPServer.js: TCP/IP server has received 38610 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.270Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.280Z SendDataTCPServer.js: TCP/IP server has received 40590 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.289Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.337Z SendDataTCPServer.js: TCP/IP server has received 42570 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.385Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.394Z SendDataTCPServer.js: TCP/IP server has received 44550 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.405Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.454Z SendDataTCPServer.js: TCP/IP server has received 46530 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.467Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.475Z SendDataTCPServer.js: TCP/IP server has received 48510 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.482Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.541Z SendDataTCPServer.js: TCP/IP server has received 50490 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.551Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.589Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.604Z SendDataTCPServer.js: TCP/IP server has received 54450 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.610Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.679Z SendDataTCPServer.js: TCP/IP server has received 56430 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.704Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.717Z SendDataTCPServer.js: TCP/IP server has received 58410 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.724Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.736Z SendDataTCPServer.js: TCP/IP server has received 60390 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.765Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.829Z SendDataTCPServer.js: TCP/IP server has received 62370 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.835Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.842Z SendDataTCPServer.js: TCP/IP server has received 64350 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.848Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.854Z SendDataTCPServer.js: TCP/IP server has received 66330 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.863Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.872Z SendDataTCPServer.js: TCP/IP server has received 68310 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.905Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.915Z SendDataTCPServer.js: TCP/IP server has received 70290 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.926Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.976Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:40.984Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.007Z SendDataTCPServer.js: TCP/IP server has received 74250 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.012Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.065Z SendDataTCPServer.js: TCP/IP server has received 76230 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.073Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.084Z SendDataTCPServer.js: TCP/IP server has received 78210 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.148Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.165Z SendDataTCPServer.js: TCP/IP server has received 80190 bytes of data
,I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.179Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.232Z SendDataTCPServer.js: TCP/IP server has received 82170 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.245Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.251Z SendDataTCPServer.js: TCP/IP server has received 84150 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.258Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.266Z SendDataTCPServer.js: TCP/IP server has received 86130 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.315Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.326Z SendDataTCPServer.js: TCP/IP server has received 88110 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.344Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.403Z SendDataTCPServer.js: TCP/IP server has received 90090 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.417Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.449Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.505Z SendDataTCPServer.js: TCP/IP server has received 94050 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.512Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.570Z SendDataTCPServer.js: TCP/IP server has received 96030 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.582Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.592Z SendDataTCPServer.js: TCP/IP server has received 98010 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.651Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:41.659Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3215): 
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1269284, pollInterval: 10000
,E/bt-btm  ( 2119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 2119): bta_dm_check_av:0
,W/bt-btif ( 2119): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2119): invalid rfc slot id: 7
,W/io.jxcore.node.StreamCopyingThread( 3215): Either failed to read from the output stream or write to the input stream (thread ID: 320, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3215): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3215): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC One M8s] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 318
D/io.jxcore.node.IncomingSocketThread( 3215): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3215): doStop: Thread ID: 320
D/io.jxcore.node.IncomingSocketThread( 3215): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3215): doStop: Thread ID: 319
D/io.jxcore.node.IncomingSocketThread( 3215): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3215): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3215): Either failed to read from the output stream or write to the input stream (thread ID: 319, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3215): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3215): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC One M8s] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3215): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3215): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 3215): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3215): Exiting thread (ID: 319, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3215): Exiting thread (ID: 320, name: Receiver)
,I/jxcore-log( 3215): 2016-01-07T08:46:42.086Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3215): 
,W/bt-rfcomm( 2119): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 2119): RFCOMM_DisconnectInd LCID:0x49
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2119): onReceive
,I/BTConnectionReceiver( 1392): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1392): Bluetooth Device Name: HTC One M8s
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 3215): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3215): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): restart: Restarting...
,D/WifiP2pManager( 3215): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): Service request added successfully
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 3215): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3215): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,W/bt-btif ( 2119): info:x10
,D/        ( 2119): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2119): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2119): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 2119): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2119): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2119): Entering PendingCommandState State
,W/BluetoothEventManager( 2706): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2706): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,I/BluetoothBondStateMachine( 2119): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2119): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 2119): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2119): StableState(): Entering Off State
,W/BluetoothEventManager( 2706): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2706): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,W/bt-btif ( 2119): new conn_srvc id:26, app_id:255
W/bt-btif ( 2119): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): Incoming connection initialized (thread ID: 321)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3215): Entering thread (ID: 321)
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1259272, pollInterval: 10000
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): onBytesRead: Read 81 bytes successfully (thread ID: 321)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): Got valid identity from [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): onBytesWritten: 66 bytes successfully written (thread ID: 321)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): removeThreadFromList: Removing thread with ID 321
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): Handshake thread disposed (thread ID: 321)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3215): Exiting thread (ID: 321)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): onConnected: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 3215): onConnected: Incoming connection to peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/io.jxcore.node.ConnectionHelper( 3215): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3215): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
,I/io.jxcore.node.ConnectionHelper( 3215): onConnected: Incoming socket thread, for peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], created successfully
D/io.jxcore.node.ConnectionHelper( 3215): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3215): Entering thread (ID: 322)
,I/jxcore-log( 3215): 2016-01-07T08:46:51.907Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3215): 
,I/io.jxcore.node.IncomingSocketThread( 3215): Local host address: localhost/127.0.0.1, port: 43872
D/io.jxcore.node.IncomingSocketThread( 3215): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3215): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3215): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3215): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3215): Exiting thread (ID: 322)
,D/io.jxcore.node.StreamCopyingThread( 3215): Entering thread (ID: 324, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3215): Entering thread (ID: 323, name: Sender)
,I/jxcore-log( 3215): 2016-01-07T08:46:53.202Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.212Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.218Z SendDataTCPServer.js: TCP/IP server has received 4950 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.228Z SendDataTCPServer.js: TCP/IP server has received 6930 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.236Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.245Z SendDataTCPServer.js: TCP/IP server has received 10890 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.252Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.288Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.289Z SendDataTCPServer.js: TCP/IP server has received 17374 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.293Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.297Z SendDataTCPServer.js: TCP/IP server has received 19354 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.300Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.305Z SendDataTCPServer.js: TCP/IP server has received 21334 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.338Z SendDataTCPServer.js: TCP/IP server has received 25294 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.345Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.349Z SendDataTCPServer.js: TCP/IP server has received 27274 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.357Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.361Z SendDataTCPServer.js: TCP/IP server has received 29254 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.365Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.368Z SendDataTCPServer.js: TCP/IP server has received 31234 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.408Z SendDataTCPServer.js: TCP/IP server has received 37174 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.417Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.425Z SendDataTCPServer.js: TCP/IP server has received 39154 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.432Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.440Z SendDataTCPServer.js: TCP/IP server has received 41134 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.479Z SendDataTCPServer.js: TCP/IP server has received 45094 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.486Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.490Z SendDataTCPServer.js: TCP/IP server has received 47074 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.496Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.500Z SendDataTCPServer.js: TCP/IP server has received 49054 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.505Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.541Z SendDataTCPServer.js: TCP/IP server has received 51034 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.580Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.585Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.592Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.597Z SendDataTCPServer.js: TCP/IP server has received 60934 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.607Z SendDataTCPServer.js: TCP/IP server has received 62914 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.641Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.657Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.665Z SendDataTCPServer.js: TCP/IP server has received 72814 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.678Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.720Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.757Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.793Z SendDataTCPServer.js: TCP/IP server has received 78754 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.803Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.807Z SendDataTCPServer.js: TCP/IP server has received 86674 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.811Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.848Z SendDataTCPServer.js: TCP/IP server has received 92614 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.860Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.863Z SendDataTCPServer.js: TCP/IP server has received 94594 bytes of data
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:46:53.898Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3215): 
,W/bt-btif ( 2119): invalid rfc slot id: 11
,W/io.jxcore.node.StreamCopyingThread( 3215): Either failed to read from the output stream or write to the input stream (thread ID: 324, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3215): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3215): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 322
D/io.jxcore.node.IncomingSocketThread( 3215): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3215): doStop: Thread ID: 324
D/io.jxcore.node.IncomingSocketThread( 3215): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3215): doStop: Thread ID: 323
D/io.jxcore.node.IncomingSocketThread( 3215): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3215): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3215): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3215): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3215): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3215): Exiting thread (ID: 324, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3215): Either failed to read from the output stream or write to the input stream (thread ID: 323, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3215): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3215): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3215): Exiting thread (ID: 323, name: Sender)
,I/jxcore-log( 3215): 2016-01-07T08:46:53.983Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3215): 
,W/bt-rfcomm( 2119): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 2119): RFCOMM_DisconnectInd LCID:0x4b
,I/jxcore-log( 3215): 2016-01-07T08:46:54.259Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:54.260Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:54.261Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:54.261Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:54.263Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3215): 
,D/btif_config_util( 2119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2119): onReceive
,I/BTConnectionReceiver( 1392): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1392): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 3215): 2016-01-07T08:46:59.263Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:59.264Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:46:59.265Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3215): 
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1249264, pollInterval: 10000
,D/io.jxcore.node.ConnectionHelper( 3215): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
E/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3215): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:3F:54:73:64:C0), either no such connection or failed to close the connection
I/jxcore-log( 3215): 2016-01-07T08:47:04.271Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:47:04.272Z SendDataConnector.js: Connect (retry count 2) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:47:04.272Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:47:04.273Z SendDataConnector.js: do connect now
I/jxcore-log( 3215): 
I/io.jxcore.node.ConnectionHelper( 3215): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3215): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): connect: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): connect: Trying to start connecting to G3-1 in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): onConnecting: G3-1 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): connect: Started connecting to G3-1 in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3215): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 325)
W/BluetoothAdapter( 3215): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/ActivityManager(  735): Killing 2724:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10003/pid_2724/cgroup.procs: No such file or directory
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1239255, pollInterval: 10000
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): setState: RESTARTING
,I/wpa_supplicant(  985): P2P-FIND-STOPPED 
,I/wpa_supplicant(  985): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  985): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): onConnectionTimeout: [58:3F:54:73:64:C0 G3-1]
I/jxcore-log( 3215): 2016-01-07T08:47:19.296Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [58:3F:54:73:64:C0 G3-1] timed out
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:47:19.296Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [58:3F:54:73:64:C0 G3-1] timed out
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:47:19.297Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:47:19.301Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3215): 
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1229248, pollInterval: 10000
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): Start timer timeout, starting now...
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/jxcore-log( 3215): 2016-01-07T08:47:24.305Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:47:24.306Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:47:24.307Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3215): 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3215): timeout now
I/jxcore-log( 3215): 
I/jxcore-log( 3215): weAreDoneNow, resultArray.length: 1
I/jxcore-log( 3215): 
I/jxcore-log( 3215): sendReportNow
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): done, now sending data to server
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:47:26.353Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:47:26.353Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:47:26.354Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3215): 
D/io.jxcore.node.ConnectionHelper( 3215): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
E/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3215): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:3F:54:73:64:C0), either no such connection or failed to close the connection
I/jxcore-log( 3215): 2016-01-07T08:47:26.355Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3215): 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): restart: Restarting...
,D/WifiP2pManager( 3215): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): Service request added successfully
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): Service discovery started successfully
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3215): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
E/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3215): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3215): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:3F:54:73:64:C0), either no such connection or failed to close the connection
I/jxcore-log( 3215): 2016-01-07T08:47:29.315Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:47:29.316Z SendDataConnector.js: Connect (retry count 3) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:47:29.328Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:47:29.328Z SendDataConnector.js: do connect now
I/jxcore-log( 3215): 
I/io.jxcore.node.ConnectionHelper( 3215): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3215): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): connect: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): connect: Trying to start connecting to G3-1 in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): onConnecting: G3-1 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): connect: Started connecting to G3-1 in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3215): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 327)
W/BluetoothAdapter( 3215): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1219240, pollInterval: 10000
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 3215): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3215): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/io.jxcore.node.ConnectionHelper( 3215): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3215): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1]
I/io.jxcore.node.ConnectionHelper( 3215): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 3215): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 Note4-1] already in the list, will not add again
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 3215): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 3215): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2119): SDP - Rcvd conn cnf with error: 0x8  CID 0x4c
E/bt-btif ( 2119): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2119): invalid rfc slot id: 13
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 325)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Maximum number of allowed retries (0) reached, giving up... (thread ID: 325)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): Exiting thread (thread ID: 325)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3215): shutdown (thread ID: 325)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [58:3F:54:73:64:C0 G3-1]
I/jxcore-log( 3215): 2016-01-07T08:47:39.434Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [58:3F:54:73:64:C0 G3-1] failed
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:47:39.435Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [58:3F:54:73:64:C0 G3-1] failed
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:47:39.436Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:47:39.436Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3215): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): restart: Restarting...
,D/WifiP2pManager( 3215): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): Service request added successfully
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,W/bt-btif ( 2119): info:x10
,D/        ( 2119): remote version info [58:3f:54:73:64:c0]: 7, f, 610c
,I/BTConnectionReceiver( 1392): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1392): Bluetooth Device Name: G3-1
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  985): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3215): Service discovery started successfully
,W/ActivityManager(  735): getRecentTasks: caller 10016 is using old GET_TASKS but privileged; allowing
,D/Finsky  ( 2639): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1209230, pollInterval: 10000
,W/bt-sdp  ( 2119): process_service_search_attr_rsp
,D/btif_config_util( 2119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3215): 2016-01-07T08:47:44.445Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:47:44.445Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3215): 
I/jxcore-log( 3215): 2016-01-07T08:47:44.446Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): teardown
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): testSendData stopped
I/jxcore-log( 3215): 
I/io.jxcore.node.ConnectionHelper( 3215): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3215): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3215): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3215): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3215): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3215): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3215): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3215): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3215): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3215): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3215): setState: NOT_STARTED
I/jxcore-log( 3215): StopBroadcasting went ok
I/jxcore-log( 3215): 
,I/jxcore-log( 3215): 2016-01-07T08:47:45.796Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3215): 
I/chromium( 3215): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3215): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3215): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3215): ****TEST TOOK:  ms ****
I/jxcore-log( 3215): 
I/jxcore-log( 3215): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3215): 
,D/AndroidRuntime( 3651): 
D/AndroidRuntime( 3651): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3651): CheckJNI is OFF
,D/AndroidRuntime( 3651): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  735): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  735): Killing 3215:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  735): WIN DEATH: Window{24263256 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  735): Client connection lost with reason: 4
,E/bt-btif ( 2119): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:14, channel:-1
,W/PackageSettings(  735): Skipping PackageSetting{c8d24f2 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  735):   Force finishing activity ActivityRecord{13e67dcd u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  735): Spurious death for ProcessRecord{b65d926 3215:com.test.thalitest/u0a270}, curProc for 3215: null
,I/ActivityManager(  735): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1392): Explicit concurrent mark sweep GC freed 20922(864KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 19MB/25MB, paused 302us total 21.120ms
,I/art     ( 1269): Explicit concurrent mark sweep GC freed 3924(292KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 506us total 16.027ms
,I/art     ( 1649): Explicit concurrent mark sweep GC freed 10691(516KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 440us total 41.937ms
,I/InputReader(  735): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1612): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1103): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1103): run()
,I/Decoder ( 1103): createOrResetDecoder
D/VoicemailCleanupService( 1345): Cleaning up data for package: com.test.thalitest
,I/UpdateIcingCorporaServi( 1392): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/art     (  735): Explicit concurrent mark sweep GC freed 39544(1997KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.155ms total 79.604ms
,I/Adreno-EGL(  945): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  945): Initialized EGL, version 1.4
,I/art     (  735): WaitForGcToComplete blocked for 48.683ms for cause Explicit
,W/Launcher( 1269): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1ae1489f new=com.google.android.velvet.VelvetApplication@1ae1489f
,D/OpenGLRenderer(  945): Enabling debug mode 0
,I/ActivityManager(  735): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3690 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,W/InputMethodManagerService(  735): Got RemoteException sending setActive(false) notification to pid 3215 uid 10270
,I/Keyboard.Facilitator( 1103): onFinishInput()
,D/BackupManagerService(  735): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  735): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1103): run()
,D/TaskPersister(  735): removeObsoleteFile: deleting file=214_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1103): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1103): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1103): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1103): run()
I/StatsUtilsManager( 1103): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1103): shouldRecordStats() = Too Soon
,W/ContextImpl( 3690): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/UpdateIcingCorporaServi( 1392): UpdateCorporaTask done [took 178 ms] updated apps [took 178 ms] 
,D/ChimeraCfgMgr( 1649): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1649): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1649): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1649): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 1649): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1649): Clearing selected account for com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1612): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1612): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/ResourcesManager( 1269): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/art     (  735): Explicit concurrent mark sweep GC freed 10022(535KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 3.033ms total 183.227ms
,I/Launcher( 1269): Deferring update until onResume
,W/ResourcesManager( 1269): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/LocationSettingsChecker( 1649): Removing dialog suppression flag for package com.test.thalitest
,I/Launcher( 1269): Deferring update until onResume
,D/gH_CompatibleDatabase( 1649): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1649): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1649): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1649): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1649): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1649): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1649): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1649): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1649): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1649): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1649): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1649): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1649): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  735): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3723 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,D/AndroidRuntime( 3651): Shutting down VM
,I/GMPM-SVC( 1649): App measurement is starting up, version: 8489
I/GMPM-SVC( 1649): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1649): Using Auth Proxy for data requests.
,W/BaseAppContext( 1649): Using Auth Proxy for data requests.
,I/Icing   ( 1649): doRemovePackageData com.test.thalitest
,I/ActivityManager(  735): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3748 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  735): Killing 2577:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10070/pid_2577/cgroup.procs: No such file or directory
,I/ActivityManager(  735): Killing 2025:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10031/pid_2025/cgroup.procs: No such file or directory
,D/ExternalStorage( 3748): After updating volumes, found 1 active roots
,W/ResourcesManager( 3126): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3126): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3723): Update found 7 roots in 299ms
,D/Documents( 3723): Update found 7 roots in 131ms

```
