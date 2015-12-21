#### Test 506502782e2cb10_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3233): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3233):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3233):   adb logcat -s GAv4
W/GAv4    ( 3233): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3233): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3233): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3233): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2697): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3233): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3233): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  756): Killing 2661:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3233): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/libprocessgroup(  756): failed to open /acct/uid_10069/pid_2661/cgroup.procs: No such file or directory
W/System  ( 3233): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3233): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1633): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1633): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1633): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1633): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3313): 
D/AndroidRuntime( 3313): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3313): CheckJNI is OFF
D/AndroidRuntime( 3313): Calling main entry com.android.commands.am.Am
I/ActivityManager(  756): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  756): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3334 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3313): Shutting down VM
V/ActivityManager(  756): Display changed displayId=0
I/ActivityManager(  756): Killing 2616:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
I/WebViewFactory( 3334): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
W/libprocessgroup(  756): failed to open /acct/uid_10045/pid_2616/cgroup.procs: No such file or directory
I/LibraryLoader( 3334): Time to load native libraries: 1 ms (timestamps 8309-8310)
I/LibraryLoader( 3334): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3334): Binding Chromium to main looper Looper (main, tid 1) {18b9b34f}
I/LibraryLoader( 3334): Expected native library version number "",actual native library version number ""
I/chromium( 3334): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3334): Initializing chromium process, singleProcess=true
W/art     ( 3334): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3334): ApplicationContext is null in ApplicationStatus
,W/chromium( 3334): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3334): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3334): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3334): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  756): Message: 20
D/BluetoothManagerService(  756): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a45c09d:true
,W/art     ( 3334): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3334): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3334): CordovaWebView is running on device made by: LGE
,W/art     ( 3334): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3334): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3334): Render dirty regions requested: true
,D/Atlas   ( 3334): Validating map...
,W/chromium( 3334): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3334): Initialized EGL, version 1.4
D/OpenGLRenderer( 3334): Enabling debug mode 0
,I/Keyboard.Facilitator( 1060): onFinishInput()
,W/IInputConnectionWrapper( 3334): showStatusIcon on inactive InputConnection
,I/ActivityManager(  756): Displayed com.test.thalitest/.MainActivity: +452ms (total +55s631ms)
,W/BindingManager( 3334): Cannot call determinedVisibility() - never saw a connection for the pid: 3334
,D/JsMessageQueue( 3334): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3334): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1405526272
D/JX-Cordova( 3334): jxcore cordova android initializing
,W/jxcore-log( 3334): Initializing JXcore engine
W/jxcore-log( 3334): JXcore engine is ready
,W/jxcore-log( 3334): Starting JXcore engine
,W/.test.thalitest( 3334): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6613]" dev="sockfs" ino=6613 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3334): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3334): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6713]" dev="sockfs" ino=6713 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3334): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[21533]" dev="sockfs" ino=21533 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3334): Platform android
W/jxcore-log( 3334): 
,W/jxcore-log( 3334): Process ARCH arm
W/jxcore-log( 3334): 
,I/jxcore-log( 3334): JXcore Cordova bridge is ready!
I/jxcore-log( 3334): 
W/jxcore-log( 3334): JXcore engine is started
I/Choreographer( 3334): Skipped 107 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3334): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3334): Toggling radios to true
I/jxcore-log( 3334): 
,D/BluetoothAdapter( 3334): enable(): BT is already enabled..!
,D/WifiService(  756): New client listening to asynchronous messages
,D/WifiService(  756): setWifiEnabled: true pid=3334, uid=10270
E/WifiService(  756): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3334): Radios toggled
I/jxcore-log( 3334): 
,D/BluetoothManagerService(  756): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3334): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3334): 
,I/jxcore-log( 3334): Perf Test app loaded loaded
I/jxcore-log( 3334): 
,I/wpa_supplicant(  996): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  756): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  756): do suspend true
I/Choreographer( 3334): Skipped 58 frames!  The application may be doing too much work on its main thread.
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,I/jxcore-log( 3334): check test folder
I/jxcore-log( 3334): 
I/jxcore-log( 3334): found test : ./testFindPeers.js
I/jxcore-log( 3334): 
,V/NativeCrypto( 1657): Read error: ssl=0x9b9bbe00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1657): SSL shutdown failed: ssl=0x9b9bbe00: I/O error during system call, Broken pipe
,D/ConnectivityService(  756): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
I/jxcore-log( 3334): found test : ./testSendData.js
I/jxcore-log( 3334): 
,E/WifiStateMachine(  756): Start Disconnecting Watchdog 1
I/wpa_supplicant(  996): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  756): do suspend true
,I/jxcore-log( 3334): found test : ./testSendData2.js
I/jxcore-log( 3334): 
,E/jxcore  ( 3334): Error!: missing ) after argument list
E/jxcore  ( 3334): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
,I/chromium( 3334): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  756): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  756): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  756): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1633): CM callback handler got msg 524292
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524292
,D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  756): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1204): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  756): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  996): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  996): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  996): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  996): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  756): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  756): Start Dhcp Watchdog 2
,W/NetworkUtils( 1306): OkHttp exception
W/EventLoggerService( 1306): Unable to send logs Error code: 262146
,E/native  (  756): do suspend false
,E/WifiStateMachine(  756): scanCount==0 - aborting
,I/dhcpcd  ( 3441): version 5.5.6 starting
,E/dhcpcd  ( 3441): get_duid: Read-only file system
,I/dhcpcd  ( 3441): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3441): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3441): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  756): do suspend true
,D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  756): Adding iface wlan0 to network 101
,E/ConnectivityService(  756): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  756): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  756): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  756): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  756): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  756): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  756): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  756): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756):    accepting network in place of null
,D/CSLegacyTypeTracker(  756): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  756): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  756): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1633): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 21 Dec 2015 22:14:00 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450736040816], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450736040803]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Validated
D/ConnectivityService(  756): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService(  756): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1633): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1204): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  756): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2800): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2800): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2800): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  756): No APN found to select.
,E/GpsLocationProvider(  756): No APN found to select.
,I/SystemUpdateService( 1633): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1633): onCreate
,D/SystemUpdateService( 1633): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1633): active receiver: enabled
,I/SystemUpdateService( 1633): showing system update notification
,I/ValidateNoPeople(  756): skipping global notification
,V/SystemUpdateService( 1633): retry (wakeup: false) in 3599983 ms
,I/ActivityManager(  756): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3532 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1633): onDestroy
,I/GAv4    ( 3532): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3532):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3532):   adb logcat -s GAv4
,W/GAv4    ( 3532): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3532): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3532): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/Nat464Xlat(  756): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  756): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1633): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524295
,I/WebViewFactory( 3532): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3532): Time to load native libraries: 2 ms (timestamps 5291-5293)
,I/LibraryLoader( 3532): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3532): Binding Chromium to main looper Looper (main, tid 1) {1e740fe9}
I/LibraryLoader( 3532): Expected native library version number "",actual native library version number ""
I/chromium( 3532): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3532): Initializing chromium process, singleProcess=true
,W/art     ( 3532): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3532): ApplicationContext is null in ApplicationStatus
,D/ConnectivityService(  756): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/chromium( 3532): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3532): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3532): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3532): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3532): Requires BLUETOOTH permission
,I/NSApplication( 3532): Starting up...
,I/ActivityManager(  756): Killing 2779:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10003/pid_2779/cgroup.procs: No such file or directory
,V/MusicLeanback( 2800): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1633): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1633): onCreate
,D/SystemUpdateService( 1633): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1633): active receiver: enabled
,I/SystemUpdateService( 1633): showing system update notification
,I/ValidateNoPeople(  756): skipping global notification
,V/SystemUpdateService( 1633): retry (wakeup: false) in 3599977 ms
,D/SystemUpdateService( 1633): onDestroy
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3334): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3334): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3334): BLE supported!!
I/jxcore-log( 3334): 
,D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  756): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2800): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2800): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1633): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1633): onCreate
,D/SystemUpdateService( 1633): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1633): active receiver: enabled
,I/SystemUpdateService( 1633): showing system update notification
,I/ValidateNoPeople(  756): skipping global notification
,E/GpsLocationProvider(  756): No APN found to select.
,V/SystemUpdateService( 1633): retry (wakeup: false) in 3599987 ms
D/SystemUpdateService( 1633): onDestroy
,I/art     (  756): Explicit concurrent mark sweep GC freed 45521(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.231ms total 100.768ms
,D/Finsky  ( 2697): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2697): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1657): Vacuum at: now=1450736054489 tag=VacuumService
,I/PhenotypeConfigurator( 1657): Scheduling Phenotype for one-off execution 7727 seconds from now (1450736054806)
,D/GetConfigurationSnapshotOperation( 1657): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1657): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1657): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1657): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1657): Explicit concurrent mark sweep GC freed 91137(4MB) AllocSpace objects, 18(311KB) LOS objects, 40% free, 23MB/38MB, paused 876us total 48.726ms
,I/Keyboard.Facilitator.LanguageModelFlusher( 1060): run()
I/Keyboard.Facilitator( 1060): flushDynamicLanguageModels()
,I/ConfigService( 1657): onCreate
,I/ConfigService( 1657): onDestroy
,I/ActivityManager(  756): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3705 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3705): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3705):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3705):   adb logcat -s GAv4
,W/GAv4    ( 3705): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3705): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3705): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  756): Killing 2761:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  756): Client connection lost with reason: 4
,W/libprocessgroup(  756): failed to open /acct/uid_1000/pid_2761/cgroup.procs: No such file or directory
,I/ClearcutLoggerApiImpl( 1657): disconnect managed GoogleApiClient
,I/EventLogService( 1633): Aggregate from 1450734301218 (log), 1450734301179 (data)
,I/ActivityManager(  756): Killing 2635:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10070/pid_2635/cgroup.procs: No such file or directory
,W/bt-smp  ( 2151): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2151): Plain text(LSB ~ MSB) = 67 6d 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2151): Encrypted text(LSB ~ MSB) = 90 96 da 73 2c 7f f8 41 fd 02 83 ba 15 7f 6f 56 
,W/bt-btm  ( 2151): Stopping oneshot timer
,I/UsageStatsService(  756): User[0] Flushing usage stats to disk
,I/ProcessStatsService(  756): Prepared write state in 33ms
,I/ProcessStatsService(  756): Prepared write state in 3ms
,W/bt-smp  ( 2151): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2151): Plain text(LSB ~ MSB) = b3 e6 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2151): Encrypted text(LSB ~ MSB) = c0 e4 62 d0 fe ed 20 25 8e 96 76 f6 05 3a 11 bc 
W/bt-btm  ( 2151): Stopping oneshot timer
,I/ProcessStatsService(  756): Prepared write state in 5ms
,I/ActivityManager(  756): Killing 3233:com.google.android.apps.docs/u0a40 (adj 13): empty for 1812s
,I/ActivityManager(  756): Killing 3201:com.android.musicfx/u0a15 (adj 13): empty for 1812s
,I/ActivityManager(  756): Killing 1427:com.google.android.partnersetup/u0a13 (adj 13): empty for 1812s
,I/ActivityManager(  756): Killing 2927:android.process.acore/u0a4 (adj 13): empty for 1812s
,I/ActivityManager(  756): Killing 3096:com.google.android.gms:car/u0a8 (adj 15): empty for 1818s
,I/ActivityManager(  756): Killing 2867:com.android.providers.calendar/u0a2 (adj 15): empty for 1819s
,I/ActivityManager(  756): Killing 2060:com.google.android.calendar/u0a31 (adj 15): empty for 1849s
,W/libprocessgroup(  756): failed to open /acct/uid_10015/pid_3201/cgroup.procs: No such file or directory
,W/libprocessgroup(  756): failed to open /acct/uid_10031/pid_2060/cgroup.procs: No such file or directory
,W/libprocessgroup(  756): failed to open /acct/uid_10040/pid_3233/cgroup.procs: No such file or directory
,W/libprocessgroup(  756): failed to open /acct/uid_10013/pid_1427/cgroup.procs: No such file or directory
,W/libprocessgroup(  756): failed to open /acct/uid_10004/pid_2927/cgroup.procs: No such file or directory
,W/libprocessgroup(  756): failed to open /acct/uid_10008/pid_3096/cgroup.procs: No such file or directory
,W/libprocessgroup(  756): failed to open /acct/uid_10002/pid_2867/cgroup.procs: No such file or directory
,TIME-OUT KILL (timeout was 1800000ms)
```
