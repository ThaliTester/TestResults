#### Test 5065027869d93ea_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/Finsky  ( 2678): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3198): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3198): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  755): Killing 2118:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 3198): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3198): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3198): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  755): failed to open /acct/uid_10038/pid_2118/cgroup.procs: No such file or directory
V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1697): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1697): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1697): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1697): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
D/CAR.SERVICE( 3082): mConnectedToCar = false, abort
E/ActivityThread( 3082): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@11c1cecb that was originally bound here
E/ActivityThread( 3082): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@11c1cecb that was originally bound here
E/ActivityThread( 3082): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3082): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3082): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3082): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3082): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3082): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3082): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3082): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3082): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3082): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3082): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3082): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3082): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3082): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3082): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3082): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3082): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3082): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3082): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3082): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3082): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3082): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3082): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/ActivityThread( 3082): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@26893df2 that was originally bound here
E/ActivityThread( 3082): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@26893df2 that was originally bound here
E/ActivityThread( 3082): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3082): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3082): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3082): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3082): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3082): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3082): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3082): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3082): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3082): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3082): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3082): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3082): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3082): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3082): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3082): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3082): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3082): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3082): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3082): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3082): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3082): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  755): Unbind failed: could not find connection for android.os.BinderProxy@b8a112f
I/ActivityManager(  755): Killing 2641:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/libprocessgroup(  755): failed to open /acct/uid_10069/pid_2641/cgroup.procs: No such file or directory
,D/AndroidRuntime( 3262): 
D/AndroidRuntime( 3262): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3262): CheckJNI is OFF
D/AndroidRuntime( 3262): Calling main entry com.android.commands.am.Am
I/ActivityManager(  755): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  755): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3286 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3262): Shutting down VM
V/ActivityManager(  755): Display changed displayId=0
I/WebViewFactory( 3286): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3286): Time to load native libraries: 2 ms (timestamps 9453-9455)
I/LibraryLoader( 3286): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3286): Binding Chromium to main looper Looper (main, tid 1) {23180f32}
I/LibraryLoader( 3286): Expected native library version number "",actual native library version number ""
I/chromium( 3286): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3286): Initializing chromium process, singleProcess=true
W/art     ( 3286): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3286): ApplicationContext is null in ApplicationStatus
W/chromium( 3286): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3286): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3286): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3286): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  755): Message: 20
D/BluetoothManagerService(  755): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c937340:true
,W/art     ( 3286): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3286): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3286): CordovaWebView is running on device made by: LGE
,W/art     ( 3286): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3286): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3286): Render dirty regions requested: true
,D/Atlas   ( 3286): Validating map...
,W/chromium( 3286): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3286): Initialized EGL, version 1.4
D/OpenGLRenderer( 3286): Enabling debug mode 0
,W/IInputConnectionWrapper( 3286): showStatusIcon on inactive InputConnection
,I/ActivityManager(  755): Displayed com.test.thalitest/.MainActivity: +423ms (total +57s747ms)
,W/BindingManager( 3286): Cannot call determinedVisibility() - never saw a connection for the pid: 3286
,D/JsMessageQueue( 3286): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3286): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342720
,D/JX-Cordova( 3286): jxcore cordova android initializing
,W/jxcore-log( 3286): Initializing JXcore engine
W/jxcore-log( 3286): JXcore engine is ready
,W/jxcore-log( 3286): Starting JXcore engine
,W/.test.thalitest( 3286): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9759]" dev="sockfs" ino=9759 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3286): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3286): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6561]" dev="sockfs" ino=6561 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3286): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19451]" dev="sockfs" ino=19451 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3286): Platform android
W/jxcore-log( 3286): 
W/jxcore-log( 3286): Process ARCH arm
W/jxcore-log( 3286): 
,I/jxcore-log( 3286): JXcore Cordova bridge is ready!
I/jxcore-log( 3286): 
W/jxcore-log( 3286): JXcore engine is started
I/Choreographer( 3286): Skipped 108 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3286): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3286): Toggling radios to true
I/jxcore-log( 3286): 
,D/BluetoothAdapter( 3286): enable(): BT is already enabled..!
,D/WifiService(  755): New client listening to asynchronous messages
,D/WifiService(  755): setWifiEnabled: true pid=3286, uid=10270
E/WifiService(  755): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3286): Radios toggled
I/jxcore-log( 3286): 
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3286): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3286): 
I/jxcore-log( 3286): Perf Test app loaded loaded
I/jxcore-log( 3286): 
,I/wpa_supplicant(  988): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  755): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  755): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
I/jxcore-log( 3286): check test folder
I/jxcore-log( 3286): 
E/native  (  755): do suspend true
I/jxcore-log( 3286): found test : ./testFindPeers.js
I/jxcore-log( 3286): 
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,I/jxcore-log( 3286): found test : ./testSendData.js
I/jxcore-log( 3286): 
,V/NativeCrypto( 1657): Read error: ssl=0xaf86ce00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1657): SSL shutdown failed: ssl=0xaf86ce00: I/O error during system call, Broken pipe
,D/ConnectivityService(  755): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiConfigStore(  755): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  755): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  755): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  755): Start Disconnecting Watchdog 1
I/wpa_supplicant(  988): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  755): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
D/ConnectivityService(  755): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  755): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  755): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  755): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Disconnected - quitting
,D/TelephonyNetworkFactory( 1295): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/Choreographer( 3286): Skipped 66 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3286): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiNetworkAgent(  755): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityManager.CallbackHandler( 1697): CM callback handler got msg 524292
,I/wpa_supplicant(  988): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  988): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  988): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  988): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  755): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  755): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  755): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  755): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  179): Setting iface cfg
E/WifiStateMachine(  755): Start Dhcp Watchdog 2
,E/native  (  755): do suspend false
,E/WifiStateMachine(  755): scanCount==0 - aborting
,I/dhcpcd  ( 3386): version 5.5.6 starting
,E/dhcpcd  ( 3386): get_duid: Read-only file system
,I/dhcpcd  ( 3386): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3386): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3386): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  755): MasterInitialState.processMessage what=3
,D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  755): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2792): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1697): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1697): onCreate
,D/SystemUpdateService( 1697): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1697): active receiver: enabled
,I/iu.Environment( 1697): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/SystemUpdateService( 1697): showing system update notification
,I/iu.UploadsManager( 1697): num queued entries: 0
I/iu.UploadsManager( 1697): num updated entries: 0
,I/iu.SyncManager( 1697): NEXT; no task
,I/Babel   ( 1962): connection state changed from CONNECTED to DISCONNECTED
,I/ValidateNoPeople(  755): skipping global notification
,V/SystemUpdateService( 1697): retry (wakeup: false) in 3599975 ms
,I/ActivityManager(  755): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3432 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1697): onDestroy
,E/GpsLocationProvider(  755): No APN found to select.
,E/GpsLocationProvider(  755): No APN found to select.
,I/GAv4    ( 3432): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3432):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3432):   adb logcat -s GAv4
,W/GAv4    ( 3432): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3432): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3432): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/native  (  755): do suspend true
,D/ConnectivityService(  755): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  755): Adding iface wlan0 to network 101
,E/WifiStateMachine(  755): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  755): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  755): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  755): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  755): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  755): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  755): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  755): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  755): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  755): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  755):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/CSLegacyTypeTracker(  755): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  755): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  755): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1697): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sat, 19 Dec 2015 00:23:04 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450484584336], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450484584321]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Validated
D/ConnectivityService(  755): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  755): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  755): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  755): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1697): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1295): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,I/WebViewFactory( 3432): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3432): Time to load native libraries: 2 ms (timestamps 6471-6473)
I/LibraryLoader( 3432): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3432): Binding Chromium to main looper Looper (main, tid 1) {2077166}
,I/LibraryLoader( 3432): Expected native library version number "",actual native library version number ""
I/chromium( 3432): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3432): Initializing chromium process, singleProcess=true
W/art     ( 3432): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3432): ApplicationContext is null in ApplicationStatus
,W/chromium( 3432): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3432): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3432): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3432): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3432): Requires BLUETOOTH permission
,I/NSApplication( 3432): Starting up...
,I/ActivityManager(  755): Killing 2595:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10045/pid_2595/cgroup.procs: No such file or directory
,V/MusicLeanback( 2792): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1697): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1697): onCreate
,D/SystemUpdateService( 1697): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1697): active receiver: enabled
I/iu.Environment( 1697): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1697): num queued entries: 0
I/iu.UploadsManager( 1697): num updated entries: 0
I/iu.SyncManager( 1697): NEXT; no task
I/SystemUpdateService( 1697): showing system update notification
,I/ValidateNoPeople(  755): skipping global notification
,V/SystemUpdateService( 1697): retry (wakeup: false) in 3599982 ms
,D/SystemUpdateService( 1697): onDestroy
,I/Babel   ( 1962): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  755): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3286): BLE supported!!
I/jxcore-log( 3286): 
,D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  755): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2792): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2792): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1697): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1697): onCreate
,D/SystemUpdateService( 1697): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1697): active receiver: enabled
,I/SystemUpdateService( 1697): showing system update notification
,I/ValidateNoPeople(  755): skipping global notification
,V/SystemUpdateService( 1697): retry (wakeup: false) in 3599986 ms
,D/SystemUpdateService( 1697): onDestroy
,E/GpsLocationProvider(  755): No APN found to select.
,D/Finsky  ( 2678): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2678): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/art     (  755): Explicit concurrent mark sweep GC freed 45412(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.156ms total 60.220ms
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1657): Vacuum at: now=1450484601172 tag=VacuumService
,I/PhenotypeConfigurator( 1657): Scheduling Phenotype for one-off execution 3803 seconds from now (1450484601396)
,D/GetConfigurationSnapshotOperation( 1657): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1657): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1657): Using platform SSLCertificateSocketFactory
,I/ClearcutLoggerApiImpl( 1657): disconnect managed GoogleApiClient
,I/jxcore-log( 3286): Connected to the server!
I/jxcore-log( 3286): 
,I/chromium( 3286): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3286): --- start :testSendData.js---
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":15}bt-address length : 0
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): daya100000
I/jxcore-log( 3286): 
I/jxcore-log( 3286): check server
I/jxcore-log( 3286): 
I/jxcore-log( 3286): serverPort is 43481
I/jxcore-log( 3286): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT6618
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3286): bind: Binding a new listener
D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3286): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3286): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6618","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3286): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): start: OK
I/io.jxcore.node.ConnectionHelper( 3286): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT6618
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3286): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6618","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3286): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6618","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3286): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6618","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3286): start: OK
I/jxcore-log( 3286): StartBroadcasting started ok
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): null
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:52.636Z SendDataTCPServer.js: TCP/IP server is bound to port: 43481
I/jxcore-log( 3286): 
,I/chromium( 3286): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3286): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3286): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
I/io.jxcore.node.ConnectionHelper( 3286): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 3286): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2143): info:x10
,D/        ( 2143): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2143): aclStateChangeCallback: Device is NULL
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
E/bt-btif ( 2143): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2143): Entering PendingCommandState State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 2143): Failed to remove device: 7C:F9:0E:51:18:22
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection initialized (thread ID: 308)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 308)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): onBytesRead: Read 83 bytes successfully (thread ID: 308)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): onBytesWritten: 77 bytes successfully written (thread ID: 308)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): removeThreadFromList: Removing thread with ID 308
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Handshake thread disposed (thread ID: 308)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 308)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
,I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Incoming connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] is available
,I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT7600","peerAvailable":true}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): Found peer : samsung-SM-A500FU_PT7600, Available: true
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
I/jxcore-log( 3286): device[1]: 7C:F9:0E:51:18:22
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:28:56.545Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:28:56.546Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:28:56.546Z SendDataConnector.js: do connect now
I/jxcore-log( 3286): 
I/BluetoothBondStateMachine( 2143): StableState(): Entering Off State
I/io.jxcore.node.ConnectionHelper( 3286): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): connect: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3286): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Incoming socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], created successfully
D/io.jxcore.node.ConnectionHelper( 3286): onConnected: The total number of connections is now 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 309)
,W/BluetoothAdapter( 3286): getBluetoothService() called with no BluetoothManagerCallback
D/io.jxcore.node.IncomingSocketThread( 3286): Entering thread (ID: 310)
D/BTIF_SOCK( 2143): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/io.jxcore.node.IncomingSocketThread( 3286): Local host address: localhost/127.0.0.1, port: 43481
,I/jxcore-log( 3286): 2015-12-19T00:28:56.556Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3286): 
,D/io.jxcore.node.IncomingSocketThread( 3286): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3286): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3286): Exiting thread (ID: 310)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 312, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 311, name: Sender)
,W/bt-sdp  ( 2143): process_service_search_attr_rsp
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onSocketConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 309)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesWritten: 77 bytes successfully written (thread ID: 313)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Outgoing connection initialized (*handshake* thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Exiting thread (thread ID: 309)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 313)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesRead: Read 83 bytes successfully (thread ID: 313)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onHandshakeSucceeded: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: We have an incoming connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 3286): onConnected: Already connected with peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] already in the list, will not add again
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 313)
,I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3286): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 3286): Entering thread (ID: 314)
,D/io.jxcore.node.OutgoingSocketThread( 3286): Server socket local port: 48906
I/io.jxcore.node.OutgoingSocketThread( 3286): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3286): onListeningForIncomingConnections: Outgoing connection is using port 48906 (peer ID: 7C:F9:0E:51:18:22)
I/jxcore-log( 3286): 2015-12-19T00:28:56.936Z SendDataConnector.js: CLIENT connected to 48906, error: null
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:28:56.937Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:56.941Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3286): 
,I/io.jxcore.node.OutgoingSocketThread( 3286): Incoming data from address: /127.0.0.1, port: 48906
D/io.jxcore.node.OutgoingSocketThread( 3286): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3286): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3286): Exiting thread (ID: 314)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 316, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 315, name: Sender)
,I/jxcore-log( 3286): 2015-12-19T00:28:57.405Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:57.468Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:57.478Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:57.497Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:57.555Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:57.641Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:57.658Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3286): 
,D/        ( 2143): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 3286): 2015-12-19T00:28:57.686Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:57.693Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:57.732Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:57.744Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:57.816Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:57.827Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:57.842Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:57.851Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:57.854Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:57.921Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:57.954Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:58.009Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3286): 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/        ( 2143): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 3286): 2015-12-19T00:28:58.047Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:58.057Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3286): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,I/jxcore-log( 3286): 2015-12-19T00:28:58.186Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:58.237Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:28:58.239Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:58.281Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:58.374Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:58.461Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:58.546Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:58.569Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3286): 
,D/        ( 2143): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3286): 2015-12-19T00:28:58.581Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:58.595Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:58.600Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:58.647Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:58.766Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:58.829Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:58.919Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:58.954Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:59.001Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:59.101Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:59.135Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:59.199Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:59.212Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:59.270Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:59.340Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:59.374Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:59.414Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:59.475Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:59.504Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:59.542Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:59.657Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:59.712Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:59.745Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:59.803Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:59.812Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:28:59.825Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:28:59.826Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3286): 
I/jxcore-log( 3286): oneRoundDownNow
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:28:59.830Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:28:59.831Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): invalid rfc slot id: 4
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 312, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3286): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 310
D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 312
D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 311
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 311, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3286): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 311, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 312, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 3286): close
D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 316
D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 315
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 315, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3286): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 316, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 315, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 316, name: Receiver)
,I/jxcore-log( 3286): 2015-12-19T00:28:59.878Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3286): 
I/jxcore-log( 3286): ---- round done--------
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/jxcore-log( 3286): 2015-12-19T00:28:59.884Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3286): 
,D/btif_config_util( 2143): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2143): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2143): onReceive
,D/BluetoothManagerService(  755): Message: 20
D/BluetoothManagerService(  755): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2381d0a8:true
,I/BTConnectionReceiver( 1379): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1379): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT6420","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] is available
,I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC-HTC One M8s_PT6420","peerAvailable":true}]
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): Found peer : HTC-HTC One M8s_PT6420, Available: true
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): device[2]: 90:E7:C4:F6:69:77
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:29:42.808Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:29:42.809Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:29:42.810Z SendDataConnector.js: do connect now
I/jxcore-log( 3286): 
I/io.jxcore.node.ConnectionHelper( 3286): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): connect: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Trying to start connecting to null in address 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnecting: null 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Started connecting to null in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 3286): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 317)
W/BluetoothAdapter( 3286): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2143): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2143): info:x10
,D/        ( 2143): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2143): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2143): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
E/bt-btif ( 2143): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2143): Entering PendingCommandState State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device 90:E7:C4:F6:69:77 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for 90:E7:C4:F6:69:77, but we have no record of that device.
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
,D/BluetoothAdapterProperties( 2143): Failed to remove device: 90:E7:C4:F6:69:77
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2143): StableState(): Entering Off State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device 90:E7:C4:F6:69:77 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for 90:E7:C4:F6:69:77, but we have no record of that device.
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onSocketConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesWritten: 77 bytes successfully written (thread ID: 318)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Outgoing connection initialized (*handshake* thread ID: 318)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Exiting thread (thread ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 318)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesRead: Read 81 bytes successfully (thread ID: 318)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Handshake succeeded with [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onHandshakeSucceeded: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 318)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing connection to peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing socket thread, for peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3286): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3286): Entering thread (ID: 319)
D/io.jxcore.node.OutgoingSocketThread( 3286): Server socket local port: 41143
I/io.jxcore.node.OutgoingSocketThread( 3286): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3286): onListeningForIncomingConnections: Outgoing connection is using port 41143 (peer ID: 90:E7:C4:F6:69:77)
I/jxcore-log( 3286): 2015-12-19T00:29:52.635Z SendDataConnector.js: CLIENT connected to 41143, error: null
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:29:52.635Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3286): 
,I/io.jxcore.node.OutgoingSocketThread( 3286): Incoming data from address: /127.0.0.1, port: 41143
D/io.jxcore.node.OutgoingSocketThread( 3286): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3286): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3286): Exiting thread (ID: 319)
,I/jxcore-log( 3286): 2015-12-19T00:29:52.657Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3286): 
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 320, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 321, name: Receiver)
,D/        ( 2143): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3286): 2015-12-19T00:29:53.253Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3286): 
,D/        ( 2143): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:17776
,I/jxcore-log( 3286): 2015-12-19T00:29:53.289Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3286): 
,D/        ( 2143): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:10846
,I/jxcore-log( 3286): 2015-12-19T00:29:53.322Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:29:53.375Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3286): 
,D/        ( 2143): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:946
,I/jxcore-log( 3286): 2015-12-19T00:29:53.419Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:29:53.460Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:29:53.558Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:29:53.608Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:29:53.671Z SendDataConnector.js: CLIENT is data received : 100000,
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:29:53.672Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): oneRoundDownNow
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:29:53.679Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:29:53.681Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3286): 
,D/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 90:E7:C4:F6:69:77
I/io.jxcore.node.OutgoingSocketThread( 3286): close
D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 321
D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 320
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 320, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3286): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 321, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Successfully disconnected (peer ID: 90:E7:C4:F6:69:77
,E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
,W/bt-btif ( 2143): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 320, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 321, name: Receiver)
,I/jxcore-log( 3286): 2015-12-19T00:29:53.730Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3286): 
I/jxcore-log( 3286): ---- round done--------
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,E/bt-btm  ( 2143): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2143): onReceive
,I/BTConnectionReceiver( 1379): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1379): Bluetooth Device Name: HTC One M8s
,D/btif_config_util( 2143): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ActivityManager(  755): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3677 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3677): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3677):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3677):   adb logcat -s GAv4
,W/GAv4    ( 3677): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3677): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3677): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  755): Killing 2767:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10003/pid_2767/cgroup.procs: No such file or directory
,W/bt-btif ( 2143): info:x10
,D/        ( 2143): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1379): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1379): Bluetooth Device Name: HTC One M8s
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection initialized (thread ID: 322)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 322)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): onBytesRead: Read 81 bytes successfully (thread ID: 322)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Got valid identity from [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): onBytesWritten: 77 bytes successfully written (thread ID: 322)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): removeThreadFromList: Removing thread with ID 322
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Handshake thread disposed (thread ID: 322)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onIncomingConnectionConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Incoming connection to peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Incoming socket thread, for peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], created successfully
D/io.jxcore.node.ConnectionHelper( 3286): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 322)
,D/io.jxcore.node.IncomingSocketThread( 3286): Entering thread (ID: 323)
,I/jxcore-log( 3286): 2015-12-19T00:30:05.481Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3286): 
,I/io.jxcore.node.IncomingSocketThread( 3286): Local host address: localhost/127.0.0.1, port: 43481
D/io.jxcore.node.IncomingSocketThread( 3286): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3286): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3286): Exiting thread (ID: 323)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 325, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 324, name: Sender)
,I/jxcore-log( 3286): 2015-12-19T00:30:06.154Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.188Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.190Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.208Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.214Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.225Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.231Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.263Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.312Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.322Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.333Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.373Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.383Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.414Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.448Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.462Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.495Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.507Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.538Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.543Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.553Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.599Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.613Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.619Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.629Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.640Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.675Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.688Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.694Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.701Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.748Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.786Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.831Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:30:06.866Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 325, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3286): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 323
D/io.jxcore.node.IncomingSocketThread( 3286): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 325
D/io.jxcore.node.IncomingSocketThread( 3286): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 324
,D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 324, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3286): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 325, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 324, name: Sender)
,W/bt-rfcomm( 2143): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
,W/bt-rfcomm( 2143): RFCOMM_DisconnectInd LCID:0x46
,I/jxcore-log( 3286): 2015-12-19T00:30:07.286Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3286): 
,D/btif_config_util( 2143): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2143): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2143): onReceive
,I/BTConnectionReceiver( 1379): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1379): Bluetooth Device Name: HTC One M8s
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): checkListForExpiredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Removed [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
,I/io.jxcore.node.ConnectionHelper( 3286): onPeerLost: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] removed
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] not available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC-HTC One M8s_PT6420","peerAvailable":false}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,W/bt-btif ( 2143): info:x10
,D/        ( 2143): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2143): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2143): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2143): Entering PendingCommandState State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
D/BluetoothAdapterProperties( 2143): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2143): StableState(): Entering Off State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
E/BluetoothEventManager( 2747): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection initialized (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 326)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): onBytesRead: Read 77 bytes successfully (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): onBytesWritten: 77 bytes successfully written (thread ID: 326)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): removeThreadFromList: Removing thread with ID 326
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Handshake thread disposed (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 326)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Incoming connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] is available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT2685","peerAvailable":true}]
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): Found peer : LGE-LG-H815_PT2685, Available: true
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): device[3]: F8:95:C7:87:3C:51
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:31:02.473Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:31:02.473Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:31:02.473Z SendDataConnector.js: do connect now
I/jxcore-log( 3286): 
,I/io.jxcore.node.ConnectionHelper( 3286): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): connect: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnecting: G4-1 F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3286): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Incoming socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], created successfully
D/io.jxcore.node.ConnectionHelper( 3286): onConnected: The total number of connections is now 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 327)
W/BluetoothAdapter( 3286): getBluetoothService() called with no BluetoothManagerCallback
D/io.jxcore.node.IncomingSocketThread( 3286): Entering thread (ID: 328)
,D/BTIF_SOCK( 2143): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/io.jxcore.node.IncomingSocketThread( 3286): Local host address: localhost/127.0.0.1, port: 43481
D/io.jxcore.node.IncomingSocketThread( 3286): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3286): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3286): Exiting thread (ID: 328)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 330, name: Receiver)
I/jxcore-log( 3286): 2015-12-19T00:31:02.480Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3286): 
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 329, name: Sender)
,W/bt-sdp  ( 2143): process_service_search_attr_rsp
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onSocketConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 327)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesWritten: 77 bytes successfully written (thread ID: 331),
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Outgoing connection initialized (*handshake* thread ID: 331)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Exiting thread (thread ID: 327)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 331)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesRead: Read 77 bytes successfully (thread ID: 331)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Handshake succeeded with [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onHandshakeSucceeded: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 331)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: We have an incoming connection with peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 3286): onConnected: Already connected with peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 3286): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 3286): Entering thread (ID: 332)
,D/io.jxcore.node.OutgoingSocketThread( 3286): Server socket local port: 46143
,I/io.jxcore.node.OutgoingSocketThread( 3286): Now accepting connections...
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/io.jxcore.node.ConnectionHelper( 3286): onListeningForIncomingConnections: Outgoing connection is using port 46143 (peer ID: F8:95:C7:87:3C:51)
,I/jxcore-log( 3286): 2015-12-19T00:31:02.927Z SendDataConnector.js: CLIENT connected to 46143, error: null
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:02.927Z SendDataConnector.js: CLIENT starting client ,
I/jxcore-log( 3286): 
,I/io.jxcore.node.OutgoingSocketThread( 3286): Incoming data from address: /127.0.0.1, port: 46143
D/io.jxcore.node.OutgoingSocketThread( 3286): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3286): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3286): Exiting thread (ID: 332)
I/jxcore-log( 3286): 2015-12-19T00:31:02.955Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3286): 
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 334, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 333, name: Sender)
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3286): 2015-12-19T00:31:03.376Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:03.405Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:03.443Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:03.581Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:03.649Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:03.698Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3286): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3286): 2015-12-19T00:31:03.894Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:03.933Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:04.166Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3286): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3286): 2015-12-19T00:31:04.319Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3286): 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3286): 2015-12-19T00:31:04.910Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:05.059Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:05.102Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3286): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3286): 2015-12-19T00:31:05.307Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:05.346Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:05.375Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:05.424Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:05.474Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:05.541Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3286): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/jxcore-log( 3286): 2015-12-19T00:31:05.619Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:05.671Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:05.736Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:05.746Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:05.754Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:05.776Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:05.805Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:05.829Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:05.832Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:05.837Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3286): 
I/jxcore-log( 3286): oneRoundDownNow
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:31:05.839Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:31:05.840Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3286): 
,D/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
,I/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread( 3286): close
,D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 334
D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 333
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 333, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3286): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 334, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:3C:51
,E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 333, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 334, name: Receiver)
,I/jxcore-log( 3286): 2015-12-19T00:31:05.880Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): ---- round done--------
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:05.883Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:05.972Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:06.003Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:06.008Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:06.016Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:06.020Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:06.051Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:06.156Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:06.174Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/jxcore-log( 3286): 2015-12-19T00:31:06.208Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:06.321Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:06.354Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:06.375Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:06.411Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:06.453Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:06.519Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:06.694Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:06.748Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:06.907Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:07.082Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): invalid rfc slot id: 8
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 330, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3286): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 328
D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 330
D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 329
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 329, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3286): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 329, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 330, name: Receiver)
,I/jxcore-log( 3286): 2015-12-19T00:31:07.271Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3286): 
,W/bt-rfcomm( 2143): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 2143): RFCOMM_DisconnectInd LCID:0x48
,D/btif_config_util( 2143): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2143): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2143): onReceive
,I/BTConnectionReceiver( 1379): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1379): Bluetooth Device Name: G4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2143): info:x10
,D/        ( 2143): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2143): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 2143): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2143): Entering PendingCommandState State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2143): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2143): StableState(): Entering Off State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection initialized (thread ID: 335)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 335)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): onBytesRead: Read 81 bytes successfully (thread ID: 335)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Got valid identity from [44:80:EB:7B:5A:05 motorola-XT1072_PT5534]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): onBytesWritten: 77 bytes successfully written (thread ID: 335)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): removeThreadFromList: Removing thread with ID 335
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Handshake thread disposed (thread ID: 335)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onIncomingConnectionConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT5534]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 335)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT5534]
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Incoming connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT5534]
,D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT5534] is available
,I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"motorola-XT1072_PT5534","peerAvailable":true}]
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): Found peer : motorola-XT1072_PT5534, Available: true
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): device[4]: 44:80:EB:7B:5A:05
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:44.012Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:44.015Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:44.017Z SendDataConnector.js: do connect now
I/jxcore-log( 3286): 
,I/io.jxcore.node.ConnectionHelper( 3286): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): connect: [44:80:EB:7B:5A:05 motorola-XT1072_PT5534]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnecting: XT1072 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
,I/io.jxcore.node.ConnectionHelper( 3286): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
,I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Incoming socket thread, for peer [44:80:EB:7B:5A:05 motorola-XT1072_PT5534], created successfully
D/io.jxcore.node.ConnectionHelper( 3286): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3286): Entering thread (ID: 337)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 336)
W/BluetoothAdapter( 3286): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2143): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/io.jxcore.node.IncomingSocketThread( 3286): Local host address: localhost/127.0.0.1, port: 43481
D/io.jxcore.node.IncomingSocketThread( 3286): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3286): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3286): Exiting thread (ID: 337)
,I/jxcore-log( 3286): 2015-12-19T00:31:44.061Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3286): 
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 339, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 338, name: Sender)
,W/bt-sdp  ( 2143): process_service_search_attr_rsp
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onSocketConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT5534]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 336)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesWritten: 77 bytes successfully written (thread ID: 340)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Outgoing connection initialized (*handshake* thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Exiting thread (thread ID: 336)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 340)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesRead: Read 81 bytes successfully (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT5534]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onHandshakeSucceeded: [44:80:EB:7B:5A:05 motorola-XT1072_PT5534]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT5534]
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT5534]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: We have an incoming connection with peer with ID 44:80:EB:7B:5A:05
W/io.jxcore.node.ConnectionHelper( 3286): onConnected: Already connected with peer [44:80:EB:7B:5A:05 motorola-XT1072_PT5534], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT5534] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing socket thread, for peer [44:80:EB:7B:5A:05 motorola-XT1072_PT5534], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3286): onConnected: The total number of connections is now 2
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 340)
,D/io.jxcore.node.OutgoingSocketThread( 3286): Entering thread (ID: 341)
D/io.jxcore.node.OutgoingSocketThread( 3286): Server socket local port: 37397
I/io.jxcore.node.OutgoingSocketThread( 3286): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3286): onListeningForIncomingConnections: Outgoing connection is using port 37397 (peer ID: 44:80:EB:7B:5A:05)
I/jxcore-log( 3286): 2015-12-19T00:31:44.467Z SendDataConnector.js: CLIENT connected to 37397, error: null
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:31:44.468Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3286): 
,I/io.jxcore.node.OutgoingSocketThread( 3286): Incoming data from address: /127.0.0.1, port: 37397
D/io.jxcore.node.OutgoingSocketThread( 3286): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3286): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3286): Exiting thread (ID: 341)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 343, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 342, name: Sender)
,I/jxcore-log( 3286): 2015-12-19T00:31:44.511Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:44.973Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:44.977Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:45.013Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:45.017Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:45.063Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:45.113Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:45.143Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:45.159Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:45.237Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:45.269Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3286): 
,D/        ( 2143): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3286): 2015-12-19T00:31:45.351Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:45.407Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:45.445Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:45.490Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:45.511Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:45.520Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:45.527Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:45.540Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:45.576Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:45.582Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:45.675Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:45.685Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3286): 
,D/        ( 2143): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 3286): 2015-12-19T00:31:45.720Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:45.772Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:45.908Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.045Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.077Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.132Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.140Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.166Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.169Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.186Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.199Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.239Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.305Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3286): 
,D/        ( 2143): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3286): 2015-12-19T00:31:46.327Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.332Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.383Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.394Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.506Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.544Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.612Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.678Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.762Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.778Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.791Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.827Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.836Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.843Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.875Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.899Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.941Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:46.952Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): invalid rfc slot id: 9
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 339, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3286): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Incoming connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT5534] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 337
D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 339
D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 338
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 338, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Incoming connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT5534] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3286): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 338, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 339, name: Receiver)
,I/jxcore-log( 3286): 2015-12-19T00:31:47.441Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:31:47.519Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:31:47.519Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3286): 
I/jxcore-log( 3286): oneRoundDownNow
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:31:47.519Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:31:47.520Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3286): 
D/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 44:80:EB:7B:5A:05
I/io.jxcore.node.OutgoingSocketThread( 3286): close
D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 343
D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 342
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 342, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT5534] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3286): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 343, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT5534] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Successfully disconnected (peer ID: 44:80:EB:7B:5A:05
,E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 342, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 343, name: Receiver)
,I/jxcore-log( 3286): 2015-12-19T00:31:47.525Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3286): 
I/jxcore-log( 3286): ---- round done--------
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,D/btif_config_util( 2143): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2143): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2143): onReceive
,I/BTConnectionReceiver( 1379): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1379): Bluetooth Device Name: XT1072
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  755): Killing 2615:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10070/pid_2615/cgroup.procs: No such file or directory
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7600","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3595","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
,I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] is available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT3595","peerAvailable":true}]
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): Found peer : samsung-SM-N910C_PT3595, Available: true
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
I/jxcore-log( 3286): device[5]: E0:DB:10:14:E2:C0
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:32:44.107Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:32:44.108Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:32:44.109Z SendDataConnector.js: do connect now
I/jxcore-log( 3286): 
I/io.jxcore.node.ConnectionHelper( 3286): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): connect: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnecting: null E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Started connecting to null in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3286): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 344)
,W/BluetoothAdapter( 3286): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2143): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2143): info:x10
,D/        ( 2143): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2143): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2143): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 2143): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2143): Entering PendingCommandState State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2143): Failed to remove device: E0:DB:10:14:E2:C0
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2143): StableState(): Entering Off State
,E/BluetoothEventManager( 2747): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onSocketConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 344)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesWritten: 77 bytes successfully written (thread ID: 345)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Outgoing connection initialized (*handshake* thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Exiting thread (thread ID: 344)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 345)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesRead: Read 82 bytes successfully (thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onHandshakeSucceeded: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 345)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing socket thread, for peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3286): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3286): Entering thread (ID: 346)
D/io.jxcore.node.OutgoingSocketThread( 3286): Server socket local port: 36235
I/io.jxcore.node.OutgoingSocketThread( 3286): Now accepting connections...
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection initialized (thread ID: 347)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 347)
,I/io.jxcore.node.ConnectionHelper( 3286): onListeningForIncomingConnections: Outgoing connection is using port 36235 (peer ID: E0:DB:10:14:E2:C0)
I/jxcore-log( 3286): 2015-12-19T00:32:49.428Z SendDataConnector.js: CLIENT connected to 36235, error: null
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:32:49.428Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3286): 
,I/io.jxcore.node.OutgoingSocketThread( 3286): Incoming data from address: /127.0.0.1, port: 36235
,D/io.jxcore.node.OutgoingSocketThread( 3286): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3286): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3286): Exiting thread (ID: 346)
,I/jxcore-log( 3286): 2015-12-19T00:32:49.432Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3286): 
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 349, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 348, name: Sender)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): onBytesRead: Read 82 bytes successfully (thread ID: 347)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Got valid identity from [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): onBytesWritten: 77 bytes successfully written (thread ID: 347)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): removeThreadFromList: Removing thread with ID 347
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Handshake thread disposed (thread ID: 347)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 347)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Incoming connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: We have an outgoing connection with peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 3286): onConnected: Already connected with peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Incoming socket thread, for peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], created successfully
D/io.jxcore.node.ConnectionHelper( 3286): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 3286): Entering thread (ID: 350)
,I/io.jxcore.node.IncomingSocketThread( 3286): Local host address: localhost/127.0.0.1, port: 43481
,D/io.jxcore.node.IncomingSocketThread( 3286): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3286): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3286): Exiting thread (ID: 350)
I/jxcore-log( 3286): 2015-12-19T00:32:49.927Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3286): 
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 352, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 351, name: Sender)
,I/jxcore-log( 3286): 2015-12-19T00:32:50.355Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.405Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.416Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.420Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.457Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.470Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.483Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.510Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.519Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.520Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.552Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.567Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:32:50.567Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3286): 
I/jxcore-log( 3286): oneRoundDownNow
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:32:50.569Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:32:50.569Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3286): 
,D/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
I/io.jxcore.node.IncomingSocketThread( 3286): close
,D/io.jxcore.node.IncomingSocketThread( 3286): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 349
D/io.jxcore.node.IncomingSocketThread( 3286): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 348
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 348, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3286): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 349, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Successfully disconnected (peer ID: E0:DB:10:14:E2:C0
,E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 348, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 349, name: Receiver)
,I/jxcore-log( 3286): 2015-12-19T00:32:50.628Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3286): 
I/jxcore-log( 3286): ---- round done--------
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.631Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.635Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.644Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.683Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.705Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,I/jxcore-log( 3286): 2015-12-19T00:32:50.743Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.764Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.792Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.824Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.831Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.865Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.873Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.879Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.914Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.927Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.936Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.947Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:50.986Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:51.000Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:32:51.027Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): invalid rfc slot id: 11
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 352, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3286): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 350
D/io.jxcore.node.IncomingSocketThread( 3286): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 352
D/io.jxcore.node.IncomingSocketThread( 3286): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 351
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 351, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 3286): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 352, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 351, name: Sender)
,I/jxcore-log( 3286): 2015-12-19T00:32:51.171Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3286): 
,D/btif_config_util( 2143): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,E/bt-btm  ( 2143): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2143): onReceive
,I/BTConnectionReceiver( 1379): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1379): Bluetooth Device Name: Note4-1
,D/WifiP2pManager( 3286): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): checkListForExpiredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerLost: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] removed
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] not available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT7600","peerAvailable":false}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): info:x10
,D/        ( 2143): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2143): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 2143): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2143): Entering PendingCommandState State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2143): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2143): StableState(): Entering Off State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection initialized (thread ID: 353)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 353)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): onBytesRead: Read 82 bytes successfully (thread ID: 353)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): onBytesWritten: 77 bytes successfully written (thread ID: 353)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): removeThreadFromList: Removing thread with ID 353
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Handshake thread disposed (thread ID: 353)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Incoming connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] is available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT6107","peerAvailable":true}]
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): Found peer : samsung-SM-G900F_PT6107, Available: true
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
I/jxcore-log( 3286): device[6]: B0:C5:59:3F:75:69
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:33:28.251Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:33:28.251Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:28.251Z SendDataConnector.js: do connect now
I/jxcore-log( 3286): 
I/io.jxcore.node.ConnectionHelper( 3286): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): connect: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Trying to start connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnecting: Thali Test (Galaxy S5) B0:C5:59:3F:75:69
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Started connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3286): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Incoming socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], created successfully
D/io.jxcore.node.ConnectionHelper( 3286): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 353)
,D/io.jxcore.node.IncomingSocketThread( 3286): Entering thread (ID: 355)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 354)
W/BluetoothAdapter( 3286): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2143): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3286): 2015-12-19T00:33:28.261Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3286): 
,I/io.jxcore.node.IncomingSocketThread( 3286): Local host address: localhost/127.0.0.1, port: 43481
D/io.jxcore.node.IncomingSocketThread( 3286): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3286): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3286): Exiting thread (ID: 355)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 356, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 357, name: Receiver)
,W/bt-sdp  ( 2143): process_service_search_attr_rsp
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onSocketConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 354)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesWritten: 77 bytes successfully written (thread ID: 358)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Outgoing connection initialized (*handshake* thread ID: 358)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Exiting thread (thread ID: 354)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 358)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesRead: Read 82 bytes successfully (thread ID: 358)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onHandshakeSucceeded: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 358)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: We have an incoming connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 3286): onConnected: Already connected with peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3286): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 3286): Entering thread (ID: 359)
D/io.jxcore.node.OutgoingSocketThread( 3286): Server socket local port: 53408
I/io.jxcore.node.OutgoingSocketThread( 3286): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3286): onListeningForIncomingConnections: Outgoing connection is using port 53408 (peer ID: B0:C5:59:3F:75:69)
I/jxcore-log( 3286): 2015-12-19T00:33:28.626Z SendDataConnector.js: CLIENT connected to 53408, error: null
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:33:28.626Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3286): 
,I/io.jxcore.node.OutgoingSocketThread( 3286): Incoming data from address: /127.0.0.1, port: 53408
D/io.jxcore.node.OutgoingSocketThread( 3286): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3286): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3286): Exiting thread (ID: 359)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 361, name: Receiver)
,I/jxcore-log( 3286): 2015-12-19T00:33:28.655Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3286): 
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 360, name: Sender)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3286): 2015-12-19T00:33:29.221Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:29.293Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:29.315Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:29.370Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
,I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:29.421Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:29.464Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:29.486Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:29.527Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:29.551Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:33:29.555Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:29.563Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:29.805Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:30.277Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:30.566Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:30.725Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:30.804Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:30.867Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:30.914Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:30.947Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:30.979Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:30.993Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:31.119Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3286): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3286): 2015-12-19T00:33:31.297Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:31.334Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:31.341Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:31.398Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:31.404Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:31.439Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:31.472Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:31.505Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:31.537Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:33:31.538Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3286): 
I/jxcore-log( 3286): oneRoundDownNow
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:33:31.540Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:33:31.540Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3286): 
,D/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: B0:C5:59:3F:75:69
I/io.jxcore.node.OutgoingSocketThread( 3286): close
D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 361
D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 360
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 360, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3286): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 361, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Successfully disconnected (peer ID: B0:C5:59:3F:75:69
,E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 360, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 361, name: Receiver)
,I/jxcore-log( 3286): 2015-12-19T00:33:31.588Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): ---- round done--------
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:31.589Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:31.622Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:31.654Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3286): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3286): 2015-12-19T00:33:31.693Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:31.718Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:31.797Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:31.806Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,I/jxcore-log( 3286): 2015-12-19T00:33:31.821Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:31.857Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:31.878Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:31.910Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:31.918Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:32.059Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:32.128Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:32.162Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:32.187Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:32.226Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3286): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3286): 2015-12-19T00:33:32.250Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:32.261Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:32.301Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:32.339Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:32.375Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:33:32.382Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): invalid rfc slot id: 14
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 357, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3286): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 355
,D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 357
D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 356
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 356, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3286): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 356, name: Sender)
,W/bt-rfcomm( 2143): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 2143): RFCOMM_DisconnectInd LCID:0x42
,D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 357, name: Receiver)
,I/jxcore-log( 3286): 2015-12-19T00:33:32.493Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3286): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2143): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2143): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2143): onReceive
,I/BTConnectionReceiver( 1379): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1379): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): checkListForExpiredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Removed [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerLost: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] removed
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] not available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT3595","peerAvailable":false}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7127","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] is available
,I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"LGE-LG-D855_PT7127","peerAvailable":true}]
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): Found peer : LGE-LG-D855_PT7127, Available: true
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): device[7]: 58:3F:54:73:64:C0
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:35:05.085Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:35:05.085Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:35:05.086Z SendDataConnector.js: do connect now
I/jxcore-log( 3286): 
I/io.jxcore.node.ConnectionHelper( 3286): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): connect: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnecting: null 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Started connecting to null in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3286): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 362)
W/BluetoothAdapter( 3286): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2143): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2143): info:x10
,D/        ( 2143): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2143): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2143): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 2143): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2143): Entering PendingCommandState State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2143): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2143): StableState(): Entering Off State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onSocketConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 362)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesWritten: 77 bytes successfully written (thread ID: 363)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Outgoing connection initialized (*handshake* thread ID: 363)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Exiting thread (thread ID: 362)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 363)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesRead: Read 77 bytes successfully (thread ID: 363)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Handshake succeeded with [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onHandshakeSucceeded: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 363)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing connection to peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing socket thread, for peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3286): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3286): Entering thread (ID: 364)
D/io.jxcore.node.OutgoingSocketThread( 3286): Server socket local port: 35443
I/io.jxcore.node.OutgoingSocketThread( 3286): Now accepting connections...
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection initialized (thread ID: 365)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 365)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): onBytesRead: Read 77 bytes successfully (thread ID: 365)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Got valid identity from [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): onBytesWritten: 77 bytes successfully written (thread ID: 365)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): removeThreadFromList: Removing thread with ID 365
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Handshake thread disposed (thread ID: 365)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onIncomingConnectionConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 365)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Incoming connection to peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: We have an outgoing connection with peer with ID 58:3F:54:73:64:C0
,W/io.jxcore.node.ConnectionHelper( 3286): onConnected: Already connected with peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Incoming socket thread, for peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], created successfully
D/io.jxcore.node.ConnectionHelper( 3286): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 3286): Entering thread (ID: 366)
,I/io.jxcore.node.IncomingSocketThread( 3286): Local host address: localhost/127.0.0.1, port: 43481
D/io.jxcore.node.IncomingSocketThread( 3286): Setting local streams and starting stream copying threads...
,I/jxcore-log( 3286): 2015-12-19T00:35:06.454Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3286): 
,I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.ConnectionHelper( 3286): onListeningForIncomingConnections: Outgoing connection is using port 35443 (peer ID: 58:3F:54:73:64:C0)
,I/jxcore-log( 3286): 2015-12-19T00:35:06.468Z SendDataConnector.js: CLIENT connected to 35443, error: null
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:35:06.468Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3286): 
,I/io.jxcore.node.IncomingSocketThread( 3286): Incoming data from address: /127.0.0.1, port: 35443
D/io.jxcore.node.IncomingSocketThread( 3286): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3286): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3286): Exiting thread (ID: 364)
,I/jxcore-log( 3286): 2015-12-19T00:35:06.472Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3286): 
,I/io.jxcore.node.IncomingSocketThread( 3286): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3286): Exiting thread (ID: 366)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 370, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 369, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 368, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 367, name: Sender)
,D/        ( 2143): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,D/        ( 2143): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11836
,I/jxcore-log( 3286): 2015-12-19T00:35:07.499Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:07.507Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:07.539Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:07.802Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:07.814Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:07.822Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:07.831Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:07.849Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:07.860Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:07.860Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3286): 
I/jxcore-log( 3286): oneRoundDownNow
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:35:07.861Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:35:07.861Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3286): 
D/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
,I/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 58:3F:54:73:64:C0
I/io.jxcore.node.IncomingSocketThread( 3286): close
D/io.jxcore.node.IncomingSocketThread( 3286): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 370
D/io.jxcore.node.IncomingSocketThread( 3286): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 369
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 369, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3286): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 370, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Successfully disconnected (peer ID: 58:3F:54:73:64:C0
,E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 369, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 370, name: Receiver)
,I/jxcore-log( 3286): 2015-12-19T00:35:07.867Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3286): 
I/jxcore-log( 3286): ---- round done--------
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:07.883Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:07.901Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,I/jxcore-log( 3286): 2015-12-19T00:35:07.934Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:07.936Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:07.939Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:07.974Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:07.988Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:08.017Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:08.059Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:08.065Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:08.070Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:08.105Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:08.167Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:08.248Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:08.406Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:08.446Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:08.461Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:08.466Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:08.507Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:08.515Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:08.521Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:08.533Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:08.559Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:08.563Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:08.572Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:35:08.603Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): invalid rfc slot id: 15
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 368, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3286): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 366
D/io.jxcore.node.IncomingSocketThread( 3286): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 368
D/io.jxcore.node.IncomingSocketThread( 3286): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 367
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3286): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 368, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 367, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 367, name: Sender)
,I/jxcore-log( 3286): 2015-12-19T00:35:08.612Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3286): 
,D/btif_config_util( 2143): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2143): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2143): onReceive
,I/BTConnectionReceiver( 1379): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1379): Bluetooth Device Name: G3-1
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7600","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
,I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] is available
,I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT7600","peerAvailable":true}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2588","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] is available
,I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT2588","peerAvailable":true}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): Found peer : samsung-SM-A300FU_PT2588, Available: true
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): device[8]: 08:EC:A9:50:75:41
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:36:08.689Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:36:08.690Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:36:08.690Z SendDataConnector.js: do connect now
I/jxcore-log( 3286): 
I/io.jxcore.node.ConnectionHelper( 3286): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
,D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): connect: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3286): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 371)
W/BluetoothAdapter( 3286): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2143): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2143): info:x10
,D/        ( 2143): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2143): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2143): process_service_search_attr_rsp
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7600","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] already in the list, will not add again
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 2143): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2143): Entering PendingCommandState State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2143): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2143): StableState(): Entering Off State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onSocketConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 371)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesWritten: 77 bytes successfully written (thread ID: 372)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Outgoing connection initialized (*handshake* thread ID: 372)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Exiting thread (thread ID: 371)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 372)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesRead: Read 83 bytes successfully (thread ID: 372)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onHandshakeSucceeded: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 372)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3286): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3286): Entering thread (ID: 373)
D/io.jxcore.node.OutgoingSocketThread( 3286): Server socket local port: 51992
I/io.jxcore.node.OutgoingSocketThread( 3286): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3286): onListeningForIncomingConnections: Outgoing connection is using port 51992 (peer ID: 08:EC:A9:50:75:41)
I/jxcore-log( 3286): 2015-12-19T00:36:10.366Z SendDataConnector.js: CLIENT connected to 51992, error: null
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:36:10.367Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3286): 
,I/io.jxcore.node.OutgoingSocketThread( 3286): Incoming data from address: /127.0.0.1, port: 51992
D/io.jxcore.node.OutgoingSocketThread( 3286): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3286): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3286): Exiting thread (ID: 373)
,I/jxcore-log( 3286): 2015-12-19T00:36:10.389Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3286): 
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 374, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 375, name: Receiver)
,D/        ( 2143): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3286): 2015-12-19T00:36:10.918Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:11.110Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3286): 
,D/        ( 2143): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 3286): 2015-12-19T00:36:11.266Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:11.309Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3286): 
,D/        ( 2143): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2926
,I/jxcore-log( 3286): 2015-12-19T00:36:11.370Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:11.475Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:11.498Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:11.537Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:11.639Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:11.778Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:36:11.779Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3286): 
I/jxcore-log( 3286): oneRoundDownNow
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:36:11.780Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:36:11.780Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3286): 
,D/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
,I/io.jxcore.node.OutgoingSocketThread( 3286): close
D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 375
D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 374
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 374, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3286): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 375, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:75:41
,E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 375, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 374, name: Sender)
,I/jxcore-log( 3286): 2015-12-19T00:36:11.832Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): ---- round done--------
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6107","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2685","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3595","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] is available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT3595","peerAvailable":true}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,D/btif_config_util( 2143): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2143): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2143): onReceive
,I/BTConnectionReceiver( 1379): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1379): Bluetooth Device Name: A3-1
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT838","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] is available
,I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT838","peerAvailable":true}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): Found peer : samsung-SM-G900F_PT838, Available: true
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
I/jxcore-log( 3286): device[9]: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:36:27.862Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:27.862Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:36:27.863Z SendDataConnector.js: do connect now
I/jxcore-log( 3286): 
I/io.jxcore.node.ConnectionHelper( 3286): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): connect: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3286): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 376)
W/BluetoothAdapter( 3286): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2143): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2457","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] is available
,I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT2457","peerAvailable":true}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): Found peer : LGE-LG-D722_PT2457, Available: true
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): info:x10
,D/        ( 2143): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2143): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2143): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 2143): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2143): Entering PendingCommandState State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2143): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2143): StableState(): Entering Off State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onSocketConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 376)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesWritten: 77 bytes successfully written (thread ID: 377)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Outgoing connection initialized (*handshake* thread ID: 377)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Exiting thread (thread ID: 376)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 377)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesRead: Read 81 bytes successfully (thread ID: 377)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Handshake succeeded with [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onHandshakeSucceeded: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 377)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing socket thread, for peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3286): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3286): Entering thread (ID: 378)
D/io.jxcore.node.OutgoingSocketThread( 3286): Server socket local port: 59693
I/io.jxcore.node.OutgoingSocketThread( 3286): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3286): onListeningForIncomingConnections: Outgoing connection is using port 59693 (peer ID: 7C:F9:0E:34:8A:A0)
I/jxcore-log( 3286): 2015-12-19T00:36:30.276Z SendDataConnector.js: CLIENT connected to 59693, error: null
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:36:30.277Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3286): 
,I/io.jxcore.node.OutgoingSocketThread( 3286): Incoming data from address: /127.0.0.1, port: 59693
D/io.jxcore.node.OutgoingSocketThread( 3286): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3286): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3286): Exiting thread (ID: 378)
,I/jxcore-log( 3286): 2015-12-19T00:36:30.303Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3286): 
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 379, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 380, name: Receiver)
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection initialized (thread ID: 381)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 381)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): onBytesRead: Read 81 bytes successfully (thread ID: 381)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Got valid identity from [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): onBytesWritten: 77 bytes successfully written (thread ID: 381)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): removeThreadFromList: Removing thread with ID 381
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Handshake thread disposed (thread ID: 381)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onIncomingConnectionConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 381)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Incoming connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
,D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: We have an outgoing connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 3286): onConnected: Already connected with peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Incoming socket thread, for peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], created successfully
D/io.jxcore.node.ConnectionHelper( 3286): onConnected: The total number of connections is now 2
D/io.jxcore.node.IncomingSocketThread( 3286): Entering thread (ID: 382)
,I/io.jxcore.node.IncomingSocketThread( 3286): Local host address: localhost/127.0.0.1, port: 43481
D/io.jxcore.node.IncomingSocketThread( 3286): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3286): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3286): Exiting thread (ID: 382)
,I/jxcore-log( 3286): 2015-12-19T00:36:30.744Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3286): 
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 384, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 383, name: Sender)
,I/jxcore-log( 3286): 2015-12-19T00:36:31.018Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:31.517Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:31.542Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:31.550Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:31.558Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:36:31.561Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:31.571Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:31.582Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:31.592Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:31.606Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:31.623Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:31.630Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:31.663Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:31.687Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:36:31.687Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3286): 
I/jxcore-log( 3286): oneRoundDownNow
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:36:31.688Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:36:31.688Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3286): 
D/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:34:8A:A0
I/io.jxcore.node.IncomingSocketThread( 3286): close
D/io.jxcore.node.IncomingSocketThread( 3286): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 380
D/io.jxcore.node.IncomingSocketThread( 3286): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 379
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 379, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3286): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 380, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 379, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 380, name: Receiver)
,I/jxcore-log( 3286): 2015-12-19T00:36:31.694Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3286): 
I/jxcore-log( 3286): ---- round done--------
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
I/jxcore-log( 3286): device[10]: F8:95:C7:87:85:54
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:36:31.695Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:36:31.695Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:36:31.695Z SendDataConnector.js: do connect now
I/jxcore-log( 3286): 
,I/io.jxcore.node.ConnectionHelper( 3286): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): connect: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnecting: null F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3286): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 385)
W/BluetoothAdapter( 3286): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2143): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3286): 2015-12-19T00:36:31.756Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:31.827Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:32.047Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:32.060Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:32.099Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:32.110Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
,I/jxcore-log( 3286): 2015-12-19T00:36:32.150Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:32.190Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:32.204Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:32.359Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:32.366Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:32.396Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:32.435Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:32.450Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): info:x10
,D/        ( 2143): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2143): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3286): 2015-12-19T00:36:32.557Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:32.595Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:32.660Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:32.692Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3286): 
,E/bt-btm  ( 2143): tBTM_SEC_DEV:0xa4051ec4 rs_disc_pending=1
W/bt-btif ( 2143): bta_dm_check_av:0
,W/bt-btif ( 2143): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3286): 2015-12-19T00:36:32.780Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:32.831Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:32.843Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:32.894Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:32.917Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3286): 
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 384, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3286): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 382
D/io.jxcore.node.IncomingSocketThread( 3286): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 384
D/io.jxcore.node.IncomingSocketThread( 3286): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 383
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3286): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 384, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 383, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 383, name: Sender)
,W/bt-btif ( 2143): invalid rfc slot id: 18
,I/jxcore-log( 3286): 2015-12-19T00:36:33.047Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3286): 
,W/bt-sdp  ( 2143): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2143): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2143): Entering PendingCommandState State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2143): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2143): StableState(): Entering Off State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onSocketConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 385)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesWritten: 77 bytes successfully written (thread ID: 386)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Outgoing connection initialized (*handshake* thread ID: 386)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Exiting thread (thread ID: 385)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 386)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesRead: Read 77 bytes successfully (thread ID: 386)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Handshake succeeded with [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onHandshakeSucceeded: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 386)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3286): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3286): Entering thread (ID: 387)
,D/io.jxcore.node.OutgoingSocketThread( 3286): Server socket local port: 56101
I/io.jxcore.node.OutgoingSocketThread( 3286): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3286): onListeningForIncomingConnections: Outgoing connection is using port 56101 (peer ID: F8:95:C7:87:85:54)
I/jxcore-log( 3286): 2015-12-19T00:36:34.259Z SendDataConnector.js: CLIENT connected to 56101, error: null
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:36:34.260Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3286): 
,I/io.jxcore.node.OutgoingSocketThread( 3286): Incoming data from address: /127.0.0.1, port: 56101
D/io.jxcore.node.OutgoingSocketThread( 3286): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3286): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread( 3286): Exiting thread (ID: 387)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 389, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 388, name: Sender)
,I/jxcore-log( 3286): 2015-12-19T00:36:34.307Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3286): 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): checkListForExpiredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Removed [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerLost: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] removed
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] not available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"LGE-LG-D855_PT7127","peerAvailable":false}]
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:35.406Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:35.545Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:35.885Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:36.052Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:36.208Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:36.365Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:36.487Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:36.668Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:36.860Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:36:36.904Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:36:36.905Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3286): 
I/jxcore-log( 3286): oneRoundDownNow
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:36:36.907Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:36:36.907Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3286): 
D/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:85:54
I/io.jxcore.node.OutgoingSocketThread( 3286): close
D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 389
D/io.jxcore.node.OutgoingSocketThread( 3286): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 388
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 388, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3286): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3286): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 389, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:85:54
,E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 389, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 388, name: Sender)
,W/bt-btif ( 2143): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,I/jxcore-log( 3286): 2015-12-19T00:36:36.959Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3286): 
I/jxcore-log( 3286): ---- round done--------
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,E/bt-btm  ( 2143): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2143): onReceive
,I/BTConnectionReceiver( 1379): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1379): Bluetooth Device Name: S5-1
,D/btif_config_util( 2143): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2143): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2143): onReceive
,I/BTConnectionReceiver( 1379): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1379): Bluetooth Device Name: G3s-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6283","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] is available
,I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT6283","peerAvailable":true}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): Found peer : samsung-SM-A500FU_PT6283, Available: true
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): device[11]: 7C:F9:0E:37:96:AB
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:06.461Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:06.466Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:37:06.466Z SendDataConnector.js: do connect now
I/jxcore-log( 3286): 
I/io.jxcore.node.ConnectionHelper( 3286): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): connect: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3286): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 390)
W/BluetoothAdapter( 3286): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2143): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2143): info:x10
,D/        ( 2143): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2143): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2143): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 2143): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11,
I/BluetoothBondStateMachine( 2143): Entering PendingCommandState State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2143): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2143): StableState(): Entering Off State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onSocketConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 390)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesWritten: 77 bytes successfully written (thread ID: 391)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Outgoing connection initialized (*handshake* thread ID: 391)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Exiting thread (thread ID: 390)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 391)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): onBytesRead: Read 83 bytes successfully (thread ID: 391)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3286): Handshake succeeded with [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onHandshakeSucceeded: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Outgoing socket thread, for peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3286): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 391)
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection initialized (thread ID: 393)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Waiting for incoming connections...
,D/io.jxcore.node.OutgoingSocketThread( 3286): Entering thread (ID: 392)
,D/io.jxcore.node.OutgoingSocketThread( 3286): Server socket local port: 50452
I/io.jxcore.node.OutgoingSocketThread( 3286): Now accepting connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 393)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): onBytesRead: Read 83 bytes successfully (thread ID: 393)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): onBytesWritten: 77 bytes successfully written (thread ID: 393)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): removeThreadFromList: Removing thread with ID 393
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Handshake thread disposed (thread ID: 393)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 393)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Incoming connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: We have an outgoing connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 3286): onConnected: Already connected with peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Incoming socket thread, for peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], created successfully
D/io.jxcore.node.ConnectionHelper( 3286): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 3286): Entering thread (ID: 394)
,I/jxcore-log( 3286): 2015-12-19T00:37:08.625Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3286): 
,I/io.jxcore.node.IncomingSocketThread( 3286): Local host address: localhost/127.0.0.1, port: 43481
,D/io.jxcore.node.IncomingSocketThread( 3286): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3286): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3286): Exiting thread (ID: 394)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 396, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 395, name: Sender)
,I/io.jxcore.node.ConnectionHelper( 3286): onListeningForIncomingConnections: Outgoing connection is using port 50452 (peer ID: 7C:F9:0E:37:96:AB)
I/jxcore-log( 3286): 2015-12-19T00:37:08.703Z SendDataConnector.js: CLIENT connected to 50452, error: null
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:37:08.703Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3286): 
,I/io.jxcore.node.IncomingSocketThread( 3286): Incoming data from address: /127.0.0.1, port: 50452
D/io.jxcore.node.IncomingSocketThread( 3286): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3286): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3286): Exiting thread (ID: 392)
,I/jxcore-log( 3286): 2015-12-19T00:37:08.709Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3286): 
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 397, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 398, name: Receiver)
,I/jxcore-log( 3286): 2015-12-19T00:37:09.486Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:09.542Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:09.567Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:09.575Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:09.584Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:09.595Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:09.605Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:10.082Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3286): 
,D/        ( 2143): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3286): 2015-12-19T00:37:10.119Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:10.128Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:10.222Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:10.254Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:10.546Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3286): 
,D/        ( 2143): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 3286): 2015-12-19T00:37:10.775Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:10.785Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:37:10.787Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:10.830Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:10.864Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:10.968Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:11.072Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3286): 
,D/        ( 2143): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3286): 2015-12-19T00:37:11.097Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:11.264Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:11.271Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:11.383Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:11.555Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:11.568Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:11.585Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:11.587Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:11.603Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:11.690Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:11.699Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:11.808Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:11.987Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:12.013Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:12.023Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:12.028Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:12.089Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:12.103Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:12.118Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:12.128Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:37:12.129Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3286): 
I/jxcore-log( 3286): oneRoundDownNow
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:12.138Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3286): 
I/jxcore-log( 3286): 2015-12-19T00:37:12.139Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3286): 
D/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
,I/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
I/io.jxcore.node.IncomingSocketThread( 3286): close
D/io.jxcore.node.IncomingSocketThread( 3286): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 398
D/io.jxcore.node.IncomingSocketThread( 3286): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 397
,D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 397, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3286): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 398, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3286): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:37:96:AB
,E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 397, name: Sender)
E/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 398, name: Receiver)
,I/jxcore-log( 3286): 2015-12-19T00:37:12.156Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3286): 
I/jxcore-log( 3286): ---- round done--------
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:12.158Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:37:12.183Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,I/jxcore-log( 3286): 2015-12-19T00:37:12.213Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): invalid rfc slot id: 21
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 396, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3286): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 394
D/io.jxcore.node.IncomingSocketThread( 3286): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 396
D/io.jxcore.node.IncomingSocketThread( 3286): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 395
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local output stream...
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 395, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3286): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 396, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 395, name: Sender)
,I/jxcore-log( 3286): 2015-12-19T00:37:12.455Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3286): 
,D/btif_config_util( 2143): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2143): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2143): onReceive
,I/BTConnectionReceiver( 1379): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1379): Bluetooth Device Name: A5-1
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): checkListForExpiredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): checkListForExpiredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Removed [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] removed
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] not available
,I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT2588","peerAvailable":false}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
I/io.jxcore.node.ConnectionHelper( 3286): onPeerLost: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] removed
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] not available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT3595","peerAvailable":false}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
I/io.jxcore.node.ConnectionHelper( 3286): onPeerLost: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] removed
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] not available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT2457","peerAvailable":false}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
I/io.jxcore.node.ConnectionHelper( 3286): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] removed
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] not available
,I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT2685","peerAvailable":false}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6283","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6107","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
,W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6107","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6283","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
,I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] already in the list, will not add again
,W/bt-btif ( 2143): info:x10
,D/        ( 2143): remote version info [f8:95:c7:87:85:54]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1379): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1379): Bluetooth Device Name: G3s-1
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2143): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2143): Entering PendingCommandState State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2143): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2143): StableState(): Entering Off State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection initialized (thread ID: 399)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 399)
,W/bt-btif ( 2143): invalid rfc slot id: 24
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Disconnected: bt socket closed, read return: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): removeThreadFromList: Removing thread with ID 399
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Handshake failed (thread ID: 399)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 399)
,W/bt-rfcomm( 2143): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 2143): RFCOMM_DisconnectInd LCID:0x45
,E/bt-btm  ( 2143): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2143): onReceive
,I/BTConnectionReceiver( 1379): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1379): Bluetooth Device Name: G3s-1
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2143): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  988): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3286): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT6420","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
,I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] is available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC-HTC One M8s_PT6420","peerAvailable":true}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): info:x10
,D/        ( 2143): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1379): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1379): Bluetooth Device Name: G3s-1
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2143): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2143): Entering PendingCommandState State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 2143): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2143): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2143): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2143): StableState(): Entering Off State
,W/BluetoothEventManager( 2747): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2747): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 2143): new conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2143): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Incoming connection initialized (thread ID: 400)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Entering thread (ID: 400)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): onBytesRead: Read 77 bytes successfully (thread ID: 400)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): onBytesWritten: 77 bytes successfully written (thread ID: 400)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): removeThreadFromList: Removing thread with ID 400
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Handshake thread disposed (thread ID: 400)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Incoming connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] is available
,I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT2457","peerAvailable":true}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
I/io.jxcore.node.ConnectionHelper( 3286): onConnected: Incoming socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], created successfully
D/io.jxcore.node.ConnectionHelper( 3286): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3286): Exiting thread (ID: 400)
,D/io.jxcore.node.IncomingSocketThread( 3286): Entering thread (ID: 401)
,I/jxcore-log( 3286): 2015-12-19T00:38:15.632Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3286): 
,I/io.jxcore.node.IncomingSocketThread( 3286): Local host address: localhost/127.0.0.1, port: 43481
D/io.jxcore.node.IncomingSocketThread( 3286): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3286): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3286): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3286): Exiting thread (ID: 401)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 403, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3286): Entering thread (ID: 402, name: Sender)
,I/jxcore-log( 3286): 2015-12-19T00:38:16.442Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:16.452Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:16.458Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:16.502Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:16.538Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:16.582Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:16.608Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:16.643Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:16.685Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:16.737Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:16.797Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:16.802Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:16.811Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:16.839Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:16.874Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:16.885Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:16.916Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:16.941Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:16.974Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:17.034Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:17.092Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:17.101Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:17.110Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:17.146Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:17.188Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:17.249Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:17.366Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:17.404Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:17.437Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:17.484Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:17.516Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:17.557Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:17.566Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:17.597Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:38:17.624Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3286): 
,W/bt-btif ( 2143): invalid rfc slot id: 25
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 403, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3286): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 401
D/io.jxcore.node.IncomingSocketThread( 3286): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 403
D/io.jxcore.node.IncomingSocketThread( 3286): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3286): doStop: Thread ID: 402
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3286): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3286): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 403, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3286): Either failed to read from the output stream or write to the input stream (thread ID: 402, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3286): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3286): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3286): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3286): Exiting thread (ID: 402, name: Sender)
,I/jxcore-log( 3286): 2015-12-19T00:38:17.723Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3286): 
,W/bt-rfcomm( 2143): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 2143): RFCOMM_DisconnectInd LCID:0x46
,D/btif_config_util( 2143): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2143): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2143): onReceive
,I/BTConnectionReceiver( 1379): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1379): Bluetooth Device Name: G3s-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2685","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] is available
,I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT2685","peerAvailable":true}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2588","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] is available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT2588","peerAvailable":true}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6283","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT6420","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
,W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3286): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2588","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7127","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] is available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"LGE-LG-D855_PT7127","peerAvailable":true}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6283","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2457","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
,I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2685","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3595","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] is available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT3595","peerAvailable":true}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  988): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3595","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2588","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7127","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT838","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6107","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): checkListForExpiredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Removed [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerLost: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] removed
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] not available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC-HTC One M8s_PT6420","peerAvailable":false}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2588","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2685","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7600","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6107","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): checkListForExpiredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerLost: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] removed
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] not available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT838","peerAvailable":false}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 3286): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7600","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7127","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2457","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/UsageStatsService(  755): User[0] Flushing usage stats to disk
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2685","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT838","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
,I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] is available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT838","peerAvailable":true}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
D/WifiP2pManager( 3286): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT838","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2685","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2457","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,D/WifiP2pManager( 3286): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2588","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6283","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2685","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2457","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7127","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7600","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
,D/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] removed
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] not available
,I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT6283","peerAvailable":false}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
I/io.jxcore.node.ConnectionHelper( 3286): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] removed
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] not available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT2588","peerAvailable":false}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6107","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
,D/WifiP2pManager( 3286): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] removed
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] not available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT2685","peerAvailable":false}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7127","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,I/Icing   ( 1697): Performing maintenance.
,I/Icing   ( 1697): updateResources: need to parse f{com.google.android.gms}
,I/Icing   ( 1697): Performing maintenance usage 1778640 budget 5208717800 free 99.966% index free 99.982% purge? false target 3646102460
,I/Icing   ( 1697): Query from com.google.android.gms package restrict com.google.android.gms start 0 num 100
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7600","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): checkListForExpiredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Removed [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
,I/io.jxcore.node.ConnectionHelper( 3286): onPeerLost: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] removed
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] not available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT6107","peerAvailable":false}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  988): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2457","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT6420","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] is available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC-HTC One M8s_PT6420","peerAvailable":true}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6283","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] is available
,I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT6283","peerAvailable":true}]
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): timeout now
I/jxcore-log( 3286): 
I/jxcore-log( 3286): weAreDoneNow, resultArray.length: 11
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): sendReportNow
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): done, now sending data to server
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:45:32.695Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3286): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7600","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2685","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] is available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT2685","peerAvailable":true}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3595","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT838","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,D/WifiP2pManager( 3286): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT838","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): checkListForExpiredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: false
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Removed [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerLost: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] removed
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] not available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"LGE-LG-D855_PT7127","peerAvailable":false}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/WifiP2pManager( 3286): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2685","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2457","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6107","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] is available
,I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT6107","peerAvailable":true}]
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7600","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): checkListForExpiredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerLost: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] removed
,D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] not available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT838","peerAvailable":false}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,D/WifiP2pManager( 3286): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): Start timer timeout, starting now...
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  988): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3286): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6107","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2588","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588] is available
,I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT2588","peerAvailable":true}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7600","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2457","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6283","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6107]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT2457], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7600]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): restart: Restarting...
,D/WifiP2pManager( 3286): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service discovery started successfully
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  988): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6283]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2588]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT6420","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6420] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7127","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7127], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7127] is available
I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"LGE-LG-D855_PT7127","peerAvailable":true}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
I/io.jxcore.node.ConnectionHelper( 3286): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685]
D/io.jxcore.node.ConnectionHelper( 3286): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3286): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] removed
D/io.jxcore.node.ConnectionHelper( 3286): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] not available
,I/jxcore-log( 3286): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT2685","peerAvailable":false}]
I/jxcore-log( 3286): 
I/jxcore-log( 3286): startWithNextDevice
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): teardown
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): testSendData stopped
I/jxcore-log( 3286): 
I/io.jxcore.node.ConnectionHelper( 3286): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3286): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3286): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3286): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3286): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3286): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3286): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3286): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3286): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3286): setState: NOT_STARTED
,I/jxcore-log( 3286): StopBroadcasting went ok
I/jxcore-log( 3286): 
,I/jxcore-log( 3286): 2015-12-19T00:48:52.720Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3286): 
I/chromium( 3286): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3286): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3286): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3286): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3286): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3286): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3286): ****TEST TOOK:  ms ****
I/jxcore-log( 3286): 
I/jxcore-log( 3286): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3286): 
,D/AndroidRuntime( 3944): 
D/AndroidRuntime( 3944): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3944): CheckJNI is OFF
,D/AndroidRuntime( 3944): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  755): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  755): Killing 3286:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,D/WifiService(  755): Client connection lost with reason: 4
I/WindowState(  755): WIN DEATH: Window{a2c70 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  755): Skipping PackageSetting{3de8aa6 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  755):   Force finishing activity ActivityRecord{1b9168c5 u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  755): Spurious death for ProcessRecord{1317a0b5 3286:com.test.thalitest/u0a270}, curProc for 3286: null
,I/ActivityManager(  755): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1697): Explicit concurrent mark sweep GC freed 28592(1699KB) AllocSpace objects, 5(80KB) LOS objects, 25% free, 22MB/30MB, paused 456us total 32.120ms
,W/GeofencerStateMachine( 1657): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1106): resetDictionaries() : en_US
I/art     ( 1342): Explicit concurrent mark sweep GC freed 3928(292KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 407us total 22.348ms
I/InputReader(  755): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1379): Explicit concurrent mark sweep GC freed 58566(2MB) AllocSpace objects, 11(176KB) LOS objects, 24% free, 19MB/25MB, paused 7.079ms total 49.840ms
,D/NetworkChangeNotifierAutoDetect(  946): Network connectivity changed, type is: 2
,I/Keyboard.Facilitator.DecoderInitializer( 1106): run()
D/VoicemailCleanupService( 1401): Cleaning up data for package: com.test.thalitest
,I/Decoder ( 1106): createOrResetDecoder
,I/LibraryLoader( 1422): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
,I/art     (  755): Explicit concurrent mark sweep GC freed 94009(4MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 28MB/43MB, paused 1.223ms total 91.525ms
,I/art     (  755): WaitForGcToComplete blocked for 99.572ms for cause Explicit
,I/UpdateIcingCorporaServi( 1379): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/LibraryLoader( 1422): Time to load native libraries: 66 ms (timestamps 5407-5473)
,I/LibraryLoader( 1422): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/chromium( 1422): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 1422): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1422): Attempt to remove local handle scope entry from IRT, ignoring
,W/Launcher( 1342): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@388be483 new=com.google.android.velvet.VelvetApplication@388be483
,I/OpenGLRenderer(  946): Initialized EGL, version 1.4
I/CheckinRequestBuilder( 1657): Classify the device as Phone.
D/OpenGLRenderer(  946): Enabling debug mode 0
,I/ActivityManager(  755): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3986 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  755): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  755): Receieved: android.intent.action.PACKAGE_REMOVED
,W/art     (  946): Attempt to remove local handle scope entry from IRT, ignoring
,D/TaskPersister(  755): removeObsoleteFile: deleting file=214_task.xml
,W/InputMethodManagerService(  755): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@3aa2f847 (uid=10034 pid=946)
,I/UpdateIcingCorporaServi( 1379): UpdateCorporaTask done [took 147 ms] updated apps [took 147 ms] 
,W/ContextImpl( 3986): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1697): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1697): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1697): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1697): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1697): Removing dialog suppression flag for package com.test.thalitest
,D/ChimeraCfgMgr( 1697): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1697): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1657): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1657): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/art     (  755): Explicit concurrent mark sweep GC freed 22315(1146KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 5.376ms total 236.707ms
W/ResourcesManager( 1342): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Launcher( 1342): Deferring update until onResume
,W/ResourcesManager( 1342): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1342): Deferring update until onResume
,D/gH_CompatibleDatabase( 1697): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1697): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1697): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1697): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1697): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1697): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1697): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/ActivityManager(  755): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4033 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,D/gH_CompatibleDatabase( 1697): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1697): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1697): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1697): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1697): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1697): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/GMPM-SVC( 1697): App measurement is starting up, version: 8489
,I/GMPM-SVC( 1697): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1106): run()
D/AndroidRuntime( 3944): Shutting down VM
,W/BaseAppContext( 1697): Using Auth Proxy for data requests.
,W/BaseAppContext( 1697): Using Auth Proxy for data requests.
,I/Icing   ( 1697): doRemovePackageData com.test.thalitest
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1106): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1106): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1106): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1106): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1106): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1106): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1106): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1106): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1106): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1106): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1106): run()
I/StatsUtilsManager( 1106): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1106): shouldRecordStats() = Too Soon
,I/ActivityManager(  755): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4058 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  755): Killing 2052:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10031/pid_2052/cgroup.procs: No such file or directory
,I/ActivityManager(  755): Killing 2074:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10002/pid_2074/cgroup.procs: No such file or directory
,D/ExternalStorage( 4058): After updating volumes, found 1 active roots
,I/EventLogService( 1697): Aggregate from 1450484214430 (log), 1450484214430 (data)
,W/ResourcesManager( 3198): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3198): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 4033): Update found 7 roots in 277ms
,W/SharedPreferencesImpl( 1697): writeToFile: Got exception:
W/SharedPreferencesImpl( 1697): java.io.IOException: write failed: EBADF (Bad file number)
W/SharedPreferencesImpl( 1697): 	at libcore.io.IoBridge.write(IoBridge.java:502)
W/SharedPreferencesImpl( 1697): 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
W/SharedPreferencesImpl( 1697): 	at com.android.internal.util.FastXmlSerializer.flushBytes(FastXmlSerializer.java:232)
W/SharedPreferencesImpl( 1697): 	at com.android.internal.util.FastXmlSerializer.flush(FastXmlSerializer.java:253)
W/SharedPreferencesImpl( 1697): 	at com.android.internal.util.FastXmlSerializer.endDocument(FastXmlSerializer.java:198)
W/SharedPreferencesImpl( 1697): 	at com.android.internal.util.XmlUtils.writeMapXml(XmlUtils.java:188)
W/SharedPreferencesImpl( 1697): 	at android.app.SharedPreferencesImpl.writeToFile(SharedPreferencesImpl.java:597)
W/SharedPreferencesImpl( 1697): 	at android.app.SharedPreferencesImpl.access$800(SharedPreferencesImpl.java:51)
W/SharedPreferencesImpl( 1697): 	at android.app.SharedPreferencesImpl$2.run(SharedPreferencesImpl.java:512)
W/SharedPreferencesImpl( 1697): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/SharedPreferencesImpl( 1697): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/SharedPreferencesImpl( 1697): 	at java.lang.Thread.run(Thread.java:818)
W/SharedPreferencesImpl( 1697): Caused by: android.system.ErrnoException: write failed: EBADF (Bad file number)
W/SharedPreferencesImpl( 1697): 	at libcore.io.Posix.writeBytes(Native Method)
W/SharedPreferencesImpl( 1697): 	at libcore.io.Posix.write(Posix.java:223)
W/SharedPreferencesImpl( 1697): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
W/SharedPreferencesImpl( 1697): 	at libcore.io.IoBridge.write(IoBridge.java:497)
W/SharedPreferencesImpl( 1697): 	... 11 more
,D/Documents( 4033): Update found 7 roots in 159ms

```
