#### Test 50650278cb112b9_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3180): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3180):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3180):   adb logcat -s GAv4
W/GAv4    ( 3180): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3180): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3180): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3180): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2623): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3180): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3180): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  758): Killing 2592:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3180): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3180): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3180): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  758): failed to open /acct/uid_10069/pid_2592/cgroup.procs: No such file or directory
I/Icing   ( 1600): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
V/GLSActivity( 1576): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1600): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1600): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1600): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3232): 
D/AndroidRuntime( 3232): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3232): CheckJNI is OFF
D/AndroidRuntime( 3232): Calling main entry com.android.commands.am.Am
I/ActivityManager(  758): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  758): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3256 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3232): Shutting down VM
V/ActivityManager(  758): Display changed displayId=0
I/WebViewFactory( 3256): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3256): Time to load native libraries: 1 ms (timestamps 9084-9085)
I/LibraryLoader( 3256): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3256): Binding Chromium to main looper Looper (main, tid 1) {ebca9d8}
I/LibraryLoader( 3256): Expected native library version number "",actual native library version number ""
I/chromium( 3256): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3256): Initializing chromium process, singleProcess=true
W/art     ( 3256): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3256): ApplicationContext is null in ApplicationStatus
W/chromium( 3256): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3256): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3256): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3256): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/ActivityManager(  758): Killing 2542:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@345bd9d2:true
,W/libprocessgroup(  758): failed to open /acct/uid_10045/pid_2542/cgroup.procs: No such file or directory
,W/art     ( 3256): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3256): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3256): CordovaWebView is running on device made by: LGE
,W/art     ( 3256): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3256): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3256): Render dirty regions requested: true
,D/Atlas   ( 3256): Validating map...
,W/chromium( 3256): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3256): Initialized EGL, version 1.4
D/OpenGLRenderer( 3256): Enabling debug mode 0
,I/Keyboard.Facilitator( 1081): onFinishInput()
,W/IInputConnectionWrapper( 3256): showStatusIcon on inactive InputConnection
,I/ActivityManager(  758): Displayed com.test.thalitest/.MainActivity: +463ms (total +56s266ms)
,W/BindingManager( 3256): Cannot call determinedVisibility() - never saw a connection for the pid: 3256
,D/JsMessageQueue( 3256): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3256): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342720
,D/JX-Cordova( 3256): jxcore cordova android initializing
,W/jxcore-log( 3256): Initializing JXcore engine
W/jxcore-log( 3256): JXcore engine is ready
,W/jxcore-log( 3256): Starting JXcore engine
,W/.test.thalitest( 3256): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7982]" dev="sockfs" ino=7982 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3256): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3256): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9553]" dev="sockfs" ino=9553 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3256): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19892]" dev="sockfs" ino=19892 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3256): Platform android
W/jxcore-log( 3256): 
W/jxcore-log( 3256): Process ARCH arm
W/jxcore-log( 3256): 
,I/jxcore-log( 3256): JXcore Cordova bridge is ready!
I/jxcore-log( 3256): 
W/jxcore-log( 3256): JXcore engine is started
,I/chromium( 3256): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3256): Toggling radios to true
I/jxcore-log( 3256): 
,D/BluetoothAdapter( 3256): enable(): BT is already enabled..!
,D/WifiService(  758): New client listening to asynchronous messages
D/WifiService(  758): setWifiEnabled: true pid=3256, uid=10270
E/WifiService(  758): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3256): Radios toggled
I/jxcore-log( 3256): 
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3256): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): Perf Test app loaded loaded
I/jxcore-log( 3256): 
I/jxcore-log( 3256): check test folder
I/jxcore-log( 3256): 
I/jxcore-log( 3256): found test : ./testFindPeers.js
I/jxcore-log( 3256): 
I/wpa_supplicant( 1045): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  758): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  758): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1576): Read error: ssl=0x9be89e00: I/O error during system call, Connection timed out
V/NativeCrypto( 1576): SSL shutdown failed: ssl=0x9be89e00: I/O error during system call, Broken pipe
I/jxcore-log( 3256): found test : ./testSendData.js
I/jxcore-log( 3256): 
,D/ConnectivityService(  758): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): ValidatedState{ when=-2ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=-2ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  758): Start Disconnecting Watchdog 1
,E/native  (  758): do suspend true
,I/wpa_supplicant( 1045): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  758): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  758): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  758): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1600): CM callback handler got msg 524292
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  758): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1221): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  758): NetworkAgent: NetworkAgent channel lost
,I/chromium( 3256): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/GLSActivity( 1576): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1576): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1366): OkHttp exception
,W/EventLoggerService( 1366): Unable to send logs Error code: 262146
,I/wpa_supplicant( 1045): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1045): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1045): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1045): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  758): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  758): Start Dhcp Watchdog 2
,E/native  (  758): do suspend false
,E/WifiStateMachine(  758): scanCount==0 - aborting
,I/dhcpcd  ( 3356): version 5.5.6 starting
,E/dhcpcd  ( 3356): get_duid: Read-only file system
,I/dhcpcd  ( 3356): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3356): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3356): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  758): do suspend true
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  758): Adding iface wlan0 to network 101
,E/ConnectivityService(  758): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  758): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  758): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  758): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  758): Setting Dns servers for network 101 to [/192.168.1.1]
E/WifiStateMachine(  758): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Nat464Xlat(  758): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  758): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  758): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758):    accepting network in place of null
,D/CSLegacyTypeTracker(  758): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  758): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  758): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1600): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 15 Dec 2015 03:21:41 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450149701182], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450149701162]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Validated
,D/ConnectivityService(  758): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  758): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1221): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1600): CM callback handler got msg 524290
,D/Nat464Xlat(  758): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  758): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1600): CM callback handler got msg 524295
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  758): MasterInitialState.processMessage what=3
D/Tethering(  758): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2740): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 2740): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2740): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  758): No APN found to select.
,E/GpsLocationProvider(  758): No APN found to select.
,I/SystemUpdateService( 1600): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1600): onCreate
,D/SystemUpdateService( 1600): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1600): active receiver: enabled
,I/SystemUpdateService( 1600): showing system update notification
,I/ValidateNoPeople(  758): skipping global notification
,V/SystemUpdateService( 1600): retry (wakeup: false) in 3599987 ms
,I/ActivityManager(  758): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3431 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1600): onDestroy
,I/GAv4    ( 3431): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3431):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3431):   adb logcat -s GAv4
,W/GAv4    ( 3431): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3431): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3431): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  758): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/WebViewFactory( 3431): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3431): Time to load native libraries: 2 ms (timestamps 6017-6019)
I/LibraryLoader( 3431): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3431): Binding Chromium to main looper Looper (main, tid 1) {b5d500a}
I/LibraryLoader( 3431): Expected native library version number "",actual native library version number ""
,I/chromium( 3431): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3431): Initializing chromium process, singleProcess=true
,W/art     ( 3431): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3431): ApplicationContext is null in ApplicationStatus
,W/chromium( 3431): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3431): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3431): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3431): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3431): Requires BLUETOOTH permission
,I/NSApplication( 3431): Starting up...
,I/ActivityManager(  758): Killing 2705:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10003/pid_2705/cgroup.procs: No such file or directory
,V/MusicLeanback( 2740): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1600): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1600): onCreate
,D/SystemUpdateService( 1600): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1600): active receiver: enabled
,I/SystemUpdateService( 1600): showing system update notification
,I/ValidateNoPeople(  758): skipping global notification
,V/SystemUpdateService( 1600): retry (wakeup: false) in 3599963 ms
,D/SystemUpdateService( 1600): onDestroy
,I/jxcore-log( 3256): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 3256): 
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  758): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2740): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2740): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1600): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/art     (  758): Explicit concurrent mark sweep GC freed 44296(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.200ms total 61.097ms
,D/SystemUpdateService( 1600): onCreate
,D/SystemUpdateService( 1600): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/GpsLocationProvider(  758): No APN found to select.
,I/SystemUpdateService( 1600): active receiver: enabled
,I/SystemUpdateService( 1600): showing system update notification
,I/ValidateNoPeople(  758): skipping global notification
,V/SystemUpdateService( 1600): retry (wakeup: false) in 3599961 ms
,D/SystemUpdateService( 1600): onDestroy
,D/Finsky  ( 2623): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2623): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,W/ProcessCpuTracker(  758): Skipping unknown process pid 3536
,W/ProcessCpuTracker(  758): Skipping unknown process pid 3539
,W/ProcessCpuTracker(  758): Skipping unknown process pid 3544
W/ProcessCpuTracker(  758): Skipping unknown process pid 3545
,V/GLSActivity( 1576): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1576): Vacuum at: now=1450149714239 tag=VacuumService
,I/PhenotypeConfigurator( 1576): Scheduling Phenotype for one-off execution 12591 seconds from now (1450149714496)
,D/GetConfigurationSnapshotOperation( 1576): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1576): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1576): Using platform SSLCertificateSocketFactory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1081): run()
I/Keyboard.Facilitator( 1081): flushDynamicLanguageModels()
,I/ConfigService( 1576): onCreate
,I/ConfigService( 1576): onDestroy
,I/ClearcutLoggerApiImpl( 1576): disconnect managed GoogleApiClient
,I/jxcore-log( 3256): Connected to the server!
I/jxcore-log( 3256): 
,I/chromium( 3256): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3256): --- start :testFindPeers.js---
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): testFindPeers created [object Object]
I/jxcore-log( 3256): 
I/jxcore-log( 3256): serverPort is 8876
I/jxcore-log( 3256): 
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): initialize: 34:FC:EF:11:AE:67 LGE-Nexus 5_PT4145
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3256): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): setState: INITIALIZED
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3256): start: OK
I/jxcore-log( 3256): StartBroadcasting started ok
I/jxcore-log( 3256): 
I/chromium( 3256): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): startWifiPeerDiscovery: Already started
,I/io.jxcore.node.ConnectionHelper( 3256): onConnectionManagerStateChanged: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/io.jxcore.node.ConnectionHelper( 3256): onConnectionManagerStateChanged: RUNNING
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3256): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1701"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT1701 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1701"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1701"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1701"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1701"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1701"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 34:FC:EF:11:B1:66, peer name: LGE-Nexus 5_PT1701, peer ID: 34:FC:EF:11:B1:66, Wi-Fi Direct device name: Android_2dc2, Wi-Fi Direct address: 52:55:27:f0:ff:f0
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Adding peer with ID 34:FC:EF:11:B1:66
,I/jxcore-log( 3256): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:B1:66","peerName":"LGE-Nexus 5_PT1701","peerAvailable":true}]
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): Found peer : 34:FC:EF:11:B1:66, peerAvailable: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): weAreDoneNow
I/jxcore-log( 3256): 
I/jxcore-log( 3256): done, now sending data to server
I/jxcore-log( 3256): 
,W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT301","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT301 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT301","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT301","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT301","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT301","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT301","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: samsung-SM-A500FU_PT301, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: A5-1, Wi-Fi Direct address: 7e:f9:0e:37:96:ac
,I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:37:96:AB,
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/jxcore-log( 3256): --- start :testFindPeers.js---
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): testFindPeers created [object Object]
I/jxcore-log( 3256): 
I/jxcore-log( 3256): serverPort is 8876
I/jxcore-log( 3256): 
I/jxcore-log( 3256): weAreDoneNow
I/jxcore-log( 3256): 
I/jxcore-log( 3256): done, now sending data to server
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): done, now sending data to server
I/jxcore-log( 3256): 
,I/chromium( 3256): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3256): teardown
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): testFindPeers stopped
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): setState: NOT_INITIALIZED
,I/jxcore-log( 3256): StopBroadcasting went ok
I/jxcore-log( 3256): 
,I/chromium( 3256): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3256): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 3256): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/jxcore-log( 3256): --- start :testSendData.js---
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":22}bt-address length : 0
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): daya100000
I/jxcore-log( 3256): 
I/jxcore-log( 3256): check server
I/jxcore-log( 3256): 
I/jxcore-log( 3256): serverPort is 55011
I/jxcore-log( 3256): 
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): initialize: 34:FC:EF:11:AE:67 LGE-Nexus 5_PT4145
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3256): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): setState: INITIALIZED
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): setState: RUNNING
I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3256): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:B1:66","peerName":"LGE-Nexus 5_PT1701","peerAvailable":true},{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT301","peerAvailable":true}]
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Found peer : LGE-Nexus 5_PT1701, Available: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Found peer : samsung-SM-A500FU_PT301, Available: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): startWithNextDevice
I/jxcore-log( 3256): 
I/jxcore-log( 3256): device[1]: 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:26:41.783Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:26:41.783Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:26:41.783Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
,D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: Android_2dc2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
I/io.jxcore.node.ConnectionHelper( 3256): start: OK
,I/jxcore-log( 3256): StartBroadcasting started ok
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:26:41.791Z SendDataTCPServer.js: TCP/IP server is bound to port: 55011
I/jxcore-log( 3256): 
I/chromium( 3256): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 3256): onConnectionManagerStateChanged: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 3256): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 309)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 2098): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): startServiceDiscovery: Invalid state, try calling restart()
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
E/bt-btif ( 2098): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2098): Entering PendingCommandState State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothAdapterProperties( 2098): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,I/BluetoothBondStateMachine( 2098): StableState(): Entering Off State
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT1701 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 309)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 310)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 310)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 309)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 310)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 77 bytes successfully (thread ID: 310)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [34:FC:EF:11:B1:66 LGE-Nexus 5_PT1701 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT1701 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 310)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT1701 34:FC:EF:11:B1:66]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: 34:FC:EF:11:B1:66, name: LGE-Nexus 5_PT1701, Bluetooth address: 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:11:B1:66 already in the list
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID 34:FC:EF:11:B1:66, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 311)
D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 51506
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 51506 (peer ID: 34:FC:EF:11:B1:66)
I/jxcore-log( 3256): 2015-12-15T03:26:46.923Z SendDataConnector.js: CLIENT connected to 51506, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:26:46.924Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 51506
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 311)
,I/jxcore-log( 3256): 2015-12-15T03:26:46.930Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 313, name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 312, name: Sender)
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3256): 2015-12-15T03:26:47.977Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:26:48.354Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3256): 
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12826
,I/jxcore-log( 3256): 2015-12-15T03:26:48.750Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3256): 
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 3256): 2015-12-15T03:26:48.824Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3256): 
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3256): 2015-12-15T03:26:49.619Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3256): 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/jxcore-log( 3256): 2015-12-15T03:26:50.885Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:26:51.488Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:26:52.373Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT3417"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT3417"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT3417, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Adding peer with ID 00:F4:6F:30:E0:6C
I/jxcore-log( 3256): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"samsung-SM-G800F_PT3417","peerAvailable":true}]
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Found peer : samsung-SM-G800F_PT3417, Available: true
I/jxcore-log( 3256): 
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/jxcore-log( 3256): 2015-12-15T03:26:53.641Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): teardown
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): testSendData stopped
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): setState: NOT_INITIALIZED
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveAllOutgoingConnections: Peer ID: 34:FC:EF:11:B1:66
I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 313
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 312
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 312, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 34:FC:EF:11:B1:66 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 313, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 34:FC:EF:11:B1:66 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 312, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 313, name: Receiver)
,I/jxcore-log( 3256): StopBroadcasting went ok
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:26:54.137Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:26:54.138Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:26:54.138Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:26:54.140Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:26:54.142Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3256): 
I/chromium( 3256): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 3256): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 3256): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/jxcore-log( 3256): --- start :testSendData.js---
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":23}bt-address length : 0
I/jxcore-log( 3256): 
I/jxcore-log( 3256): daya100000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): check server
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): serverPort is 36677
I/jxcore-log( 3256): 
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): initialize: 34:FC:EF:11:AE:67 LGE-Nexus 5_PT4145
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3256): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): setState: INITIALIZED
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): setState: RUNNING
,I/jxcore-log( 3256): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:B1:66","peerName":"LGE-Nexus 5_PT1701","peerAvailable":true},{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT301","peerAvailable":true},{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"samsung-SM-G800F_PT3417","peerAvailable":true}]
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Found peer : LGE-Nexus 5_PT1701, Available: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Found peer : samsung-SM-A500FU_PT301, Available: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Found peer : samsung-SM-G800F_PT3417, Available: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): startWithNextDevice
I/jxcore-log( 3256): 
I/jxcore-log( 3256): device[1]: 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:26:54.202Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:26:54.202Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:26:54.202Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: Android_2dc2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Waiting for incoming connections...
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: Nexus 5 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
I/io.jxcore.node.ConnectionHelper( 3256): start: OK
,I/jxcore-log( 3256): StartBroadcasting started ok
I/jxcore-log( 3256): 
I/jxcore-log( 3256): null
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:26:54.216Z SendDataTCPServer.js: TCP/IP server is bound to port: 36677
I/jxcore-log( 3256): 
I/chromium( 3256): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 315)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 3256): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/io.jxcore.node.ConnectionHelper( 3256): onConnectionManagerStateChanged: RUNNING
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 8
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:9, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 9
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 315)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 315)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 10
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 11
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 315)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 315)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local services cleared successfully
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 12
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 13
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 315)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 315)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 14
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 15
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 315)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 315)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 16
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:17, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 17
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 315)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Maximum number of retries (5) reached, giving up... (thread ID: 315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 315)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 LGE-Nexus 5_PT1701 34:FC:EF:11:B1:66]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): shutdown
,I/jxcore-log( 3256): 2015-12-15T03:27:00.402Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:27:00.402Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:27:00.404Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
,W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d231902:true
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3256): 2015-12-15T03:27:05.406Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:27:05.410Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: XT1039_8c05 f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: XT1039_8c05 f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: XT1039_8c05 f4:f1:e1:5c:43:c8
D/WifiP2pManager( 3256): Ignored { when=-5ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3256): Ignored { when=-11ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
,I/jxcore-log( 3256): 2015-12-15T03:27:10.417Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:27:10.421Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:27:10.424Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:27:10.427Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
,I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: Android_2dc2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: Nexus 5 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 316)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Nexus 5
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:18, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 18
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:19, failed to find channle,                                       status:1, scn:0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 316)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 316)
,W/bt-btif ( 2098): invalid rfc slot id: 19
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 20
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 21
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 316)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 316)
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 22
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 23
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 316)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 316)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 24
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 25
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 316)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 316)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback,
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 26
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 27
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 316)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Maximum number of retries (5) reached, giving up... (thread ID: 316)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 316)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 LGE-Nexus 5_PT1701 34:FC:EF:11:B1:66]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): shutdown
,I/jxcore-log( 3256): 2015-12-15T03:27:18.581Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:27:18.590Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:27:18.590Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3256): 2015-12-15T03:27:23.592Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:27:23.593Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT37","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT37 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT37","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT37","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT37","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT37","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT37, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:9a:02:7b:60:ac
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Adding peer with ID 58:3F:54:73:64:C0
I/jxcore-log( 3256): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"LGE-LG-D855_PT37","peerAvailable":true}]
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): Found peer : LGE-LG-D855_PT37, Available: true
I/jxcore-log( 3256): 
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
,I/jxcore-log( 3256): 2015-12-15T03:27:28.603Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:27:28.604Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:27:28.604Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:27:28.605Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: Android_2dc2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: Nexus 5 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 317)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Nexus 5
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:28, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 28
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 29
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 317)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 30
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 31
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 32
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 33
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 34
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 35
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 36
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 37
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Maximum number of retries (5) reached, giving up... (thread ID: 317)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 317)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 LGE-Nexus 5_PT1701 34:FC:EF:11:B1:66]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): shutdown
I/jxcore-log( 3256): 2015-12-15T03:27:32.494Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:27:32.495Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:27:32.495Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3256): 2015-12-15T03:27:37.496Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:27:37.497Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:27:42.505Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:27:42.506Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:27:42.507Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:27:42.512Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: Android_2dc2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: Nexus 5 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 318)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Nexus 5
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 38
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:39, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 39
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 318)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 318)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 40
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 41
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 318)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 318)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 42
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:43, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 43
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 318)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 318)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:44, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 44
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 45
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 318)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 318)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 46
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 47
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 318)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Maximum number of retries (5) reached, giving up... (thread ID: 318)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 318)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 LGE-Nexus 5_PT1701 34:FC:EF:11:B1:66]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): shutdown
I/jxcore-log( 3256): 2015-12-15T03:27:45.644Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:27:45.645Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:27:45.645Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3256): 2015-12-15T03:27:50.646Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:27:50.647Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:27:55.651Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:27:55.652Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:27:55.653Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:27:55.653Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: Android_2dc2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: Nexus 5 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 319)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Nexus 5
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:48, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 48
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 49
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 319)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 319)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 50
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 51
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 319)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 319)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:52, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 52
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:53, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 53
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 319)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 319)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 54
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 55
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 319)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 319)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:56, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 56
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 57
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 319)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Maximum number of retries (5) reached, giving up... (thread ID: 319)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 319)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 LGE-Nexus 5_PT1701 34:FC:EF:11:B1:66]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): shutdown
I/jxcore-log( 3256): 2015-12-15T03:28:00.730Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:28:00.730Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): oneRoundDownNow
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:28:00.734Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
,I/jxcore-log( 3256): 2015-12-15T03:28:00.737Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3256): 
I/jxcore-log( 3256): ---- round done--------
I/jxcore-log( 3256): 
I/jxcore-log( 3256): startWithNextDevice
I/jxcore-log( 3256): 
I/jxcore-log( 3256): device[2]: 7C:F9:0E:37:96:AB
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:28:00.747Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:28:00.758Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:28:00.758Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: A5-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 320)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Nexus 5
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 58
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:1, scn:0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 320)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 320)
,W/bt-btif ( 2098): invalid rfc slot id: 59
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2098): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 2098): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2098): Entering PendingCommandState State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2098): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2098): StableState(): Entering Off State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT301 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 2 (thread ID: 320)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 321)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 321)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 320)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 321)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 82 bytes successfully (thread ID: 321)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT301 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT301 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT301 7C:F9:0E:37:96:AB]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: 7C:F9:0E:37:96:AB, name: samsung-SM-A500FU_PT301, Bluetooth address: 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID 7C:F9:0E:37:96:AB, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 321)
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 322)
D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 53326
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 53326 (peer ID: 7C:F9:0E:37:96:AB)
I/jxcore-log( 3256): 2015-12-15T03:28:13.694Z SendDataConnector.js: CLIENT connected to 53326, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:28:13.694Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:28:13.696Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 53326
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 322)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 324, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 323, name: Sender)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3256): 2015-12-15T03:28:14.294Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:28:14.476Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3256): 
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 3256): 2015-12-15T03:28:14.570Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:28:14.643Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3256): 
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3256): 2015-12-15T03:28:14.723Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:28:14.764Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:28:14.856Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:28:14.911Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:28:14.992Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:28:15.025Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:28:15.026Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): oneRoundDownNow
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:28:15.033Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:28:15.034Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
I/io.jxcore.node.OutgoingSocketThread( 3256): close
,I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 324
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 323
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 323, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 324, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:37:96:AB
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 323, name: Sender)
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 324, name: Receiver)
,I/jxcore-log( 3256): 2015-12-15T03:28:15.074Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3256): 
I/jxcore-log( 3256): ---- round done--------
I/jxcore-log( 3256): 
I/jxcore-log( 3256): startWithNextDevice
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): device[3]: 00:F4:6F:30:E0:6C
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:28:15.076Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:28:15.076Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:28:15.076Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 325)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
E/BluetoothRemoteDevices( 2098): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: A5-1
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
E/bt-btif ( 2098): check_cod: remote_cod = 0x5a020c
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2098): Entering PendingCommandState State
,E/BluetoothEventManager( 2686): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 2098): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 2098): StableState(): Entering Off State
,E/BluetoothEventManager( 2686): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
,W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 325)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 326)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 325)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 326)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 82 bytes successfully (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 326)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
,I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT3417, Bluetooth address: 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID 00:F4:6F:30:E0:6C, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 327)
,D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 57246
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 57246 (peer ID: 00:F4:6F:30:E0:6C)
,I/jxcore-log( 3256): 2015-12-15T03:28:21.361Z SendDataConnector.js: CLIENT connected to 57246, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:28:21.362Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 57246
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 327)
,I/jxcore-log( 3256): 2015-12-15T03:28:21.383Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 328, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 329, name: Receiver)
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2098): dm_pm_timer expires
W/bt-btif ( 2098): dm_pm_timer expires 0
W/bt-btif ( 2098): proc dm_pm_timer expires
,I/jxcore-log( 3256): 2015-12-15T03:28:31.794Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:28:31.795Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:28:31.796Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:28:31.797Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:28:31.803Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3256): 
,E/io.jxcore.node.StreamCopyingThread( 3256): Input stream got -1 on read (thread ID: 328, thread name: Sender)
E/io.jxcore.node.OutgoingSocketThread( 3256): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Input stream got -1 on read
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 329
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 328
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 329, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 329, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 328, name: Sender)
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 3256): 2015-12-15T03:28:36.801Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:28:36.802Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3256): 
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:28:41.806Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:28:41.806Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:28:41.807Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:28:41.813Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
,I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 330)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [00:f4:6f:30:e0:6c]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: S5mini-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
,W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 330)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 331)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 331)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 330)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 331)
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 82 bytes successfully (thread ID: 331)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 331)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT3417, Bluetooth address: 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
,I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
,I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID 00:F4:6F:30:E0:6C, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 332)
,D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 47493
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 47493 (peer ID: 00:F4:6F:30:E0:6C)
I/jxcore-log( 3256): 2015-12-15T03:28:49.132Z SendDataConnector.js: CLIENT connected to 47493, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:28:49.133Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 47493
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 332)
,I/jxcore-log( 3256): 2015-12-15T03:28:49.156Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 333, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 334, name: Receiver)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3256): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3256): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,W/bt-btif ( 2098): dm_pm_timer expires
W/bt-btif ( 2098): dm_pm_timer expires 0
,W/bt-btif ( 2098): proc dm_pm_timer expires
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/jxcore-log( 3256): 2015-12-15T03:28:59.584Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:28:59.584Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:28:59.586Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:28:59.587Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:28:59.597Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3256): 
,E/io.jxcore.node.StreamCopyingThread( 3256): Input stream got -1 on read (thread ID: 333, thread name: Sender)
E/io.jxcore.node.OutgoingSocketThread( 3256): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Input stream got -1 on read
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 334
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 333
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 334, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 333, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 334, name: Receiver)
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 3256): 2015-12-15T03:29:04.592Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:04.593Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3256): 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
,I/jxcore-log( 3256): 2015-12-15T03:29:09.602Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:09.603Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:09.604Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:09.604Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 335)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 335)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 336)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 336)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 335)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 336)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 82 bytes successfully (thread ID: 336)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 336)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT3417, Bluetooth address: 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID 00:F4:6F:30:E0:6C, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 337)
,D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 32853
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 32853 (peer ID: 00:F4:6F:30:E0:6C)
I/jxcore-log( 3256): 2015-12-15T03:29:12.941Z SendDataConnector.js: CLIENT connected to 32853, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:12.942Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 32853
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 337)
,I/jxcore-log( 3256): 2015-12-15T03:29:12.963Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 339, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 338, name: Sender)
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2098): dm_pm_timer expires
W/bt-btif ( 2098): dm_pm_timer expires 0
W/bt-btif ( 2098): proc dm_pm_timer expires
,I/jxcore-log( 3256): 2015-12-15T03:29:23.409Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:23.410Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:23.411Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:23.412Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:23.413Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3256): 
,E/io.jxcore.node.StreamCopyingThread( 3256): Input stream got -1 on read (thread ID: 338, thread name: Sender)
E/io.jxcore.node.OutgoingSocketThread( 3256): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Input stream got -1 on read
,I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 339
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 338
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 339, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 339, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 338, name: Sender)
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,E/BluetoothRemoteDevices( 2098): aclStateChangeCallback: Device is NULL
W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 3256): 2015-12-15T03:29:28.413Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:28.413Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully,
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
E/bt-btif ( 2098): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2098): Entering PendingCommandState State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 90:E7:C4:F6:69:77 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for 90:E7:C4:F6:69:77, but we have no record of that device.
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
,D/BluetoothAdapterProperties( 2098): Failed to remove device: 90:E7:C4:F6:69:77
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2098): StableState(): Entering Off State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 90:E7:C4:F6:69:77 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for 90:E7:C4:F6:69:77, but we have no record of that device.
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:255
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Incoming connection initialized (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 340)
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:29:33.416Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:33.416Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:33.416Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:33.416Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 341)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): onBytesRead: Read 81 bytes successfully (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Got valid identity from [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT2862 90:E7:C4:F6:69:77]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 340)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): removeThreadFromList: Removing thread with ID 340
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Handshake thread disposed (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onIncomingConnectionConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT2862 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 340)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT2862 90:E7:C4:F6:69:77]
,I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Incoming connection, peer ID: 90:E7:C4:F6:69:77, name: HTC-HTC One M8s_PT2862, Bluetooth address: 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Adding peer with ID 90:E7:C4:F6:69:77
I/jxcore-log( 3256): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC-HTC One M8s_PT2862","peerAvailable":true}]
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Found peer : HTC-HTC One M8s_PT2862, Available: true
I/jxcore-log( 3256): 
,I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Incoming socket thread, for peer with ID 90:E7:C4:F6:69:77, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3256): Entering thread (ID: 342)
,I/io.jxcore.node.IncomingSocketThread( 3256): Local host address: localhost/127.0.0.1, port: 36677
D/io.jxcore.node.IncomingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3256): Exiting thread (ID: 342)
,I/jxcore-log( 3256): 2015-12-15T03:29:34.827Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3256): 
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 343, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 344, name: Receiver)
,I/jxcore-log( 3256): 2015-12-15T03:29:35.663Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3256): 
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3256): 2015-12-15T03:29:35.837Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:35.912Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:36.122Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:36.286Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:36.395Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3256): 
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 3256): 2015-12-15T03:29:36.503Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3256): 
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3256): 2015-12-15T03:29:37.552Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:37.558Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:37.632Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:37.639Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:37.730Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3256): 
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3256): 2015-12-15T03:29:37.766Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:37.916Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:38.001Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:38.009Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3256): 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3256): 2015-12-15T03:29:38.279Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:38.312Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:38.441Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:38.448Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:38.454Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:38.540Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:38.610Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:38.616Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:38.704Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:38.710Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:38.723Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:38.804Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:38.812Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:38.903Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:38.912Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:38.971Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:39.009Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3256): 
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,I/jxcore-log( 3256): 2015-12-15T03:29:39.060Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:39.067Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:39.151Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:39.189Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:39.244Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:39.272Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:39.364Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:39.372Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:39.436Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3256): 
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3256): 2015-12-15T03:29:39.469Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:39.511Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:39.524Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:39.561Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:39.570Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:39.610Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:39.615Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3256): 
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 341)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 345)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 341)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 345)
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
,W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2098): invalid rfc slot id: 7
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 344, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3256): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Incoming connection, peer with ID 90:E7:C4:F6:69:77 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 342
I/io.jxcore.node.IncomingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 344
I/io.jxcore.node.IncomingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 343
I/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 343, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Incoming connection, peer with ID 90:E7:C4:F6:69:77 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
,I/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3256): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 343, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 344, name: Receiver)
,I/jxcore-log( 3256): 2015-12-15T03:29:40.044Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3256): 
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 82 bytes successfully (thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 345)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT3417, Bluetooth address: 00:F4:6F:30:E0:6C
,D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID 00:F4:6F:30:E0:6C, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 346)
D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 49807
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 49807 (peer ID: 00:F4:6F:30:E0:6C)
,I/jxcore-log( 3256): 2015-12-15T03:29:40.871Z SendDataConnector.js: CLIENT connected to 49807, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:40.873Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 49807
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 346)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 348, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 347, name: Sender)
,I/jxcore-log( 3256): 2015-12-15T03:29:40.911Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,W/bt-rfcomm( 2098): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 2098): RFCOMM_DisconnectInd LCID:0x44
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3256): 2015-12-15T03:29:42.286Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:42.517Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:42.894Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:42.972Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:43.640Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:43.716Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:43.803Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:43.935Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:44.160Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:44.250Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:44.251Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3256): 
I/jxcore-log( 3256): oneRoundDownNow
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:44.253Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:44.253Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 348
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 347
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 347, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 348, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:F4:6F:30:E0:6C
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 347, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 348, name: Receiver)
,I/jxcore-log( 3256): 2015-12-15T03:29:44.301Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3256): 
I/jxcore-log( 3256): ---- round done--------
I/jxcore-log( 3256): 
I/jxcore-log( 3256): startWithNextDevice
I/jxcore-log( 3256): 
I/jxcore-log( 3256): device[4]: 58:3F:54:73:64:C0
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:44.305Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:44.305Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:44.306Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
,I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 349)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: HTC One M8s
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2098): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: S5mini-1
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 2098): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2098): Entering PendingCommandState State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2098): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2098): StableState(): Entering Off State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [58:3F:54:73:64:C0 LGE-LG-D855_PT37 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 349)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 350)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 350)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 349)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 350)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 75 bytes successfully (thread ID: 350)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [58:3F:54:73:64:C0 LGE-LG-D855_PT37 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [58:3F:54:73:64:C0 LGE-LG-D855_PT37 58:3F:54:73:64:C0]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT37 58:3F:54:73:64:C0]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: 58:3F:54:73:64:C0, name: LGE-LG-D855_PT37, Bluetooth address: 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 58:3F:54:73:64:C0 already in the list
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID 58:3F:54:73:64:C0, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 350)
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 351)
,D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 44193
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 44193 (peer ID: 58:3F:54:73:64:C0)
I/jxcore-log( 3256): 2015-12-15T03:29:49.763Z SendDataConnector.js: CLIENT connected to 44193, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:49.764Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 44193
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 351)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 353, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 352, name: Sender)
,I/jxcore-log( 3256): 2015-12-15T03:29:49.801Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3256): 2015-12-15T03:29:50.650Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3256): 
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18766
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3256): 2015-12-15T03:29:50.754Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:50.876Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3256): 
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 3256): 2015-12-15T03:29:50.889Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:50.957Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:51.036Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:51.095Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:51.139Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:51.261Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:29:51.680Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:51.680Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3256): 
I/jxcore-log( 3256): oneRoundDownNow
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:51.682Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:51.682Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 58:3F:54:73:64:C0
I/io.jxcore.node.OutgoingSocketThread( 3256): close
,I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 353
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 352
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 352, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 58:3F:54:73:64:C0 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 353, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 58:3F:54:73:64:C0 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Successfully disconnected (peer ID: 58:3F:54:73:64:C0
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 352, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 353, name: Receiver)
,I/jxcore-log( 3256): 2015-12-15T03:29:51.739Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3256): 
I/jxcore-log( 3256): ---- round done--------
I/jxcore-log( 3256): 
I/jxcore-log( 3256): startWithNextDevice
I/jxcore-log( 3256): 
I/jxcore-log( 3256): device[5]: 90:E7:C4:F6:69:77
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:51.744Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:51.744Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:29:51.745Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to HTC One M8s in address 90:E7:C4:F6:69:77
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: HTC One M8s 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to HTC One M8s in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 354)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: G3-1
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 67
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [90:e7:c4:f6:69:77]: 6, f, 410d
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,I/BluetoothClassifier( 1366): Bluetooth Device Name: HTC One M8s
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT2862 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 354)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 355)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 355)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 354)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 355)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 81 bytes successfully (thread ID: 355)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT2862 90:E7:C4:F6:69:77]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT2862 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT2862 90:E7:C4:F6:69:77]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: 90:E7:C4:F6:69:77, name: HTC-HTC One M8s_PT2862, Bluetooth address: 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 90:E7:C4:F6:69:77 already in the list
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID 90:E7:C4:F6:69:77, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 355)
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 356)
D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 53410
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 53410 (peer ID: 90:E7:C4:F6:69:77)
I/jxcore-log( 3256): 2015-12-15T03:30:00.612Z SendDataConnector.js: CLIENT connected to 53410, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:30:00.612Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 53410
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 356)
,I/jxcore-log( 3256): 2015-12-15T03:30:00.634Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 357, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 358, name: Receiver)
,I/ActivityManager(  758): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3740 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3740): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3740):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3740):   adb logcat -s GAv4
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,W/GAv4    ( 3740): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3740): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3740): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  758): Killing 2562:com.google.android.gm/u0a70 (adj 15): empty #17
,I/jxcore-log( 3256): 2015-12-15T03:30:01.298Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3256): 
,W/libprocessgroup(  758): failed to open /acct/uid_10070/pid_2562/cgroup.procs: No such file or directory
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,I/jxcore-log( 3256): 2015-12-15T03:30:01.690Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3256): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12826
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,I/jxcore-log( 3256): 2015-12-15T03:30:01.757Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3256): 
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 3256): 2015-12-15T03:30:01.841Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:30:01.965Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:30:02.161Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:30:02.456Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:30:02.737Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:30:03.032Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3256): 
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3256): 2015-12-15T03:30:03.195Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:30:03.196Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3256): 
I/jxcore-log( 3256): oneRoundDownNow
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:30:03.201Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:30:03.203Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 90:E7:C4:F6:69:77
I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 358
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 357
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 357, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 90:E7:C4:F6:69:77 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 358, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 90:E7:C4:F6:69:77 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Successfully disconnected (peer ID: 90:E7:C4:F6:69:77
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 358, name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 357, name: Sender)
,I/jxcore-log( 3256): 2015-12-15T03:30:03.245Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3256): 
I/jxcore-log( 3256): ---- round done--------
I/jxcore-log( 3256): 
I/jxcore-log( 3256): startWithNextDevice
I/jxcore-log( 3256): 
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: HTC One M8s
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: XT1039_8c05 f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3256): Ignored { when=-12ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3538"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT3538 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3538"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3538"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT3538, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: , Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Adding peer with ID B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3256): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"HTC-HTC Desire 820_PT3538","peerAvailable":true}]
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Found peer : HTC-HTC Desire 820_PT3538, Available: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): startWithNextDevice
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): device[6]: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:30:13.365Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:30:13.368Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:30:13.371Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
,I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null B4:CE:F6:AB:A4:6A
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: B4:CE:F6:AB:A4:6A)
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address B4:CE:F6:AB:A4:6A (thread ID: 359)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 69
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 70
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 359)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 359)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): Connection timeout
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:71, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 71
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2098): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
E/bt-btif ( 2098): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2098): Entering PendingCommandState State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
,D/BluetoothAdapterProperties( 2098): Failed to remove device: B4:CE:F6:AB:A4:6A
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2098): StableState(): Entering Off State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT3538 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT37","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT37 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT37","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT37","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9469","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9469 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9469","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9469","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Cancelled: Connection timeout [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT3538 B4:CE:F6:AB:A4:6A]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using system decided port, total number of attempts: 2 (thread ID: 359)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 359)
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT37, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:9a:02:7b:60:ac
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 58:3F:54:73:64:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: B0:C5:59:3F:75:69, peer name: samsung-SM-G900F_PT9469, peer ID: B0:C5:59:3F:75:69, Wi-Fi Direct device name: , Wi-Fi Direct address: ee:1f:72:18:8b:78
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Adding peer with ID B0:C5:59:3F:75:69
I/jxcore-log( 3256): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT9469","peerAvailable":true}]
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Found peer : samsung-SM-G900F_PT9469, Available: true
I/jxcore-log( 3256): 
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/jxcore-log( 3256): 2015-12-15T03:30:53.498Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:30:53.499Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:30:53.499Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,I/ActivityManager(  758): Killing 1992:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10031/pid_1992/cgroup.procs: No such file or directory
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3256): 2015-12-15T03:30:58.504Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:30:58.504Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3256): 
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID B4:CE:F6:AB:A4:6A
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: B4:CE:F6:AB:A4:6A), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:31:03.510Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:31:03.510Z SendDataConnector.js: Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:31:03.511Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:31:03.511Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: HTC Desire 820 B4:CE:F6:AB:A4:6A
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: B4:CE:F6:AB:A4:6A)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address B4:CE:F6:AB:A4:6A (thread ID: 360)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:73, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 73
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
,W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3256): Ignored { when=-11ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): Connection timeout
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2098): info:x10
D/        ( 2098): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: HTC Desire 820
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT3538 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 360)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 360)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Cancelled: Connection timeout [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT3538 B4:CE:F6:AB:A4:6A]
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,I/jxcore-log( 3256): 2015-12-15T03:31:35.591Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:31:35.591Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:31:35.592Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 11 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 5: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 9: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 10: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 11: S5mini-1 02:f4:6f:30:e0:6d
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3256): 2015-12-15T03:31:40.594Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:31:40.595Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3256): 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID B4:CE:F6:AB:A4:6A
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: B4:CE:F6:AB:A4:6A), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:31:45.601Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:31:45.601Z SendDataConnector.js: Connect (retry count 2) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:31:45.602Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:31:45.602Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: HTC Desire 820 B4:CE:F6:AB:A4:6A
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: B4:CE:F6:AB:A4:6A)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address B4:CE:F6:AB:A4:6A (thread ID: 361)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:75, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 75
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 76
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 361)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 361)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): Connection timeout
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:77, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 77
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:78, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2098): invalid rfc slot id: 78
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 361)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 361)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Cancelled: Connection timeout [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT3538 B4:CE:F6:AB:A4:6A]
,I/jxcore-log( 3256): 2015-12-15T03:32:06.521Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:32:06.522Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:32:06.524Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 361)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,I/jxcore-log( 3256): 2015-12-15T03:32:11.525Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:32:11.526Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3256): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,D/WifiP2pManager( 3256): Ignored { when=-8ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID B4:CE:F6:AB:A4:6A
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: B4:CE:F6:AB:A4:6A), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:32:16.531Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:32:16.531Z SendDataConnector.js: Connect (retry count 3) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:32:16.532Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:32:16.532Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: HTC Desire 820 B4:CE:F6:AB:A4:6A
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: B4:CE:F6:AB:A4:6A)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address B4:CE:F6:AB:A4:6A (thread ID: 362)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT3538 B4:CE:F6:AB:A4:6A]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 362)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 363)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 363)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 362)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 363)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 84 bytes successfully (thread ID: 363)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT3538 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT3538 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 363)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT3538 B4:CE:F6:AB:A4:6A]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: B4:CE:F6:AB:A4:6A, name: HTC-HTC Desire 820_PT3538, Bluetooth address: B4:CE:F6:AB:A4:6A
,D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
,I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID B4:CE:F6:AB:A4:6A, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 364)
,D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 47708
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 47708 (peer ID: B4:CE:F6:AB:A4:6A)
I/jxcore-log( 3256): 2015-12-15T03:32:18.515Z SendDataConnector.js: CLIENT connected to 47708, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:32:18.515Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 47708
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 364)
,I/jxcore-log( 3256): 2015-12-15T03:32:18.543Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 366, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 365, name: Sender)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT3461"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [38:94:96:B5:06:DC samsung-SM-G800H_PT3461 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT3461"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT8182","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8182 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT8182","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 38:94:96:B5:06:DC, peer name: samsung-SM-G800H_PT3461, peer ID: 38:94:96:B5:06:DC, Wi-Fi Direct device name: , Wi-Fi Direct address: 3a:94:96:b5:06:dd
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Adding peer with ID 38:94:96:B5:06:DC
I/jxcore-log( 3256): peerAvailabilityChanged [{"peerIdentifier":"38:94:96:B5:06:DC","peerName":"samsung-SM-G800H_PT3461","peerAvailable":true}]
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Found peer : samsung-SM-G800H_PT3461, Available: true
I/jxcore-log( 3256): 
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT8182, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: , Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Adding peer with ID 08:EC:A9:50:76:27
I/jxcore-log( 3256): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT8182","peerAvailable":true}]
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Found peer : samsung-SM-A300FU_PT8182, Available: true
I/jxcore-log( 3256): 
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7596"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7596"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT7596, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: XT1039_8c05, Wi-Fi Direct address: f4:f1:e1:5c:43:c8
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Adding peer with ID F4:F1:E1:5C:3B:E2
I/jxcore-log( 3256): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"motorola-XT1039_PT7596","peerAvailable":true}]
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Found peer : motorola-XT1039_PT7596, Available: true
I/jxcore-log( 3256): 
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/jxcore-log( 3256): 2015-12-15T03:32:19.511Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:32:19.641Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:32:19.844Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:32:20.154Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:32:20.339Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:32:20.424Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:32:20.459Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3256): 
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3256): 2015-12-15T03:32:20.719Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:32:20.821Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:32:20.823Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3256): 
I/jxcore-log( 3256): oneRoundDownNow
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:32:20.825Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:32:20.825Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: B4:CE:F6:AB:A4:6A
I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 366
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 365
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 365, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID B4:CE:F6:AB:A4:6A disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 366, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID B4:CE:F6:AB:A4:6A disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Successfully disconnected (peer ID: B4:CE:F6:AB:A4:6A
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 365, name: Sender)
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 366, name: Receiver)
,I/jxcore-log( 3256): 2015-12-15T03:32:20.866Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): ---- round done--------
I/jxcore-log( 3256): 
I/jxcore-log( 3256): startWithNextDevice
I/jxcore-log( 3256): 
I/jxcore-log( 3256): device[7]: B0:C5:59:3F:75:69
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:32:20.868Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:32:20.868Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:32:20.868Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null B0:C5:59:3F:75:69
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 367)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
E/BluetoothRemoteDevices( 2098): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 2098): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2098): Entering PendingCommandState State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2098): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2098): StableState(): Entering Off State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9469 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 367)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 368)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 368)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 367)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 368)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 82 bytes successfully (thread ID: 368)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9469 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9469 B0:C5:59:3F:75:69]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9469 B0:C5:59:3F:75:69],
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: B0:C5:59:3F:75:69, name: samsung-SM-G900F_PT9469, Bluetooth address: B0:C5:59:3F:75:69
,D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID B0:C5:59:3F:75:69 already in the list
,I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID B0:C5:59:3F:75:69, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 368)
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 369)
,D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 34795
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 34795 (peer ID: B0:C5:59:3F:75:69)
I/jxcore-log( 3256): 2015-12-15T03:32:23.836Z SendDataConnector.js: CLIENT connected to 34795, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:32:23.836Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 34795
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 369)
,I/jxcore-log( 3256): 2015-12-15T03:32:23.862Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 371, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 370, name: Sender)
,I/jxcore-log( 3256): 2015-12-15T03:32:24.425Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:32:24.618Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:32:24.703Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:32:25.000Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:32:25.161Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:32:25.509Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:32:26.224Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:32:27.071Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3256): 
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3256): 2015-12-15T03:32:27.698Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3256): 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3256): 2015-12-15T03:32:28.826Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:32:28.827Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3256): 
I/jxcore-log( 3256): oneRoundDownNow
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:32:28.836Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:32:28.836Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: B0:C5:59:3F:75:69
I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 371
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 370
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 370, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID B0:C5:59:3F:75:69 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 371, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID B0:C5:59:3F:75:69 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Successfully disconnected (peer ID: B0:C5:59:3F:75:69
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 370, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 371, name: Receiver)
,I/jxcore-log( 3256): 2015-12-15T03:32:28.884Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3256): 
I/jxcore-log( 3256): ---- round done--------
I/jxcore-log( 3256): 
I/jxcore-log( 3256): startWithNextDevice
I/jxcore-log( 3256): 
I/jxcore-log( 3256): device[8]: 38:94:96:B5:06:DC
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:32:28.884Z SendDataConnector.js: Start called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:32:28.884Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:32:28.884Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null 38:94:96:B5:06:DC
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address 38:94:96:B5:06:DC
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 38:94:96:B5:06:DC)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 38:94:96:B5:06:DC (thread ID: 372)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9469","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9469 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9469","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: B0:C5:59:3F:75:69, peer name: samsung-SM-G900F_PT9469, peer ID: B0:C5:59:3F:75:69, Wi-Fi Direct device name: Thali Test (Galaxy S5), Wi-Fi Direct address: ee:1f:72:18:8b:78
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID B0:C5:59:3F:75:69 already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:81, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 81
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2082","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT2082 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2082","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT2082, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: , Wi-Fi Direct address: fa:cf:c5:d9:e5:62
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Adding peer with ID F8:CF:C5:D9:E5:61
,I/jxcore-log( 3256): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"motorola-Nexus 6_PT2082","peerAvailable":true}]
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): Found peer : motorola-Nexus 6_PT2082, Available: true
I/jxcore-log( 3256): 
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT2862","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT2862 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT2862","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 90:E7:C4:F6:69:77, peer name: HTC-HTC One M8s_PT2862, peer ID: 90:E7:C4:F6:69:77, Wi-Fi Direct device name: , Wi-Fi Direct address: 92:e7:c4:e6:4c:f8
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 90:E7:C4:F6:69:77 already in the list
,W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 6 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4642","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4642 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 7 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4642","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT4642, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: , Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Adding peer with ID F8:95:C7:87:3C:51
,I/jxcore-log( 3256): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT4642","peerAvailable":true}]
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Found peer : LGE-LG-H815_PT4642, Available: true
I/jxcore-log( 3256): 
,W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 7 peer(s), but doing nothing with that list
,W/bt-btm  ( 2098): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=2
E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: HTC Desire 820
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT37","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT37 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 8 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT37","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT37, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:9a:02:7b:60:ac
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 58:3F:54:73:64:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): Connection timeout
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0xd  CID 0x4f
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:82, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 82
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onConnectionFailed: Cancelled: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT3417"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 9 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT3417"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT8130"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT8130 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 10 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT8130"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3356","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT3356 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 11 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3356","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A",,"pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3538"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT3538 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 372)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 12 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3538"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Cancelled: Connection timeout [38:94:96:B5:06:DC samsung-SM-G800H_PT3461 38:94:96:B5:06:DC]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT3417, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 12 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT8130, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: Thali Test's G2, Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Adding peer with ID 34:FC:EF:9D:93:0B
I/jxcore-log( 3256): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"LGE-LG-D802_PT8130","peerAvailable":true}]
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Found peer : LGE-LG-D802_PT8130, Available: true
I/jxcore-log( 3256): 
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 12 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT3356, peer ID: 44:80:EB:7B:5A:05, Wi-Fi Direct device name: , Wi-Fi Direct address: 44:80:eb:7b:5a:07
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Adding peer with ID 44:80:EB:7B:5A:05
I/jxcore-log( 3256): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"motorola-XT1072_PT3356","peerAvailable":true}]
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Found peer : motorola-XT1072_PT3356, Available: true
I/jxcore-log( 3256): 
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 12 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT3538, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: Android_1950, Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 12 peer(s), but doing nothing with that list
,I/jxcore-log( 3256): 2015-12-15T03:32:46.337Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:32:46.349Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:32:46.352Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4840","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4840 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 13 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4840","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT4840, peer ID: 7C:F9:0E:51:18:22, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:51:18:23
,I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:51:18:22
,I/jxcore-log( 3256): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT4840","peerAvailable":true}]
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Found peer : samsung-SM-A500FU_PT4840, Available: true
I/jxcore-log( 3256): 
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 13 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9389","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9389 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 14 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9389","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT9389, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: , Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Adding peer with ID 08:EC:A9:50:75:41
I/jxcore-log( 3256): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT9389","peerAvailable":true}]
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Found peer : samsung-SM-A300FU_PT9389, Available: true
I/jxcore-log( 3256): 
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 14 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3256): 2015-12-15T03:32:51.361Z SendDataConnector.js: re-try now : 38:94:96:B5:06:DC
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:32:51.363Z SendDataConnector.js: ReStart called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3256): 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 38:94:96:B5:06:DC
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: 38:94:96:B5:06:DC), either no such connection or failed to close the connection
,I/jxcore-log( 3256): 2015-12-15T03:32:56.374Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:32:56.375Z SendDataConnector.js: Connect (retry count 1) to peer 38:94:96:B5:06:DC with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:32:56.375Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:32:56.376Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
,I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null 38:94:96:B5:06:DC
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address 38:94:96:B5:06:DC
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 38:94:96:B5:06:DC)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 38:94:96:B5:06:DC (thread ID: 373)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:83, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 83
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): Connection timeout
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0xd  CID 0x40
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:84, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 84
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 373)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 373)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): cancel: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Cancelled: Connection timeout [38:94:96:B5:06:DC samsung-SM-G800H_PT3461 38:94:96:B5:06:DC]
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,I/jxcore-log( 3256): 2015-12-15T03:33:14.796Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:33:14.796Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:33:14.796Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 373)
,I/jxcore-log( 3256): 2015-12-15T03:33:19.797Z SendDataConnector.js: re-try now : 38:94:96:B5:06:DC
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:33:19.799Z SendDataConnector.js: ReStart called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Android_1950 b6:ce:f6:ad:a4:6b
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 38:94:96:B5:06:DC
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: 38:94:96:B5:06:DC), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:33:24.804Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:33:24.804Z SendDataConnector.js: Connect (retry count 2) to peer 38:94:96:B5:06:DC with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:33:24.805Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:33:24.805Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null 38:94:96:B5:06:DC
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address 38:94:96:B5:06:DC
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 38:94:96:B5:06:DC)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 38:94:96:B5:06:DC (thread ID: 374)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:85, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 85
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [38:94:96:b5:06:dc]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2098): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4642","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4642 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4642","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4642","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT4642, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: , Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 38:94:96:B5:06:DC newState: 1
E/bt-btif ( 2098): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:38:94:96:B5:06:DC OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2098): Entering PendingCommandState State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 38:94:96:B5:06:DC not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for 38:94:96:B5:06:DC, but we have no record of that device.
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 38:94:96:B5:06:DC newState: 0
,D/BluetoothAdapterProperties( 2098): Failed to remove device: 38:94:96:B5:06:DC
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:38:94:96:B5:06:DC OldState: 11 NewState: 10
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 38:94:96:B5:06:DC not found, calling readPairedDevices().
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): Connection timeout
,I/BluetoothBondStateMachine( 2098): StableState(): Entering Off State
,E/BluetoothEventManager( 2686): Got bonding state changed for 38:94:96:B5:06:DC, but we have no record of that device.
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [38:94:96:B5:06:DC samsung-SM-G800H_PT3461 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onConnectionFailed: Cancelled: Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Cancelled: Connection timeout [38:94:96:B5:06:DC samsung-SM-G800H_PT3461 38:94:96:B5:06:DC]
I/jxcore-log( 3256): 2015-12-15T03:33:43.889Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:33:43.890Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:33:43.891Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 374)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 374)
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/jxcore-log( 3256): 2015-12-15T03:33:48.908Z SendDataConnector.js: re-try now : 38:94:96:B5:06:DC
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:33:48.909Z SendDataConnector.js: ReStart called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3256): 
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=38:94:96:B5:06:DC, alias=null, name=Galaxy S5-2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Galaxy S5-2
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 38:94:96:B5:06:DC
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: 38:94:96:B5:06:DC), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:33:53.913Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:33:53.914Z SendDataConnector.js: Connect (retry count 3) to peer 38:94:96:B5:06:DC with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:33:53.915Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:33:53.915Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: Galaxy S5-2 38:94:96:B5:06:DC
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 38:94:96:B5:06:DC)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 38:94:96:B5:06:DC (thread ID: 375)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [38:94:96:b5:06:dc]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=38:94:96:B5:06:DC, alias=null, name=Galaxy S5-2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Galaxy S5-2
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [38:94:96:B5:06:DC samsung-SM-G800H_PT3461 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 375)
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 376)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 376)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 375)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 376)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT37","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT37 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT37","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT37","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT37, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:9a:02:7b:60:ac
,I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 58:3F:54:73:64:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 82 bytes successfully (thread ID: 376)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [38:94:96:B5:06:DC samsung-SM-G800H_PT3461 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [38:94:96:B5:06:DC samsung-SM-G800H_PT3461 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 376)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [38:94:96:B5:06:DC samsung-SM-G800H_PT3461 38:94:96:B5:06:DC]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: 38:94:96:B5:06:DC, name: samsung-SM-G800H_PT3461, Bluetooth address: 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 38:94:96:B5:06:DC already in the list
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID 38:94:96:B5:06:DC, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 377)
D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 59086
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 59086 (peer ID: 38:94:96:B5:06:DC)
I/jxcore-log( 3256): 2015-12-15T03:33:59.393Z SendDataConnector.js: CLIENT connected to 59086, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:33:59.394Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 59086
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 377)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 379, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 378, name: Sender)
,I/jxcore-log( 3256): 2015-12-15T03:33:59.445Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11836
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2098): dm_pm_timer expires
W/bt-btif ( 2098): dm_pm_timer expires 0
W/bt-btif ( 2098): proc dm_pm_timer expires
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3256): 2015-12-15T03:34:09.816Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:34:09.816Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:34:09.822Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:34:09.824Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:34:09.825Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3256): 
,E/io.jxcore.node.StreamCopyingThread( 3256): Input stream got -1 on read (thread ID: 378, thread name: Sender)
E/io.jxcore.node.OutgoingSocketThread( 3256): The sending thread failed with error: Input stream got -1 on read
,W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 38:94:96:B5:06:DC disconnected: Input stream got -1 on read
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 38:94:96:B5:06:DC
I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 379
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 378
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 379, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 38:94:96:B5:06:DC disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 378, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 379, name: Receiver)
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3256): 2015-12-15T03:34:14.826Z SendDataConnector.js: re-try now : 38:94:96:B5:06:DC
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:34:14.827Z SendDataConnector.js: ReStart called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3256): 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 38:94:96:B5:06:DC
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: 38:94:96:B5:06:DC), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:34:19.835Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:34:19.835Z SendDataConnector.js: Connect (retry count 4) to peer 38:94:96:B5:06:DC with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:34:19.836Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:34:19.836Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
,I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 38:94:96:B5:06:DC
,D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: Galaxy S5-2 38:94:96:B5:06:DC
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 38:94:96:B5:06:DC)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 38:94:96:B5:06:DC (thread ID: 380)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): Connection timeout
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:88, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2098): invalid rfc slot id: 88
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapService( 2098): onReceive
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=38:94:96:B5:06:DC, alias=null, name=Galaxy S5-2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Galaxy S5-2
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [38:94:96:b5:06:dc]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=38:94:96:B5:06:DC, alias=null, name=Galaxy S5-2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Galaxy S5-2
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [38:94:96:B5:06:DC samsung-SM-G800H_PT3461 38:94:96:B5:06:DC]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Cancelled: Connection timeout [38:94:96:B5:06:DC samsung-SM-G800H_PT3461 38:94:96:B5:06:DC]
I/jxcore-log( 3256): 2015-12-15T03:34:42.837Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:34:42.837Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): oneRoundDownNow
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 380)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 380)
,I/jxcore-log( 3256): 2015-12-15T03:34:42.851Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:34:42.852Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3256): 
D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 38:94:96:B5:06:DC
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: 38:94:96:B5:06:DC), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:34:42.855Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 3256): 
I/jxcore-log( 3256): ---- round done--------
I/jxcore-log( 3256): 
I/jxcore-log( 3256): startWithNextDevice
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): device[9]: 08:EC:A9:50:76:27
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:34:42.868Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:34:42.869Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:34:42.869Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 381)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=0
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=38:94:96:B5:06:DC, alias=null, name=Galaxy S5-2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Galaxy S5-2
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2098): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 2098): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2098): Entering PendingCommandState State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 2098): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2098): StableState(): Entering Off State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8182 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 381)
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 382)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 382)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 381)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 382)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 83 bytes successfully (thread ID: 382)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8182 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8182 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 382)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8182 08:EC:A9:50:76:27]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT8182, Bluetooth address: 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID 08:EC:A9:50:76:27, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 383)
D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 48326
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 48326 (peer ID: 08:EC:A9:50:76:27)
I/jxcore-log( 3256): 2015-12-15T03:34:55.676Z SendDataConnector.js: CLIENT connected to 48326, error: null
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:34:55.677Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 48326
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 383)
,I/jxcore-log( 3256): 2015-12-15T03:34:55.702Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 384, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 385, name: Receiver)
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 3256): 2015-12-15T03:34:56.305Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:34:56.722Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3256): 
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 3256): 2015-12-15T03:34:56.924Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:34:57.052Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3256): 
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3256): 2015-12-15T03:34:57.246Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:34:57.469Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:34:57.588Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:34:57.875Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:34:58.091Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3256): 
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/bt-btif ( 2098): dm_pm_timer expires
W/bt-btif ( 2098): dm_pm_timer expires 0
W/bt-btif ( 2098): proc dm_pm_timer expires
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/jxcore-log( 3256): 2015-12-15T03:35:08.091Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:08.092Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:08.093Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:08.093Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:08.094Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3256): 
,E/io.jxcore.node.StreamCopyingThread( 3256): Input stream got -1 on read (thread ID: 384, thread name: Sender)
E/io.jxcore.node.OutgoingSocketThread( 3256): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:76:27 disconnected: Input stream got -1 on read
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:76:27
,I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 385,
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 384
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 385, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:76:27 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 385, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 384, name: Sender)
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT8182","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8182 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT8182","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT8182","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT8182, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: , Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2082","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT2082 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2082","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2082","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT2082, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: Android_50a5, Wi-Fi Direct address: fa:cf:c5:d9:e5:62
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 3256): 2015-12-15T03:35:13.094Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:13.095Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3256): 
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:35:18.099Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:18.100Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:18.101Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:18.101Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: Thali Test (Galaxy A3) 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 386)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:91, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 91
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8182 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 386)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 387)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 387)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 386)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 387)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 83 bytes successfully (thread ID: 387)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8182 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8182 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 387)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8182 08:EC:A9:50:76:27]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT8182, Bluetooth address: 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID 08:EC:A9:50:76:27, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 388)
D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 56272
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 56272 (peer ID: 08:EC:A9:50:76:27)
I/jxcore-log( 3256): 2015-12-15T03:35:25.990Z SendDataConnector.js: CLIENT connected to 56272, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:25.993Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:35:25.995Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 56272
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 388)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 389, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 390, name: Receiver)
,I/jxcore-log( 3256): 2015-12-15T03:35:26.108Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:26.108Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3256): 
I/jxcore-log( 3256): oneRoundDownNow
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:26.108Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:26.108Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 390
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 389
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 389, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:76:27 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 390, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:76:27 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:76:27
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 389, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 390, name: Receiver)
,I/jxcore-log( 3256): 2015-12-15T03:35:26.114Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3256): 
I/jxcore-log( 3256): ---- round done--------
I/jxcore-log( 3256): 
I/jxcore-log( 3256): startWithNextDevice
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): device[10]: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:26.115Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:26.115Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:26.115Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: XT1039_8c05
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 391)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2098): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 2098): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2098): Entering PendingCommandState State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 2098): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2098): StableState(): Entering Off State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 391)
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 392)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 392)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 391)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 392)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 81 bytes successfully (thread ID: 392)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT7596, Bluetooth address: F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID F4:F1:E1:5C:3B:E2, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 392)
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 393)
D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 38469
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,W/bt-btif ( 2098): invalid rfc slot id: 93
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 38469 (peer ID: F4:F1:E1:5C:3B:E2)
,I/jxcore-log( 3256): 2015-12-15T03:35:27.537Z SendDataConnector.js: CLIENT connected to 38469, error: null
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:35:27.542Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 38469
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 393)
,I/jxcore-log( 3256): 2015-12-15T03:35:27.563Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 395, name: Receiver)
W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 395, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3256): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F4:F1:E1:5C:3B:E2
I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 395
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 394
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 394, name: Sender)
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 394, name: Sender)
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 395, name: Receiver)
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: XT1039
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3256): 2015-12-15T03:35:37.954Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:37.955Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:37.956Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:37.956Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:35:37.961Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:35:42.959Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:42.959Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:42.960Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:35:47.963Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:47.964Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:47.965Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:47.965Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: XT1039_8c05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 396)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [f4:f1:e1:5c:3b:e2]: 7, 1d, 7d3,
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 396)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 397)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 397)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 396)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 397)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 81 bytes successfully (thread ID: 397)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT7596, Bluetooth address: F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID F4:F1:E1:5C:3B:E2, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 397)
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 398)
D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 57741
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,W/bt-btif ( 2098): invalid rfc slot id: 94
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 57741 (peer ID: F4:F1:E1:5C:3B:E2)
I/jxcore-log( 3256): 2015-12-15T03:35:48.940Z SendDataConnector.js: CLIENT connected to 57741, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:48.940Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:35:48.947Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 57741
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 398)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 400, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 399, name: Sender)
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 400, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3256): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F4:F1:E1:5C:3B:E2
,I/io.jxcore.node.OutgoingSocketThread( 3256): close
,I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 400
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 399
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 399, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 400, name: Receiver)
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 399, name: Sender)
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: XT1039
,I/jxcore-log( 3256): 2015-12-15T03:35:59.371Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:59.372Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:59.373Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:59.373Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:35:59.374Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:36:04.374Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:04.374Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:04.375Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:36:09.381Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:09.382Z SendDataConnector.js: Connect (retry count 2) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:09.382Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:09.383Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: XT1039_8c05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 401)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 401)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 402)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 402)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 401)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 402)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 81 bytes successfully (thread ID: 402)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 402)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT7596, Bluetooth address: F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID F4:F1:E1:5C:3B:E2, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 403)
D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 59103
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,W/bt-btif ( 2098): invalid rfc slot id: 95
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 59103 (peer ID: F4:F1:E1:5C:3B:E2)
,I/jxcore-log( 3256): 2015-12-15T03:36:10.707Z SendDataConnector.js: CLIENT connected to 59103, error: null
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:36:10.711Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 59103
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 403)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 405, name: Receiver)
W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 405, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3256): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 404, name: Sender)
,I/jxcore-log( 3256): 2015-12-15T03:36:10.765Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F4:F1:E1:5C:3B:E2
I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 405
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 404
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 405, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 404, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 404, name: Sender)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: XT1039_8c05 f4:f1:e1:5c:43:c8
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): startServiceDiscovery: Invalid state, try calling restart()
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: XT1039
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: XT1039_8c05 f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3256): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT8182","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8182 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT8182","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT8182","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT8182","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT8182","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT8182, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: , Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2756","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT2756 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2756","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2756","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2756","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2756","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT2756, peer ID: E0:DB:10:1F:C9:5E, Wi-Fi Direct device name: , Wi-Fi Direct address: ea:50:8b:de:28:a3
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Adding peer with ID E0:DB:10:1F:C9:5E
I/jxcore-log( 3256): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"samsung-SM-N9005_PT2756","peerAvailable":true}]
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): Found peer : samsung-SM-N9005_PT2756, Available: true
I/jxcore-log( 3256): 
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/jxcore-log( 3256): 2015-12-15T03:36:21.154Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:21.155Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:21.155Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:21.156Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:36:21.157Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:36:26.157Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:26.159Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:26.160Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:36:31.164Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:31.165Z SendDataConnector.js: Connect (retry count 3) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:31.165Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:31.166Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: XT1039_8c05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 406)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 406)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 407)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 407)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 406)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 407)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 81 bytes successfully (thread ID: 407)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT7596, Bluetooth address: F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID F4:F1:E1:5C:3B:E2, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 407)
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 408)
D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 37484
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,W/bt-btif ( 2098): invalid rfc slot id: 96
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 37484 (peer ID: F4:F1:E1:5C:3B:E2)
I/jxcore-log( 3256): 2015-12-15T03:36:32.473Z SendDataConnector.js: CLIENT connected to 37484, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:32.474Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 37484
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 408)
,I/jxcore-log( 3256): 2015-12-15T03:36:32.494Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 410, name: Receiver)
W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 410, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3256): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F4:F1:E1:5C:3B:E2
I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 410
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 409
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 409, name: Sender)
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 409, name: Sender)
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 410, name: Receiver)
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: XT1039
,I/art     (  758): Explicit concurrent mark sweep GC freed 89247(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 1.206ms total 72.822ms
,I/jxcore-log( 3256): 2015-12-15T03:36:42.900Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:42.900Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:42.901Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:42.902Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:42.903Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:36:47.903Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:36:47.903Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:47.904Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:36:52.910Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:52.911Z SendDataConnector.js: Connect (retry count 4) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:52.911Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:36:52.912Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: XT1039_8c05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 411)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: XT1039
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e51ec4 rs_disc_pending=0
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): Connection timeout
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:97, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2098): invalid rfc slot id: 97
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapService( 2098): onReceive
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: XT1039
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): cancel: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0x7):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 411)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 411)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Cancelled: Connection timeout [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local services cleared successfully
I/jxcore-log( 3256): 2015-12-15T03:37:18.189Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:37:18.189Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:37:18.189Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): oneRoundDownNow
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:37:18.190Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:37:18.190Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:37:18.190Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:37:18.191Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3256): 
I/jxcore-log( 3256): ---- round done--------
I/jxcore-log( 3256): 
I/jxcore-log( 3256): startWithNextDevice
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): device[11]: F8:CF:C5:D9:E5:61
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:37:18.195Z SendDataConnector.js: Start called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:37:18.196Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:37:18.196Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null F8:CF:C5:D9:E5:61
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: F8:CF:C5:D9:E5:61)
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address F8:CF:C5:D9:E5:61 (thread ID: 412)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 2098): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: XT1039
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3256): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 7 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 5: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 6: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 7 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 5: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 6: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 7 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 5: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 6: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3256): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully,
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT301","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT301 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT301","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT301","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT301","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT301","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT301","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT301","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: samsung-SM-A500FU_PT301, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:37:96:ac
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT3417"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT3417"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT3417"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT3417"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT3417"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT3417"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT3417"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT3417, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7596"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7596"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7596"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7596"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7596"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7596"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7596"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT7596, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: XT1039_8c05, Wi-Fi Direct address: f4:f1:e1:5c:43:c8
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): Connection timeout
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x4e
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:99, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 99
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e5208c rs_disc_pending=1
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:100, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 100
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 2098): aclStateChangeCallback: Device is NULL
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 412)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 412)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Cancelled: Connection timeout [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT2082 F8:CF:C5:D9:E5:61]
,W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,I/jxcore-log( 3256): 2015-12-15T03:38:41.800Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:38:41.801Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:38:41.801Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:38:41.801Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 412)
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): startServiceDiscovery: Invalid state, try calling restart()
,I/jxcore-log( 3256): 2015-12-15T03:38:46.802Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:38:46.803Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:38:46.803Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: XT1039_8c05 f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3256): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:CF:C5:D9:E5:61
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:CF:C5:D9:E5:61), either no such connection or failed to close the connection
,I/jxcore-log( 3256): 2015-12-15T03:38:51.811Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:38:51.812Z SendDataConnector.js: Connect (retry count 1) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:38:51.812Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:38:51.813Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null F8:CF:C5:D9:E5:61
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: F8:CF:C5:D9:E5:61)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address F8:CF:C5:D9:E5:61 (thread ID: 413)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:101, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 101
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [f8:cf:c5:d9:e5:61]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 2098): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
E/bt-btif ( 2098): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2098): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 2098): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2098): StableState(): Entering Off State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT2082 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 413)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 414)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 414)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 413)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 414)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 82 bytes successfully (thread ID: 414)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT2082 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT2082 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 414)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT2082 F8:CF:C5:D9:E5:61]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: F8:CF:C5:D9:E5:61, name: motorola-Nexus 6_PT2082, Bluetooth address: F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
,I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID F8:CF:C5:D9:E5:61, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 415)
D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 40456
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 40456 (peer ID: F8:CF:C5:D9:E5:61)
I/jxcore-log( 3256): 2015-12-15T03:38:58.027Z SendDataConnector.js: CLIENT connected to 40456, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:38:58.027Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 40456
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 415)
I/jxcore-log( 3256): 2015-12-15T03:38:58.030Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 416, name: Sender)
I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 417, name: Receiver)
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 3256): 2015-12-15T03:38:58.478Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3256): 
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19756
,I/jxcore-log( 3256): 2015-12-15T03:38:58.546Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:38:58.592Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3256): 
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 3256): 2015-12-15T03:38:58.725Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:38:58.866Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:38:59.027Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:38:59.082Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:38:59.094Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:38:59.133Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:38:59.180Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:38:59.181Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3256): 
I/jxcore-log( 3256): oneRoundDownNow
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:38:59.186Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:38:59.186Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:CF:C5:D9:E5:61
I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 417
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 416
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 416, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID F8:CF:C5:D9:E5:61 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 417, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID F8:CF:C5:D9:E5:61 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:CF:C5:D9:E5:61
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 416, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 417, name: Receiver)
,I/jxcore-log( 3256): 2015-12-15T03:38:59.236Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): ---- round done--------
I/jxcore-log( 3256): 
I/jxcore-log( 3256): startWithNextDevice
I/jxcore-log( 3256): 
I/jxcore-log( 3256): device[12]: F8:95:C7:87:3C:51
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:38:59.244Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:38:59.244Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:38:59.245Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 418)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e5208c rs_disc_pending=0
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2098): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e5208c rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e5208c rs_disc_pending=0
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Nexus 6
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [00:f4:6f:30:e0:6c]: 7, f, 230f
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: S5mini-1
,W/bt-l2cap( 2098): L2CAP - con rsp - bad ID. Exp: 5 Got: 3
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:255
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Incoming connection initialized (thread ID: 419)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 419)
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 2098): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2098): Entering PendingCommandState State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): onBytesRead: Read 82 bytes successfully (thread ID: 419)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Got valid identity from [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 419)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): removeThreadFromList: Removing thread with ID 419
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Handshake thread disposed (thread ID: 419)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onIncomingConnectionConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 419)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
,I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Incoming connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT3417, Bluetooth address: 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
,I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Incoming socket thread, for peer with ID 00:F4:6F:30:E0:6C, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3256): Entering thread (ID: 420)
,I/jxcore-log( 3256): 2015-12-15T03:39:06.413Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3256): 
,I/io.jxcore.node.IncomingSocketThread( 3256): Local host address: localhost/127.0.0.1, port: 36677
D/io.jxcore.node.IncomingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3256): Exiting thread (ID: 420)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 422, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 421, name: Sender)
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2098): Failed to remove device: F8:95:C7:87:3C:51
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2098): StableState(): Entering Off State
,E/BluetoothEventManager( 2686): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/jxcore-log( 3256): 2015-12-15T03:39:07.442Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:07.542Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:07.783Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:07.877Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:07.880Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:07.989Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3256): 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3256): 2015-12-15T03:39:08.019Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:08.076Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:08.165Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:08.510Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:08.715Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:08.992Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3256): 
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3256): 2015-12-15T03:39:09.272Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3256): 
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e52254 rs_disc_pending=0
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3256): 2015-12-15T03:39:09.432Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:09.525Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:09.564Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:09.583Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:09.842Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:10.095Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:10.361Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:10.422Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3256): 
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4642 F8:95:C7:87:3C:51]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 418)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 423)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 423)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 418)
,I/jxcore-log( 3256): 2015-12-15T03:39:10.776Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 423)
,I/jxcore-log( 3256): 2015-12-15T03:39:10.909Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3256): 
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3256): 2015-12-15T03:39:12.245Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:12.271Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3256): 
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e52254 rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3256): 2015-12-15T03:39:12.740Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3256): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 77 bytes successfully (thread ID: 423)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [F8:95:C7:87:3C:51 LGE-LG-H815_PT4642 F8:95:C7:87:3C:51]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4642 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 423)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4642 F8:95:C7:87:3C:51]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: F8:95:C7:87:3C:51, name: LGE-LG-H815_PT4642, Bluetooth address: F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID F8:95:C7:87:3C:51, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 2
,I/jxcore-log( 3256): 2015-12-15T03:39:13.233Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3256): 
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 424)
D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 55099
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 55099 (peer ID: F8:95:C7:87:3C:51)
,I/jxcore-log( 3256): 2015-12-15T03:39:13.550Z SendDataConnector.js: CLIENT connected to 55099, error: null
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:13.551Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 55099
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 424)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 426, name: Receiver)
,I/jxcore-log( 3256): 2015-12-15T03:39:13.577Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:39:13.593Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 425, name: Sender)
,I/jxcore-log( 3256): 2015-12-15T03:39:13.979Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:14.078Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:14.206Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:14.239Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:14.947Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:15.150Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:15.356Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:15.651Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:15.689Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:15.853Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:16.127Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:16.160Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:16.169Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:16.467Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:16.499Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:16.583Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:16.612Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:16.932Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:17.086Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:17.251Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:17.430Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3256): 
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2098): invalid rfc slot id: 64
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 422, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3256): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Incoming connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 420
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...,
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 422
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 421
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 421, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Incoming connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 421, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 422, name: Receiver)
,I/jxcore-log( 3256): 2015-12-15T03:39:18.003Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3256): 
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2098): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
W/bt-rfcomm( 2098): RFCOMM_DisconnectInd LCID:0x43
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 3256): 2015-12-15T03:39:23.974Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:39:23.975Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:39:23.976Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:39:23.976Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:39:23.985Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3256): 
,E/io.jxcore.node.StreamCopyingThread( 3256): Input stream got -1 on read (thread ID: 425, thread name: Sender)
E/io.jxcore.node.OutgoingSocketThread( 3256): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID F8:95:C7:87:3C:51 disconnected: Input stream got -1 on read
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 426
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 425
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 426, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID F8:95:C7:87:3C:51 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 425, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 426, name: Receiver)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: G4-1
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3256): Ignored { when=-13ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=-5ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: XT1039_8c05 f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3256): 2015-12-15T03:39:28.977Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:39:28.979Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:3C:51), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:39:33.983Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:39:33.984Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:39:33.984Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:39:33.985Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: G4-1 F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 427)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): No ag scb for peer addr
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): Connection timeout
,E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:105, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 105
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/UsageStatsService(  758): User[0] Flushing usage stats to disk
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [f8:95:c7:87:3c:51]: 6, f, 410d
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: G4-1
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 2098): PORT_StartCnf failed result:5
E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 2098): Do not find the bg connection mask for the remote device
,E/bt-btif ( 2098): check_cod: remote_cod = 0x5a020c
,W/bt-btif ( 2098): invalid rfc slot id: 106
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 9 Address: F8:95:C7:87:3C:51 newState: 0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 427)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 427)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onConnectionFailed: Cancelled: Connection timeout
,E/BluetoothBondStateMachine( 2098): In stable state, received invalid newState: 10
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Cancelled: Connection timeout [F8:95:C7:87:3C:51 LGE-LG-H815_PT4642 F8:95:C7:87:3C:51]
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,I/jxcore-log( 3256): 2015-12-15T03:40:49.932Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F8:95:C7:87:3C:51 failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:40:49.932Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F8:95:C7:87:3C:51 failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:40:49.932Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/BluetoothMapService( 2098): onReceive
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: G4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 427)
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): startServiceDiscovery: Invalid state, try calling restart()
,I/jxcore-log( 3256): 2015-12-15T03:40:54.933Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:40:54.934Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Cannot start, because not initialized
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3256): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:3C:51), either no such connection or failed to close the connection
,I/jxcore-log( 3256): 2015-12-15T03:40:59.944Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:40:59.945Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:40:59.945Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:40:59.946Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
,I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: G4-1 F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 428)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4840","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4840 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4840","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4840","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT4840, peer ID: 7C:F9:0E:51:18:22, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:51:18:23
,I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
,W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: G4-1
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2098): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2098): Entering PendingCommandState State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2098): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2098): StableState(): Entering Off State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4642 F8:95:C7:87:3C:51]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 428)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 429)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 429)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 428)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 429)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 77 bytes successfully (thread ID: 429)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [F8:95:C7:87:3C:51 LGE-LG-H815_PT4642 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4642 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 429)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4642 F8:95:C7:87:3C:51]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: F8:95:C7:87:3C:51, name: LGE-LG-H815_PT4642, Bluetooth address: F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID F8:95:C7:87:3C:51, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 430)
,D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 43078
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 43078 (peer ID: F8:95:C7:87:3C:51)
I/jxcore-log( 3256): 2015-12-15T03:41:04.814Z SendDataConnector.js: CLIENT connected to 43078, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:41:04.815Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 43078
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 430)
,I/jxcore-log( 3256): 2015-12-15T03:41:04.845Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 431, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 432, name: Receiver)
,I/jxcore-log( 3256): 2015-12-15T03:41:05.662Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:41:05.819Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:41:06.463Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3256): 
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3256): 2015-12-15T03:41:06.757Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:41:07.721Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7596"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7596"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7596"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT7596, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: XT1039_8c05, Wi-Fi Direct address: f4:f1:e1:5c:43:c8
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3256): 2015-12-15T03:41:09.963Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:41:10.102Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:41:10.692Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:41:10.944Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:41:11.342Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:41:11.343Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3256): 
I/jxcore-log( 3256): oneRoundDownNow
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:41:11.344Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:41:11.345Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 432
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 431
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 431, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID F8:95:C7:87:3C:51 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 432, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID F8:95:C7:87:3C:51 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:3C:51
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 431, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 432, name: Receiver)
,I/jxcore-log( 3256): 2015-12-15T03:41:11.393Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3256): 
I/jxcore-log( 3256): ---- round done--------
I/jxcore-log( 3256): 
I/jxcore-log( 3256): startWithNextDevice
I/jxcore-log( 3256): 
I/jxcore-log( 3256): device[13]: 34:FC:EF:9D:93:0B
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:41:11.394Z SendDataConnector.js: Start called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:41:11.394Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:41:11.394Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: Thali Test's G2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 433)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e52254 rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e52254 rs_disc_pending=0
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 2098): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e5241c rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 2098): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2098): Entering PendingCommandState State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 2098): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2098): StableState(): Entering Off State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [34:FC:EF:9D:93:0B LGE-LG-D802_PT8130 34:FC:EF:9D:93:0B]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 433)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 434)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 434)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 433)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 434)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 77 bytes successfully (thread ID: 434)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [34:FC:EF:9D:93:0B LGE-LG-D802_PT8130 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT8130 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 434)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT8130 34:FC:EF:9D:93:0B]
,I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: 34:FC:EF:9D:93:0B, name: LGE-LG-D802_PT8130, Bluetooth address: 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID 34:FC:EF:9D:93:0B, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 435)
,D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 53562
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 53562 (peer ID: 34:FC:EF:9D:93:0B)
I/jxcore-log( 3256): 2015-12-15T03:41:17.131Z SendDataConnector.js: CLIENT connected to 53562, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:41:17.132Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 53562
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 435)
,I/jxcore-log( 3256): 2015-12-15T03:41:17.154Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 437, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 436, name: Sender)
,I/jxcore-log( 3256): 2015-12-15T03:41:17.922Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3256): 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3256): 2015-12-15T03:41:18.235Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3256): 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3256): 2015-12-15T03:41:18.630Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3256): 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3256): 2015-12-15T03:41:18.922Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:41:19.193Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:41:19.406Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3256): 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3256): 2015-12-15T03:41:19.892Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:41:20.098Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:41:20.572Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3256): 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3256): 2015-12-15T03:41:20.976Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:41:20.976Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3256): 
I/jxcore-log( 3256): oneRoundDownNow
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:41:20.981Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:41:20.984Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:9D:93:0B
I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 437
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 436
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 436, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 34:FC:EF:9D:93:0B disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 437, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 34:FC:EF:9D:93:0B disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Successfully disconnected (peer ID: 34:FC:EF:9D:93:0B
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 436, name: Sender)
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 437, name: Receiver)
,I/jxcore-log( 3256): 2015-12-15T03:41:21.015Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3256): 
I/jxcore-log( 3256): ---- round done--------
I/jxcore-log( 3256): 
I/jxcore-log( 3256): startWithNextDevice
I/jxcore-log( 3256): 
I/jxcore-log( 3256): device[14]: 44:80:EB:7B:5A:05
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:41:21.015Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:41:21.015Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:41:21.015Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
,I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 438)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Thali Test's G2
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0x1f  CID 0x42
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:109, failed to find channle,                                       status:1, scn:0
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,W/bt-btif ( 2098): invalid rfc slot id: 109
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btm  ( 2098): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e52254 rs_disc_pending=2
E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: G4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): Connection timeout
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2098): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 2098): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2098): Entering PendingCommandState State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2098): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2098): StableState(): Entering Off State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [44:80:EB:7B:5A:05 motorola-XT1072_PT3356 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 438)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 438)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9389","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9389 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9389","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9389","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Cancelled: Connection timeout [44:80:EB:7B:5A:05 motorola-XT1072_PT3356 44:80:EB:7B:5A:05]
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT9389, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: , Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/jxcore-log( 3256): 2015-12-15T03:41:46.667Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:41:46.674Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:41:46.675Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: XT1072
,I/jxcore-log( 3256): 2015-12-15T03:41:51.675Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:41:51.676Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3256): 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: 44:80:EB:7B:5A:05), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:41:56.680Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:41:56.681Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:41:56.682Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:41:56.682Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: XT1072 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
,I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 439)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local services cleared successfully
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0xd  CID 0x41
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:111, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 111
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:112, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 112
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 439)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect again in 300 ms... (thread ID: 439)
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: XT1072
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [44:80:EB:7B:5A:05 motorola-XT1072_PT3356 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 2 (thread ID: 439)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 440)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 440)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 439)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 440)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 81 bytes successfully (thread ID: 440)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT3356 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [44:80:EB:7B:5A:05 motorola-XT1072_PT3356 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 440)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT3356 44:80:EB:7B:5A:05]
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: 44:80:EB:7B:5A:05, name: motorola-XT1072_PT3356, Bluetooth address: 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 44:80:EB:7B:5A:05 already in the list
,I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID 44:80:EB:7B:5A:05, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 441)
D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 54766
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 54766 (peer ID: 44:80:EB:7B:5A:05)
,I/jxcore-log( 3256): 2015-12-15T03:42:12.130Z SendDataConnector.js: CLIENT connected to 54766, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:42:12.131Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 54766
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 441),
,I/jxcore-log( 3256): 2015-12-15T03:42:12.153Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 443, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 442, name: Sender)
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3256): 2015-12-15T03:42:12.924Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3256): 
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18766
,I/jxcore-log( 3256): 2015-12-15T03:42:12.982Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3256): 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3256): 2015-12-15T03:42:13.331Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3256): 
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 3256): 2015-12-15T03:42:13.459Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3256): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3538"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT3538 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3538"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT3538, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: , Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/jxcore-log( 3256): 2015-12-15T03:42:13.581Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:42:13.920Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3256): 
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3256): 2015-12-15T03:42:14.203Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:42:14.451Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:42:14.606Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:42:14.607Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): oneRoundDownNow
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:42:14.615Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:42:14.619Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 44:80:EB:7B:5A:05
I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 443
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 442
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 442, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 44:80:EB:7B:5A:05 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 443, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 44:80:EB:7B:5A:05 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Successfully disconnected (peer ID: 44:80:EB:7B:5A:05
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 442, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 443, name: Receiver)
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,I/jxcore-log( 3256): 2015-12-15T03:42:14.665Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3256): 
I/jxcore-log( 3256): ---- round done--------
I/jxcore-log( 3256): 
I/jxcore-log( 3256): startWithNextDevice
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): device[15]: 7C:F9:0E:51:18:22
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:42:14.676Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:42:14.677Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:42:14.677Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 444)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e525e4 rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2098): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: XT1072
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
E/bt-btif ( 2098): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2098): Entering PendingCommandState State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 2098): Failed to remove device: 7C:F9:0E:51:18:22
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2098): StableState(): Entering Off State
,E/BluetoothEventManager( 2686): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4840 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 444)
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 445)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 445)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 444)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 445)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 83 bytes successfully (thread ID: 445)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4840 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4840 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 445)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4840 7C:F9:0E:51:18:22]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT4840, Bluetooth address: 7C:F9:0E:51:18:22
,D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
,I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID 7C:F9:0E:51:18:22, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 446)
,D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 37818
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 37818 (peer ID: 7C:F9:0E:51:18:22)
I/jxcore-log( 3256): 2015-12-15T03:42:22.312Z SendDataConnector.js: CLIENT connected to 37818, error: null
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:42:22.313Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 37818
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 446)
,I/jxcore-log( 3256): 2015-12-15T03:42:22.345Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 447, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 448, name: Receiver)
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,W/ProcessCpuTracker(  758): Skipping unknown process pid 4027
W/ProcessCpuTracker(  758): Skipping unknown process pid 4028
W/ProcessCpuTracker(  758): Skipping unknown process pid 4030
,W/ProcessCpuTracker(  758): Skipping unknown process pid 4031
W/ProcessCpuTracker(  758): Skipping unknown process pid 4032
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3256): 2015-12-15T03:42:23.810Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3256): 
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3256): 2015-12-15T03:42:25.722Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3256): 
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 3256): 2015-12-15T03:42:28.383Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:42:31.223Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3256): 
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3256): 2015-12-15T03:42:34.300Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:42:44.301Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:42:44.302Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:42:44.303Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:42:44.304Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:42:44.305Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3256): 
,E/io.jxcore.node.StreamCopyingThread( 3256): Input stream got -1 on read (thread ID: 447, thread name: Sender)
E/io.jxcore.node.OutgoingSocketThread( 3256): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Input stream got -1 on read
,I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 448
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 447
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 448, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 448, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 447, name: Sender)
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,I/jxcore-log( 3256): 2015-12-15T03:42:49.305Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:42:49.306Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3256): 
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Thali Test (Galaxy A5)
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:42:54.311Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:42:54.312Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:42:54.312Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:42:54.313Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 449)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2098): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 2098): DISCOVERY_COMP_EVT slot id:115, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2098): invalid rfc slot id: 115
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [7c:f9:0e:51:18:22]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Thali Test (Galaxy A5)
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4840 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 449)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 450)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 450)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 449)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 450)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 83 bytes successfully (thread ID: 450)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4840 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4840 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 450)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4840 7C:F9:0E:51:18:22]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT4840, Bluetooth address: 7C:F9:0E:51:18:22
,D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
,I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID 7C:F9:0E:51:18:22, created successfully
,D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 451)
,D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 46852
,I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 46852 (peer ID: 7C:F9:0E:51:18:22)
I/jxcore-log( 3256): 2015-12-15T03:43:01.160Z SendDataConnector.js: CLIENT connected to 46852, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:43:01.161Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 46852
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 451)
,I/jxcore-log( 3256): 2015-12-15T03:43:01.183Z SendDataConnector.js: CLIENT now sending 50000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 452, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 453, name: Receiver)
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2098): dm_pm_timer expires
W/bt-btif ( 2098): dm_pm_timer expires 0
W/bt-btif ( 2098): proc dm_pm_timer expires
,I/jxcore-log( 3256): 2015-12-15T03:43:11.506Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:43:11.509Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:43:11.510Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:43:11.511Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:43:11.512Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3256): 
,E/io.jxcore.node.StreamCopyingThread( 3256): Input stream got -1 on read (thread ID: 452, thread name: Sender)
,E/io.jxcore.node.OutgoingSocketThread( 3256): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Input stream got -1 on read
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 3256): close
,I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 453
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 452
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 453, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 453, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 452, name: Sender)
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): startServiceDiscovery: Invalid state, try calling restart()
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/jxcore-log( 3256): 2015-12-15T03:43:16.512Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:43:16.513Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
,I/jxcore-log( 3256): 2015-12-15T03:43:21.517Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:43:21.526Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:43:21.527Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:43:21.528Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 454)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Thali Test (Galaxy A5)
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4840 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 454)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 455)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 455)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 454)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 455)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 83 bytes successfully (thread ID: 455)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4840 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4840 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 455)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4840 7C:F9:0E:51:18:22]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT4840, Bluetooth address: 7C:F9:0E:51:18:22
,D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
,I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID 7C:F9:0E:51:18:22, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 456)
,D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 33431
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 33431 (peer ID: 7C:F9:0E:51:18:22)
I/jxcore-log( 3256): 2015-12-15T03:43:27.492Z SendDataConnector.js: CLIENT connected to 33431, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:43:27.493Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 33431
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 456)
,I/jxcore-log( 3256): 2015-12-15T03:43:27.515Z SendDataConnector.js: CLIENT now sending 50000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 458, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 457, name: Sender)
,I/jxcore-log( 3256): 2015-12-15T03:43:32.078Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:43:32.084Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:43:32.186Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:43:32.187Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3256): 
I/jxcore-log( 3256): oneRoundDownNow
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:43:32.195Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:43:32.196Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 458
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 457
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 457, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 458, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:51:18:22
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 458, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 457, name: Sender)
,I/jxcore-log( 3256): 2015-12-15T03:43:32.243Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): ---- round done--------
I/jxcore-log( 3256): 
I/jxcore-log( 3256): startWithNextDevice
I/jxcore-log( 3256): 
I/jxcore-log( 3256): device[16]: 08:EC:A9:50:75:41
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:43:32.244Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:43:32.244Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:43:32.244Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
,D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 459)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2098): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e527ac rs_disc_pending=0
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3256): timeout now
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): weAreDoneNow, resultArray.length: 15
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): sendReportNow
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): done, now sending data to server
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:43:34.259Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-15T03:43:34.262Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3256): 
,W/bt-btif ( 2098): info:x10
,D/        ( 2098): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e527ac rs_disc_pending=1
W/bt-btif ( 2098): bta_dm_check_av:0
,E/BluetoothRemoteDevices( 2098): aclStateChangeCallback: Device is NULL
W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: Thali Test (Galaxy A5)
,E/bt-btm  ( 2098): tBTM_SEC_DEV:0xa3e52974 rs_disc_pending=0
W/bt-btif ( 2098): bta_dm_check_av:0
,W/bt-btif ( 2098): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2098): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 2098): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2098): Entering PendingCommandState State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 2098): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2098): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2098): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2098): StableState(): Entering Off State
,W/BluetoothEventManager( 2686): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2686): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,W/bt-btif ( 2098): new conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2098): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: Authenticating next: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9389 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 459)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 460)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 460)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 459)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Entering thread (ID: 460)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 83 bytes successfully (thread ID: 460)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9389 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onAuthenticated: Fully connected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9389 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9389 08:EC:A9:50:75:41]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:75:41, name: samsung-SM-A300FU_PT9389, Bluetooth address: 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer with ID 08:EC:A9:50:75:41, created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3256): Exiting thread (ID: 460)
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 461)
,D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 43427
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 43427 (peer ID: 08:EC:A9:50:75:41)
I/jxcore-log( 3256): 2015-12-15T03:43:37.406Z SendDataConnector.js: CLIENT connected to 43427, error: null
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:43:37.407Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 43427
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 461)
,I/jxcore-log( 3256): 2015-12-15T03:43:37.431Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 462, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 463, name: Receiver)
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,D/        ( 2098): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11836
,D/btif_config_util( 2098): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3256): 2015-12-15T03:43:42.209Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:43:42.210Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3256): 
I/jxcore-log( 3256): oneRoundDownNow
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:43:42.211Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-15T03:43:42.212Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
I/io.jxcore.node.OutgoingSocketThread( 3256): close
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 463
I/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 462
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 462, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:75:41 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 463, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:75:41 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:75:41
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 462, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 463, name: Receiver)
,I/jxcore-log( 3256): 2015-12-15T03:43:42.254Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3256): 
,W/bt-btif ( 2098): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,E/bt-btm  ( 2098): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2098): onReceive
,I/BTConnectionReceiver( 1366): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1366): Bluetooth Device Name: A3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged,
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Android_1950 b6:ce:f6:ad:a4:6b
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3256): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7596"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7596"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7596"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7596"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT7596, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: XT1039_8c05, Wi-Fi Direct address: f4:f1:e1:5c:43:c8
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
,W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT3417"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT3417"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT3417"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT3417"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT3417, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2082","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT2082 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2082","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2082","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2082","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT2082, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: , Wi-Fi Direct address: fa:cf:c5:d9:e5:62
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9389","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9389 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9389","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9389","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9389","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT9389, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: , Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5929","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT5929 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5929","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5929","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5929","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: F8:95:C7:87:85:54, peer name: LGE-LG-D722_PT5929, peer ID: F8:95:C7:87:85:54, Wi-Fi Direct device name: G3s-1, Wi-Fi Direct address: a2:39:f7:70:12:80
,I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Adding peer with ID F8:95:C7:87:85:54
,I/jxcore-log( 3256): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT5929","peerAvailable":true}]
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Found peer : LGE-LG-D722_PT5929, Available: true
I/jxcore-log( 3256): 
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT8130"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT8130 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT8130"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT8130"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT8130"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT8130, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: , Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 6 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4642","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4642 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 7 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4642","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4642","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4642","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT4642, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 7 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3538"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT3538 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 8 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3538"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3538"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3538"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT3538, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: Android_1950, Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2756","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT2756 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 9 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2756","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2756","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT2756","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT2756, peer ID: E0:DB:10:1F:C9:5E, Wi-Fi Direct device name: , Wi-Fi Direct address: ea:50:8b:de:28:a3
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID E0:DB:10:1F:C9:5E already in the list
,W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 9 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT2862","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT2862 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 10 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT2862","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT2862","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT2862","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 90:E7:C4:F6:69:77, peer name: HTC-HTC One M8s_PT2862, peer ID: 90:E7:C4:F6:69:77, Wi-Fi Direct device name: Android_608e, Wi-Fi Direct address: 92:e7:c4:e6:4c:f8
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 90:E7:C4:F6:69:77 already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 10 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT37","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT37 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 11 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT37","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT37","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT37","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT37, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: G3-1, Wi-Fi Direct address: 02:9a:02:7b:60:ac
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 58:3F:54:73:64:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 11 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT301","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT301 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 12 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT301","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT301","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT301","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: samsung-SM-A500FU_PT301, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: A5-1, Wi-Fi Direct address: 7e:f9:0e:37:96:ac
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 12 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
,W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery started successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT3461"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [38:94:96:B5:06:DC samsung-SM-G800H_PT3461 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT3461"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT3461"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 38:94:96:B5:06:DC, peer name: samsung-SM-G800H_PT3461, peer ID: 38:94:96:B5:06:DC, Wi-Fi Direct device name: Galaxy S5-2, Wi-Fi Direct address: 3a:94:96:b5:06:dd
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 38:94:96:B5:06:DC already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7596"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7596 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7596"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT7596"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT7596, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: XT1039_8c05, Wi-Fi Direct address: f4:f1:e1:5c:43:c8
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT3417"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3417 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT3417"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT3417"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT3417, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
,W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT8130"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT8130 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT8130"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT8130"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT8130, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: Thali Test's G2, Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3356","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT3356 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3356","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT3356","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT3356, peer ID: 44:80:EB:7B:5A:05, Wi-Fi Direct device name: , Wi-Fi Direct address: 44:80:eb:7b:5a:07
,I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 44:80:EB:7B:5A:05 already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9389","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9389 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9389","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9389","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT9389, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: A3-1, Wi-Fi Direct address: 0a:ec:a9:50:75:42,
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 6 peer(s), but doing nothing with that list
,W/bt-smp  ( 2098): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2098): Plain text(LSB ~ MSB) = f8 47 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2098): Encrypted text(LSB ~ MSB) = 37 af 48 00 3b 96 07 f8 ec 97 a0 7d 8b 50 32 da 
W/bt-btm  ( 2098): Stopping oneshot timer
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3538"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT3538 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 7 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3538"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3538"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT3538, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: , Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
,W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 7 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT37","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT37 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 8 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT37","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT37","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT37, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: G3-1, Wi-Fi Direct address: 02:9a:02:7b:60:ac
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 58:3F:54:73:64:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT301","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT301 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceListChanged: 9 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT301","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT301","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: samsung-SM-A500FU_PT301, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:37:96:ac
I/io.jxcore.node.ConnectionHelper( 3256): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
W/io.jxcore.node.ConnectionHelper( 3256): onPeerListChanged: Got a list containing 9 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1045): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1045): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1045): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/EventLogService( 1600): Aggregate from 1450149395708 (log), 1450149395708 (data)
,I/jxcore-log( 3256): server initiated timeout
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): testSendData stopped
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): stopServiceDiscovery
,I/wpa_supplicant( 1045): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1045): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): setState: NOT_INITIALIZED
I/jxcore-log( 3256): StopBroadcasting went ok
I/jxcore-log( 3256): 
I/jxcore-log( 3256): sendReportNow
I/jxcore-log( 3256): 
I/jxcore-log( 3256): done, now sending data to server
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-15T03:46:42.349Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3256): 
I/chromium( 3256): [INFO:CONSOLE(63)] "logCallback server initiated timeout", source: file:///android_asset/www/js/thali_main.js (63)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3256): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 3256): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/ActivityManager(  758): Killing 3028:com.android.defcontainer/u0a5 (adj 13): empty for 1806s
,I/ActivityManager(  758): Killing 3180:com.google.android.apps.docs/u0a40 (adj 13): empty for 1808s
,I/ActivityManager(  758): Killing 3146:com.android.musicfx/u0a15 (adj 13): empty for 1809s
,I/ActivityManager(  758): Killing 1480:com.google.android.partnersetup/u0a13 (adj 13): empty for 1809s
,I/ActivityManager(  758): Killing 2857:android.process.acore/u0a4 (adj 15): empty for 1809s
,I/ActivityManager(  758): Killing 3053:com.google.android.gms:car/u0a8 (adj 15): empty for 1816s
,I/ActivityManager(  758): Killing 2014:com.android.providers.calendar/u0a2 (adj 15): empty for 1817s
,I/ProcessStatsService(  758): Prepared write state in 3ms
,W/libprocessgroup(  758): failed to open /acct/uid_10040/pid_3180/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10008/pid_3053/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10002/pid_2014/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10005/pid_3028/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10015/pid_3146/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10013/pid_1480/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10004/pid_2857/cgroup.procs: No such file or directory
,V/GLSActivity( 1576): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1576): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  758): Pruning old procstats: /data/system/procstats/state-2015-12-14-15-37-21.bin
,TIME-OUT KILL (timeout was 1800000ms)
```
