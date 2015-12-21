#### Test 506502781c2754f_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1601): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1601): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3127): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3127):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3127):   adb logcat -s GAv4
W/GAv4    ( 3127): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3127): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3127): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3127): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2593): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3127): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3127): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  758): Killing 2557:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3127): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3127): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3127): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  758): failed to open /acct/uid_10069/pid_2557/cgroup.procs: No such file or directory
V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1601): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1601): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1601): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1601): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3190): 
D/AndroidRuntime( 3190): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3190): CheckJNI is OFF
D/AndroidRuntime( 3190): Calling main entry com.android.commands.am.Am
I/ActivityManager(  758): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  758): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3214 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3190): Shutting down VM
V/ActivityManager(  758): Display changed displayId=0
I/WebViewFactory( 3214): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3214): Time to load native libraries: 2 ms (timestamps 1524-1526)
I/LibraryLoader( 3214): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3214): Binding Chromium to main looper Looper (main, tid 1) {1036952c}
I/LibraryLoader( 3214): Expected native library version number "",actual native library version number ""
I/chromium( 3214): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3214): Initializing chromium process, singleProcess=true
W/art     ( 3214): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3214): ApplicationContext is null in ApplicationStatus
,W/chromium( 3214): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3214): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3214): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3214): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24d8e56a:true
,W/art     ( 3214): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3214): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3214): CordovaWebView is running on device made by: LGE
,W/art     ( 3214): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3214): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3214): Render dirty regions requested: true
,D/Atlas   ( 3214): Validating map...
,W/chromium( 3214): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  758): Killing 2512:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10045/pid_2512/cgroup.procs: No such file or directory
,I/OpenGLRenderer( 3214): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3214): Enabling debug mode 0
,I/Keyboard.Facilitator( 1101): onFinishInput()
,W/IInputConnectionWrapper( 3214): showStatusIcon on inactive InputConnection
,I/ActivityManager(  758): Displayed com.test.thalitest/.MainActivity: +446ms (total +59s564ms)
,W/BindingManager( 3214): Cannot call determinedVisibility() - never saw a connection for the pid: 3214
,D/JsMessageQueue( 3214): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3214): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3214): jxcore cordova android initializing
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/jxcore-log( 3214): Initializing JXcore engine
W/jxcore-log( 3214): JXcore engine is ready
,W/jxcore-log( 3214): Starting JXcore engine
,W/.test.thalitest( 3214): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8001]" dev="sockfs" ino=8001 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3214): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3214): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8051]" dev="sockfs" ino=8051 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3214): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19730]" dev="sockfs" ino=19730 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3214): Platform android
W/jxcore-log( 3214): 
W/jxcore-log( 3214): Process ARCH arm
W/jxcore-log( 3214): 
,I/jxcore-log( 3214): JXcore Cordova bridge is ready!
I/jxcore-log( 3214): 
,W/jxcore-log( 3214): JXcore engine is started
I/Choreographer( 3214): Skipped 107 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3214): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  758): Killing 2667:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10003/pid_2667/cgroup.procs: No such file or directory
,I/jxcore-log( 3214): Toggling radios to true
I/jxcore-log( 3214): 
,D/BluetoothAdapter( 3214): enable(): BT is already enabled..!
,D/WifiService(  758): New client listening to asynchronous messages
,D/WifiService(  758): setWifiEnabled: true pid=3214, uid=10270
E/WifiService(  758): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3214): Radios toggled
I/jxcore-log( 3214): 
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3214): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3214): 
,I/jxcore-log( 3214): Perf Test app loaded loaded
I/jxcore-log( 3214): 
,I/jxcore-log( 3214): check test folder
I/jxcore-log( 3214): 
I/jxcore-log( 3214): found test : ./testFindPeers.js
I/jxcore-log( 3214): 
I/wpa_supplicant( 1033): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  758): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  758): do suspend true
D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1567): Read error: ssl=0x9d60e200: I/O error during system call, Connection timed out
V/NativeCrypto( 1567): SSL shutdown failed: ssl=0x9d60e200: I/O error during system call, Broken pipe
,D/ConnectivityService(  758): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiStateMachine(  758): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1033): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  758): do suspend true
,I/jxcore-log( 3214): found test : ./testSendData.js
I/jxcore-log( 3214): 
,D/CommandListener(  180): Clearing all IP addresses on wlan0
D/ConnectivityService(  758): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524292
D/Nat464Xlat(  758): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  758): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  758): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1270): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1601): CM callback handler got msg 524292
,D/WifiNetworkAgent(  758): NetworkAgent: NetworkAgent channel lost
,I/jxcore-log( 3214): found test : ./testSendData2.js
I/jxcore-log( 3214): 
,E/jxcore  ( 3214): Error!: unlabeled break must be inside loop or switch
E/jxcore  ( 3214): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
I/Choreographer( 3214): Skipped 64 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3214): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 1033): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1033): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1033): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1033): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  758): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  180): Setting iface cfg
,E/WifiStateMachine(  758): Start Dhcp Watchdog 2
,E/native  (  758): do suspend false
,E/WifiStateMachine(  758): scanCount==0 - aborting
,I/dhcpcd  ( 3321): version 5.5.6 starting
,E/dhcpcd  ( 3321): get_duid: Read-only file system
,I/dhcpcd  ( 3321): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3321): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3321): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  758): MasterInitialState.processMessage what=3
D/Tethering(  758): MasterInitialState.processMessage what=3
,E/native  (  758): do suspend true
,V/MusicLeanback( 2705): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  758): Adding iface wlan0 to network 101
,E/WifiStateMachine(  758): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/ConnectivityService(  758): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  758): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  758): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  758): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  758): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  758): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  758): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  758): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  758): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/SystemUpdateService( 1601): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/ConnectivityService(  758): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  758): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1601): CM callback handler got msg 524290
,D/SystemUpdateService( 1601): onCreate
,E/GpsLocationProvider(  758): No APN found to select.
,D/SystemUpdateService( 1601): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1601): active receiver: enabled
,E/GpsLocationProvider(  758): No APN found to select.
,I/SystemUpdateService( 1601): showing system update notification
,I/ValidateNoPeople(  758): skipping global notification
,V/SystemUpdateService( 1601): retry (wakeup: false) in 3599987 ms
,D/SystemUpdateService( 1601): onDestroy
,I/ActivityManager(  758): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3378 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 21 Dec 2015 00:32:43 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450657963344], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450657963330]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Validated
D/ConnectivityService(  758): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  758): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1270): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1601): CM callback handler got msg 524290
,I/GAv4    ( 3378): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3378):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3378):   adb logcat -s GAv4
,W/GAv4    ( 3378): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3378): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3378): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3378): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/Nat464Xlat(  758): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  758): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1601): CM callback handler got msg 524295
,I/LibraryLoader( 3378): Time to load native libraries: 2 ms (timestamps 8423-8425)
,I/LibraryLoader( 3378): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3378): Binding Chromium to main looper Looper (main, tid 1) {17c1023e}
I/LibraryLoader( 3378): Expected native library version number "",actual native library version number ""
I/chromium( 3378): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3378): Initializing chromium process, singleProcess=true
,W/art     ( 3378): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3378): ApplicationContext is null in ApplicationStatus
,W/chromium( 3378): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3378): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3378): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3378): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3378): Requires BLUETOOTH permission
,I/NSApplication( 3378): Starting up...
,I/ActivityManager(  758): Killing 2649:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  758): Client connection lost with reason: 4
,W/libprocessgroup(  758): failed to open /acct/uid_1000/pid_2649/cgroup.procs: No such file or directory
,V/MusicLeanback( 2705): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1601): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1601): onCreate
,I/art     (  758): Explicit concurrent mark sweep GC freed 41481(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 800us total 52.491ms
,D/SystemUpdateService( 1601): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1601): active receiver: enabled
,I/SystemUpdateService( 1601): showing system update notification
,I/ValidateNoPeople(  758): skipping global notification
,V/SystemUpdateService( 1601): retry (wakeup: false) in 3599964 ms
,D/SystemUpdateService( 1601): onDestroy
,D/ConnectivityService(  758): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3214): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3214): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3214): BLE supported!!
I/jxcore-log( 3214): 
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  758): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2705): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2705): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1601): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1601): onCreate
,D/SystemUpdateService( 1601): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1601): active receiver: enabled
,I/SystemUpdateService( 1601): showing system update notification
,E/GpsLocationProvider(  758): No APN found to select.
,I/ValidateNoPeople(  758): skipping global notification
,V/SystemUpdateService( 1601): retry (wakeup: false) in 3599983 ms
,D/SystemUpdateService( 1601): onDestroy
,D/Finsky  ( 2593): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2593): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1567): Vacuum at: now=1450657973377 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1101): run()
I/Keyboard.Facilitator( 1101): flushDynamicLanguageModels()
,I/ConfigService( 1567): onCreate
,I/ConfigService( 1567): onDestroy
,I/ClearcutLoggerApiImpl( 1567): disconnect managed GoogleApiClient
,I/ActivityManager(  758): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3529 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3529): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3529):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3529):   adb logcat -s GAv4
,W/GAv4    ( 3529): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3529): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3529): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  758): Killing 2531:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10070/pid_2531/cgroup.procs: No such file or directory
,W/bt-smp  ( 2073): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2073): Plain text(LSB ~ MSB) = 04 9c 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2073): Encrypted text(LSB ~ MSB) = d7 90 72 74 a4 46 65 4d 3d 58 d0 4f a9 32 87 07 
W/bt-btm  ( 2073): Stopping oneshot timer
,I/EventLogService( 1601): Aggregate from 1450656901281 (log), 1450656901281 (data)
,I/PhenotypeConfigurator( 1567): Scheduling Phenotype for one-off execution 4166 seconds from now (1450658867414)
,D/GetConfigurationSnapshotOperation( 1567): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1567): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1567): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UsageStatsService(  758): User[0] Flushing usage stats to disk
,I/ProcessStatsService(  758): Prepared write state in 29ms
,I/ProcessStatsService(  758): Prepared write state in 4ms
,W/bt-smp  ( 2073): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2073): Plain text(LSB ~ MSB) = f5 8c 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 2073): Encrypted text(LSB ~ MSB) = ea 82 94 c3 62 d8 12 14 c6 f8 d3 31 5d 90 c0 eb 
W/bt-btm  ( 2073): Stopping oneshot timer
,I/ProcessStatsService(  758): Pruning old procstats: /data/system/procstats/state-2015-12-20-04-11-07.bin
,TIME-OUT KILL (timeout was 1800000ms),I/ActivityManager(  758): Killing 3094:com.android.musicfx/u0a15 (adj 13): empty for 1813s
I/ActivityManager(  758): Killing 1487:com.google.android.partnersetup/u0a13 (adj 13): empty for 1813s
I/ActivityManager(  758): Killing 2799:android.process.acore/u0a4 (adj 13): empty for 1813s
I/ActivityManager(  758): Killing 1991:com.android.providers.calendar/u0a2 (adj 13): empty for 1823s
I/ActivityManager(  758): Killing 2958:com.google.android.gms:car/u0a8 (adj 15): empty for 1823s
I/ActivityManager(  758): Killing 1956:com.google.android.calendar/u0a31 (adj 15): empty for 1853s
W/libprocessgroup(  758): failed to open /acct/uid_10015/pid_3094/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10004/pid_2799/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10002/pid_1991/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10008/pid_2958/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10031/pid_1956/cgroup.procs: No such file or directory
W/libprocessgroup(  758): failed to open /acct/uid_10013/pid_1487/cgroup.procs: No such file or directory
V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  758): Killing 3127:com.google.android.apps.docs/u0a40 (adj 15): empty for 1812s
W/libprocessgroup(  758): failed to open /acct/uid_10040/pid_3127/cgroup.procs: No such file or directory
D/AndroidRuntime( 3641): 
D/AndroidRuntime( 3641): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3641): CheckJNI is OFF
D/AndroidRuntime( 3641): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  758): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  758): Killing 3214:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  758): WIN DEATH: Window{2ead7d1a u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  758): Client connection lost with reason: 4
W/PackageSettings(  758): Skipping PackageSetting{21c3e500 com.example.hello/10278} due to missing metadata
I/ActivityManager(  758):   Force finishing activity ActivityRecord{5349786 u0 com.test.thalitest/.MainActivity t214}
W/ActivityManager(  758): Spurious death for ProcessRecord{30c76290 3214:com.test.thalitest/u0a270}, curProc for 3214: null
I/ActivityManager(  758): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/art     ( 1298): Explicit concurrent mark sweep GC freed 4002(296KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 673us total 30.377ms
W/GeofencerStateMachine( 1567): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1101): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1101): run()
I/Decoder ( 1101): createOrResetDecoder
I/InputReader(  758): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  758): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=3669 uid=10004 gids={50004, 9997} abi=armeabi-v7a
I/art     (  758): Explicit concurrent mark sweep GC freed 35879(1983KB) AllocSpace objects, 12(289KB) LOS objects, 33% free, 27MB/41MB, paused 1.777ms total 77.134ms
I/art     ( 1393): Explicit concurrent mark sweep GC freed 15737(1088KB) AllocSpace objects, 1(39KB) LOS objects, 24% free, 18MB/25MB, paused 353us total 97.522ms
I/art     ( 1601): Explicit concurrent mark sweep GC freed 35981(2MB) AllocSpace objects, 9(144KB) LOS objects, 24% free, 22MB/30MB, paused 1.061ms total 97.722ms
I/ConfigService( 1567): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1101): run()
D/BackupManagerService(  758): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  758): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  758): removeObsoleteFile: deleting file=214_task.xml
I/art     (  758): Explicit concurrent mark sweep GC freed 6721(368KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.676ms total 87.311ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1101): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1101): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1101): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1101): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1101): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1101): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1101): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1101): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1101): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1101): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1101): run()
I/StatsUtilsManager( 1101): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1101): shouldRecordStats() = Too Soon
W/InputMethodManagerService(  758): Got RemoteException sending setActive(false) notification to pid 3214 uid 10270
I/Keyboard.Facilitator( 1101): onFinishInput()
D/VoicemailCleanupService( 3669): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  758): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=3704 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
I/ContactLocale( 3669): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/AndroidRuntime( 3641): Shutting down VM
I/Launcher( 1298): Deferring update until onResume
I/ActivityManager(  758): Killing 3030:com.android.defcontainer/u0a5 (adj 15): empty for 1813s
W/ResourcesManager( 1298): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1298): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1298): Deferring update until onResume
W/libprocessgroup(  758): failed to open /acct/uid_10005/pid_3030/cgroup.procs: No such file or directory
I/UpdateIcingCorporaServi( 1393): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1298): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@14b91bf5 new=com.google.android.velvet.VelvetApplication@14b91bf5
I/ActivityManager(  758): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3728 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  758): Killing 2705:com.google.android.music:main/u0a60 (adj 15): empty for 1804s
W/libprocessgroup(  758): failed to open /acct/uid_10060/pid_2705/cgroup.procs: No such file or directory
I/UpdateIcingCorporaServi( 1393): UpdateCorporaTask done [took 96 ms] updated apps [took 96 ms] 
W/ContextImpl( 3728): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
D/PackageBroadcastService( 1601): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1601): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1601): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1601): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1601): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1601): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1601): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1567): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1567): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1601): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1601): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1601): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1601): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1601): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1601): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1601): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/ActivityManager(  758): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3755 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
D/gH_CompatibleDatabase( 1601): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1601): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1601): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1601): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1601): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1601): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/BaseAppContext( 1601): Using Auth Proxy for data requests.
W/BaseAppContext( 1601): Using Auth Proxy for data requests.
E/SQLiteDatabase( 1601): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1601): 	at com.google.android.gms.common.k.a.delete(SourceFile:272)
E/SQLiteDatabase( 1601): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/SQLiteDatabase( 1601): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1601): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1601): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1601): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/SQLiteDatabase( 1601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1601): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteDatabase( 1601): 	at java.lang.Thread.run(Thread.java:818)
I/art     ( 1567): Explicit concurrent mark sweep GC freed 92464(5MB) AllocSpace objects, 26(439KB) LOS objects, 39% free, 23MB/38MB, paused 774us total 47.953ms
E/ClearPendingStateOp( 1601): Runtime exception while performing operation
E/ClearPendingStateOp( 1601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/ClearPendingStateOp( 1601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1601): 	at com.google.android.gms.common.k.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1601): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/ClearPendingStateOp( 1601): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1601): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1601): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1601): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 1601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1601): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1601): 	at java.lang.Thread.run(Thread.java:818)
E/DataBuffer( 1567): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@116fc6d1)
F/ClearPendingStateOp( 1601): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
F/ClearPendingStateOp( 1601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
F/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1601): 	at com.google.android.gms.common.k.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1601): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
F/ClearPendingStateOp( 1601): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1601): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1601): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1601): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 1601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1601): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1601): 	at java.lang.Thread.run(Thread.java:818)
E/DataBuffer( 1567): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@251a35a4)
E/DataBuffer( 1567): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2958ff0d)
E/DataBuffer( 1567): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@9a8bec2)
E/DataBuffer( 1567): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@130484d3)
I/GMPM-SVC( 1601): App measurement is starting up, version: 8489
I/GMPM-SVC( 1601): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/DataBuffer( 1567): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@c237f09)
E/DropBoxManagerService(  758): Can't write: system_app_wtf
E/DropBoxManagerService(  758): java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  758): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  758): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  758): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  758): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  758): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  758): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  758): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  758): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  758): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  758): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  758): 	... 5 more

```
