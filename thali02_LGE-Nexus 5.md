#### Test 54312298c831015_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3125): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3125):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3125):   adb logcat -s GAv4
W/GAv4    ( 3125): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3125): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3125): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3125): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2638): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  758): Killing 2085:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/ResourcesManager( 3125): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3125): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AndroidRuntime( 3172): 
D/AndroidRuntime( 3172): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3172): CheckJNI is OFF
W/libprocessgroup(  758): failed to open /acct/uid_10038/pid_2085/cgroup.procs: No such file or directory
V/JNIHelp ( 3125): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3125): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3125): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 3172): Calling main entry com.android.commands.am.Am
V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  758): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  758): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3198 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3172): Shutting down VM
I/art     (  193): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 393us total 8.892ms
I/art     (  193): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 240us total 10.499ms
I/art     (  193): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 231us total 9.861ms
V/ActivityManager(  758): Display changed displayId=0
I/Icing   ( 1624): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1624): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1624): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/WebViewFactory( 3198): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3198): Time to load native libraries: 2 ms (timestamps 7796-7798)
I/LibraryLoader( 3198): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3198): Binding Chromium to main looper Looper (main, tid 1) {4b3bee6}
I/LibraryLoader( 3198): Expected native library version number "",actual native library version number ""
I/chromium( 3198): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/Icing   ( 1624): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/BrowserStartupController( 3198): Initializing chromium process, singleProcess=true
W/art     ( 3198): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3198): ApplicationContext is null in ApplicationStatus
,W/chromium( 3198): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3198): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3198): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3198): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11dc146f:true
,W/art     ( 3198): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3198): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3198): CordovaWebView is running on device made by: LGE
W/art     ( 3198): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3198): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3198): Render dirty regions requested: true
D/Atlas   ( 3198): Validating map...
W/chromium( 3198): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3198): Initialized EGL, version 1.4
D/OpenGLRenderer( 3198): Enabling debug mode 0
I/Keyboard.Facilitator( 1109): onFinishInput()
W/BindingManager( 3198): Cannot call determinedVisibility() - never saw a connection for the pid: 3198
W/IInputConnectionWrapper( 3198): showStatusIcon on inactive InputConnection
I/ActivityManager(  758): Displayed com.test.thalitest/.MainActivity: +460ms (total +56s451ms)
D/CAR.SERVICE( 3019): mConnectedToCar = false, abort
E/ActivityThread( 3019): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3800f9ef that was originally bound here
E/ActivityThread( 3019): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3800f9ef that was originally bound here
E/ActivityThread( 3019): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3019): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3019): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3019): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3019): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3019): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3019): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3019): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3019): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3019): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3019): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3019): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3019): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3019): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3019): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3019): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3019): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3019): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3019): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3019): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3019): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3019): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3019): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/ActivityThread( 3019): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1b35c1a6 that was originally bound here
E/ActivityThread( 3019): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1b35c1a6 that was originally bound here
E/ActivityThread( 3019): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3019): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3019): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3019): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3019): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3019): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3019): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3019): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3019): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3019): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3019): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3019): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3019): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3019): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3019): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3019): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3019): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3019): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3019): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3019): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3019): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3019): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  758): Unbind failed: could not find connection for android.os.BinderProxy@18574098
D/JsMessageQueue( 3198): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3198): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258381056
D/JX-Cordova( 3198): jxcore cordova android initializing
I/ActivityManager(  758): Killing 2608:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/libprocessgroup(  758): failed to open /acct/uid_10069/pid_2608/cgroup.procs: No such file or directory
,W/jxcore-log( 3198): Initializing JXcore engine
W/jxcore-log( 3198): JXcore engine is ready
,W/jxcore-log( 3198): Starting JXcore engine
,W/.test.thalitest( 3198): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8086]" dev="sockfs" ino=8086 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3198): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3198): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8503]" dev="sockfs" ino=8503 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3198): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20561]" dev="sockfs" ino=20561 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3198): Platform android
W/jxcore-log( 3198): 
W/jxcore-log( 3198): Process ARCH arm
W/jxcore-log( 3198): 
,I/jxcore-log( 3198): JXcore Cordova bridge is ready!
I/jxcore-log( 3198): 
W/jxcore-log( 3198): JXcore engine is started
,I/Choreographer( 3198): Skipped 117 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3198): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3198): Toggling radios to true
I/jxcore-log( 3198): 
,D/BluetoothAdapter( 3198): enable(): BT is already enabled..!
,D/WifiService(  758): New client listening to asynchronous messages
,D/WifiService(  758): setWifiEnabled: true pid=3198, uid=10270
E/WifiService(  758): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3198): Radios toggled
I/jxcore-log( 3198): 
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3198): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3198): 
,I/jxcore-log( 3198): Perf Test app loaded loaded
I/jxcore-log( 3198): 
,I/jxcore-log( 3198): check test folder
I/jxcore-log( 3198): 
I/wpa_supplicant(  992): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
I/jxcore-log( 3198): found test : ./testFindPeers.js
I/jxcore-log( 3198): 
,E/WifiStateMachine(  758): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  758): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1602): Read error: ssl=0xa4249e00: I/O error during system call, Connection timed out
V/NativeCrypto( 1602): SSL shutdown failed: ssl=0xa4249e00: I/O error during system call, Broken pipe
D/ConnectivityService(  758): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Checking http://clients3.google.com/generate_204 on "NG7005g"
,E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  758): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  992): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  758): do suspend true
,I/jxcore-log( 3198): found test : ./testSendData.js
I/jxcore-log( 3198): 
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  758): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  758): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  758): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityManager.CallbackHandler( 1624): CM callback handler got msg 524292
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Disconnected - quitting
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  758): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1269): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  758): NetworkAgent: NetworkAgent channel lost
,I/jxcore-log( 3198): found test : ./testSendData2.js
I/jxcore-log( 3198): 
,E/jxcore  ( 3198): Error!: missing ) after argument list
E/jxcore  ( 3198): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
I/chromium( 3198): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1390): OkHttp exception
,W/EventLoggerService( 1390): Unable to send logs Error code: 262146
,I/wpa_supplicant(  992): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  992): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  992): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  992): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  758): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  178): Setting iface cfg
,E/WifiStateMachine(  758): Start Dhcp Watchdog 2
,E/native  (  758): do suspend false
,E/WifiStateMachine(  758): scanCount==0 - aborting
,I/dhcpcd  ( 3294): version 5.5.6 starting
,E/dhcpcd  ( 3294): get_duid: Read-only file system
,I/dhcpcd  ( 3294): wlan0: rebinding lease of 192.168.1.114
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  758): MasterInitialState.processMessage what=3
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  758): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2755): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1624): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1624): onCreate
,D/SystemUpdateService( 1624): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1624): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1624): num queued entries: 0
I/iu.UploadsManager( 1624): num updated entries: 0
I/iu.SyncManager( 1624): NEXT; no task
,I/SystemUpdateService( 1624): active receiver: enabled
,I/Babel   ( 1948): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1624): showing system update notification
,I/ActivityManager(  758): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3323 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  758): No APN found to select.
,E/GpsLocationProvider(  758): No APN found to select.
,I/ValidateNoPeople(  758): skipping global notification
,V/SystemUpdateService( 1624): retry (wakeup: false) in 3599962 ms
,D/SystemUpdateService( 1624): onDestroy
,I/GAv4    ( 3323): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3323):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3323):   adb logcat -s GAv4
,W/GAv4    ( 3323): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3323): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3323): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3323): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3323): Time to load native libraries: 1 ms (timestamps 4846-4847)
,I/LibraryLoader( 3323): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3323): Binding Chromium to main looper Looper (main, tid 1) {f361da}
,I/LibraryLoader( 3323): Expected native library version number "",actual native library version number ""
I/chromium( 3323): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/dhcpcd  ( 3294): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/BrowserStartupController( 3323): Initializing chromium process, singleProcess=true
,W/art     ( 3323): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3323): ApplicationContext is null in ApplicationStatus
,W/chromium( 3323): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,I/dhcpcd  ( 3294): wlan0: leased 192.168.1.114 for 86400 seconds
,E/libEGL  ( 3323): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3323): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3323): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3323): Requires BLUETOOTH permission
,I/NSApplication( 3323): Starting up...
,I/ActivityManager(  758): Killing 2563:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,E/native  (  758): do suspend true
,W/libprocessgroup(  758): failed to open /acct/uid_10045/pid_2563/cgroup.procs: No such file or directory
,V/MusicLeanback( 2755): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  758): Adding iface wlan0 to network 101
,E/WifiStateMachine(  758): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  758): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  758): Adding Route [fe80::/64 -> :: wlan0] to network 101
,I/SystemUpdateService( 1624): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/ConnectivityService(  758): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  758): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  758): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  758): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  758): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/CSLegacyTypeTracker(  758): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SystemUpdateService( 1624): onCreate
,D/ConnectivityService(  758): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  758): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1624): CM callback handler got msg 524290
,D/SystemUpdateService( 1624): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1624): active receiver: enabled
,I/iu.Environment( 1624): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1624): showing system update notification
,I/iu.UploadsManager( 1624): num queued entries: 0
,I/iu.UploadsManager( 1624): num updated entries: 0
I/iu.SyncManager( 1624): NEXT; no task
,I/ValidateNoPeople(  758): skipping global notification
,V/SystemUpdateService( 1624): retry (wakeup: false) in 3599977 ms
,D/SystemUpdateService( 1624): onDestroy
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 21 Dec 2015 23:01:00 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450738860098], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450738860081]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Validated
,D/ConnectivityService(  758): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  758): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1624): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1269): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/Babel   ( 1948): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  758): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3198): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3198): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3198): BLE supported!!
I/jxcore-log( 3198): 
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  758): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2755): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2755): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1624): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1624): onCreate
,D/SystemUpdateService( 1624): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1624): active receiver: enabled
,I/SystemUpdateService( 1624): showing system update notification
,I/ValidateNoPeople(  758): skipping global notification
,V/SystemUpdateService( 1624): retry (wakeup: false) in 3599979 ms
,I/art     (  758): Explicit concurrent mark sweep GC freed 42651(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 878us total 67.589ms
,D/SystemUpdateService( 1624): onDestroy
,E/GpsLocationProvider(  758): No APN found to select.
,D/Finsky  ( 2638): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2638): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1602): Vacuum at: now=1450738878328 tag=VacuumService
,I/PhenotypeConfigurator( 1602): Scheduling Phenotype for one-off execution 7057 seconds from now (1450738878679)
,D/GetConfigurationSnapshotOperation( 1602): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1602): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1602): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1109): run()
,I/Keyboard.Facilitator( 1109): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1602): disconnect managed GoogleApiClient
,I/ActivityManager(  758): Killing 2732:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10003/pid_2732/cgroup.procs: No such file or directory
,I/ActivityManager(  758): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3545 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3545): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3545):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3545):   adb logcat -s GAv4
,W/GAv4    ( 3545): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3545): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3545): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  758): Killing 2713:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  758): Client connection lost with reason: 4
,W/libprocessgroup(  758): failed to open /acct/uid_1000/pid_2713/cgroup.procs: No such file or directory
,W/bt-smp  ( 2111): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2111): Plain text(LSB ~ MSB) = bf 28 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2111): Encrypted text(LSB ~ MSB) = 8e 95 eb f8 e4 ea 19 7c 00 22 c2 54 4c 35 88 66 
,W/bt-btm  ( 2111): Stopping oneshot timer
,I/UsageStatsService(  758): User[0] Flushing usage stats to disk
,I/EventLogService( 1624): Aggregate from 1450737960410 (log), 1450737960410 (data)
,I/ProcessStatsService(  758): Prepared write state in 31ms
,I/ProcessStatsService(  758): Prepared write state in 3ms
,I/ProcessStatsService(  758): Pruning old procstats: /data/system/procstats/state-2015-12-21-01-31-26.bin
,W/bt-smp  ( 2111): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2111): Plain text(LSB ~ MSB) = 42 29 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2111): Encrypted text(LSB ~ MSB) = 2d ac e5 10 6f f7 d0 f0 4c ff 51 12 11 b3 13 ff 
W/bt-btm  ( 2111): Stopping oneshot timer
,I/ActivityManager(  758): Killing 3019:com.google.android.gms:car/u0a8 (adj 13): empty for 1807s
,I/ActivityManager(  758): Killing 3092:com.android.musicfx/u0a15 (adj 13): empty for 1808s
,I/ActivityManager(  758): Killing 1477:com.google.android.partnersetup/u0a13 (adj 13): empty for 1808s
,I/ActivityManager(  758): Killing 2038:com.android.providers.calendar/u0a2 (adj 13): empty for 1811s
,I/ActivityManager(  758): Killing 2018:com.google.android.calendar/u0a31 (adj 15): empty for 1841s
,I/ActivityManager(  758): Killing 2582:com.google.android.gm/u0a70 (adj 15): empty for 1841s
,W/libprocessgroup(  758): failed to open /acct/uid_10013/pid_1477/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10002/pid_2038/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10031/pid_2018/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10070/pid_2582/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10008/pid_3019/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10015/pid_3092/cgroup.procs: No such file or directory
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/DataBuffer( 1602): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@39e4ec25)
E/DataBuffer( 1602): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@300a01fa)
E/DataBuffer( 1602): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@23933ab)
E/DataBuffer( 1602): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@15b4a08)
E/DataBuffer( 1602): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2e9d25a1)
,I/art     ( 1602): Explicit concurrent mark sweep GC freed 84523(4MB) AllocSpace objects, 25(400KB) LOS objects, 39% free, 23MB/38MB, paused 1.078ms total 65.431ms
,I/ActivityManager(  758): Killing 3125:com.google.android.apps.docs/u0a40 (adj 15): empty for 1809s
,W/libprocessgroup(  758): failed to open /acct/uid_10040/pid_3125/cgroup.procs: No such file or directory
,TIME-OUT KILL (timeout was 1800000ms)
```
