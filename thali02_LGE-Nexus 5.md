#### Test 55431344e5dd625_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3160): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3160):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3160):   adb logcat -s GAv4
W/GAv4    ( 3160): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3160): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3160): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3160): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2624): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  733): Killing 2053:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/ResourcesManager( 3160): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3160): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  733): failed to open /acct/uid_10038/pid_2053/cgroup.procs: No such file or directory
V/JNIHelp ( 3160): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3160): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3160): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1619): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1619): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1619): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1619): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3229): 
D/AndroidRuntime( 3229): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3229): CheckJNI is OFF
D/AndroidRuntime( 3229): Calling main entry com.android.commands.am.Am
I/ActivityManager(  733): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  733): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3250 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3229): Shutting down VM
I/ActivityManager(  733): Killing 2543:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
V/ActivityManager(  733): Display changed displayId=0
W/libprocessgroup(  733): failed to open /acct/uid_10045/pid_2543/cgroup.procs: No such file or directory
I/WebViewFactory( 3250): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3250): Time to load native libraries: 2 ms (timestamps 8093-8095)
I/LibraryLoader( 3250): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3250): Binding Chromium to main looper Looper (main, tid 1) {3e3e0239}
I/LibraryLoader( 3250): Expected native library version number "",actual native library version number ""
I/chromium( 3250): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3250): Initializing chromium process, singleProcess=true
W/art     ( 3250): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3250): ApplicationContext is null in ApplicationStatus
,W/chromium( 3250): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3250): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3250): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3250): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  733): Message: 20
D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@21e109e6:true
,W/art     ( 3250): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3250): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3250): CordovaWebView is running on device made by: LGE
,W/art     ( 3250): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3250): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3250): Render dirty regions requested: true
,D/Atlas   ( 3250): Validating map...
,W/chromium( 3250): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3250): Initialized EGL, version 1.4
D/OpenGLRenderer( 3250): Enabling debug mode 0
,W/IInputConnectionWrapper( 3250): showStatusIcon on inactive InputConnection
,I/ActivityManager(  733): Displayed com.test.thalitest/.MainActivity: +431ms (total +58s369ms)
,W/BindingManager( 3250): Cannot call determinedVisibility() - never saw a connection for the pid: 3250
,D/JsMessageQueue( 3250): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3250): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3250): jxcore cordova android initializing
,W/jxcore-log( 3250): Initializing JXcore engine
W/jxcore-log( 3250): JXcore engine is ready
,W/jxcore-log( 3250): Starting JXcore engine
,W/.test.thalitest( 3250): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7981]" dev="sockfs" ino=7981 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3250): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3250): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8600]" dev="sockfs" ino=8600 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3250): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19195]" dev="sockfs" ino=19195 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3250): Platform android
W/jxcore-log( 3250): 
W/jxcore-log( 3250): Process ARCH arm
W/jxcore-log( 3250): 
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3250): JXcore Cordova bridge is ready!
I/jxcore-log( 3250): 
W/jxcore-log( 3250): JXcore engine is started
I/Choreographer( 3250): Skipped 113 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3250): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3250): Toggling radios to true
I/jxcore-log( 3250): 
,D/BluetoothAdapter( 3250): enable(): BT is already enabled..!
,D/WifiService(  733): New client listening to asynchronous messages
,D/WifiService(  733): setWifiEnabled: true pid=3250, uid=10270
E/WifiService(  733): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3250): Radios toggled
I/jxcore-log( 3250): 
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3250): Received device characteristics:
I/jxcore-log( 3250): Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3250): Bluetooth name: Nexus 5
I/jxcore-log( 3250): Device name: LGE-Nexus 5
I/jxcore-log( 3250): 
,I/jxcore-log( 3250): Perf Test app loaded loaded
I/jxcore-log( 3250): 
,I/Choreographer( 3250): Skipped 69 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3250): check test folder
I/jxcore-log( 3250): 
,I/wpa_supplicant( 1036): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  733): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 3250): found test : ./testFindPeers.js
I/jxcore-log( 3250): 
E/native  (  733): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,I/jxcore-log( 3250): found test : ./testSendData.js
I/jxcore-log( 3250): 
V/NativeCrypto( 1569): Read error: ssl=0xb3dc8e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1569): SSL shutdown failed: ssl=0xb3dc8e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  733): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiStateMachine(  733): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1036): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  733): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  733): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  733): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  733): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler(  893): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Disconnected - quitting
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  733): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1619): CM callback handler got msg 524292
D/TelephonyNetworkFactory( 1247): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  733): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/chromium( 3250): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiNetworkAgent(  733): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant( 1036): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1036): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1036): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1036): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  733): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
,E/WifiStateMachine(  733): Start Dhcp Watchdog 2
,E/native  (  733): do suspend false
,E/WifiStateMachine(  733): scanCount==0 - aborting
,I/dhcpcd  ( 3350): version 5.5.6 starting
,E/dhcpcd  ( 3350): get_duid: Read-only file system
,I/dhcpcd  ( 3350): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3350): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3350): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  733): do suspend true
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  733): Adding iface wlan0 to network 101
,E/WifiStateMachine(  733): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  733): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  733): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  733): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  733): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  733): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  733): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  733): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  733): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  733): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  733): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityManager.CallbackHandler(  893): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1619): CM callback handler got msg 524290
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  733): MasterInitialState.processMessage what=3
D/Tethering(  733): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2749): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 2749): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2749): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
E/GpsLocationProvider(  733): No APN found to select.
,E/GpsLocationProvider(  733): No APN found to select.
,I/SystemUpdateService( 1619): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1619): onCreate
,D/SystemUpdateService( 1619): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1619): active receiver: enabled
,I/SystemUpdateService( 1619): showing system update notification
,I/ValidateNoPeople(  733): skipping global notification
,V/SystemUpdateService( 1619): retry (wakeup: false) in 3599986 ms
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 07:26:18 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452237978273], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452237978258]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Validated
D/ConnectivityService(  733): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  733): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  733): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  893): CM callback handler got msg 524290
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1619): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1247): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ActivityManager(  733): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3400 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1619): onDestroy
,I/GAv4    ( 3400): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3400):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3400):   adb logcat -s GAv4
,W/GAv4    ( 3400): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3400): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3400): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/Nat464Xlat(  733): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  733): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  893): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1619): CM callback handler got msg 524295
,I/WebViewFactory( 3400): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3400): Time to load native libraries: 2 ms (timestamps 5393-5395)
,I/LibraryLoader( 3400): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3400): Binding Chromium to main looper Looper (main, tid 1) {2a6c1043}
,I/LibraryLoader( 3400): Expected native library version number "",actual native library version number ""
,I/chromium( 3400): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3400): Initializing chromium process, singleProcess=true
,W/art     ( 3400): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3400): ApplicationContext is null in ApplicationStatus
,W/chromium( 3400): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3400): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3400): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3400): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3400): Requires BLUETOOTH permission
,I/NSApplication( 3400): Starting up...
,I/ActivityManager(  733): Killing 2722:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10003/pid_2722/cgroup.procs: No such file or directory
,V/MusicLeanback( 2749): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1619): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1619): onCreate
,D/SystemUpdateService( 1619): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1619): active receiver: enabled
,I/SystemUpdateService( 1619): showing system update notification
,I/ValidateNoPeople(  733): skipping global notification
,V/SystemUpdateService( 1619): retry (wakeup: false) in 3599978 ms
,D/SystemUpdateService( 1619): onDestroy
,D/ConnectivityService(  733): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3250): BLE is supported
I/jxcore-log( 3250): 
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  733): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2749): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2749): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1619): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/art     (  733): Explicit concurrent mark sweep GC freed 45833(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.012ms total 86.378ms
,D/SystemUpdateService( 1619): onCreate
,D/SystemUpdateService( 1619): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1619): active receiver: enabled
,E/GpsLocationProvider(  733): No APN found to select.
,I/SystemUpdateService( 1619): showing system update notification
,I/ValidateNoPeople(  733): skipping global notification
,V/SystemUpdateService( 1619): retry (wakeup: false) in 3599979 ms
,D/SystemUpdateService( 1619): onDestroy
,D/Finsky  ( 2624): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2624): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1569): Vacuum at: now=1452237989749 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1569): disconnect managed GoogleApiClient
,I/ActivityManager(  733): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3541 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3541): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3541):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3541):   adb logcat -s GAv4
,W/GAv4    ( 3541): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3541): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3541): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  733): Killing 2702:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  733): Client connection lost with reason: 4
,W/libprocessgroup(  733): failed to open /acct/uid_1000/pid_2702/cgroup.procs: No such file or directory
,I/jxcore-log( 3250): Connected to the server!
I/jxcore-log( 3250): 
,I/chromium( 3250): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3250): --- start :testFindPeers.js---
I/jxcore-log( 3250): 
,I/jxcore-log( 3250): testFindPeers created [object Object]
I/jxcore-log( 3250): 
I/jxcore-log( 3250): serverPort is 8876
I/jxcore-log( 3250): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3250): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3250): bind: Binding a new listener
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3250): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3250): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3250): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3250): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3250): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3250): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3250): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3250): start: OK
I/io.jxcore.node.ConnectionHelper( 3250): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3250): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3250): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3250): start: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3250): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3250): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3250): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3250): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3250): start: OK
I/jxcore-log( 3250): StartBroadcasting started ok
I/jxcore-log( 3250): 
I/chromium( 3250): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3250): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3250): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3250): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3250): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3250): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3250): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3250): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pManager( 3250): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3250): Service request added successfully
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3250): Service discovery started successfully
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1036): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3250): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3250): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3250): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3250): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3250): Service request added successfully
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3250): Service discovery started successfully
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3250): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3250): restart: Restarting...
,D/WifiP2pManager( 3250): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3250): Service request added successfully
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3250): Service discovery started successfully
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3250): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3250): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3250): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 3250): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3250): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
I/jxcore-log( 3250): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"G4-1","peerAvailable":true}]
I/jxcore-log( 3250): 
,I/jxcore-log( 3250): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 3250): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3250): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3250): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3250): setState: RESTARTING
,I/wpa_supplicant( 1036): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1036): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1036): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1036): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3250): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3250): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3250): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3250): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3250): Start timer timeout, starting now...
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3250): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3250): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3250): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1036): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3250): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3250): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3250): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,D/WifiP2pManager( 3250): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3250): Service request added successfully
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3250): Service discovery started successfully
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3250): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3250): restart: Restarting...
,D/WifiP2pManager( 3250): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3250): Service request added successfully
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3250): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3250): Service discovery started successfully
,I/wpa_supplicant( 1036): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1036): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1036): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3250): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3250): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3250): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3250): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3250): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 3250): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 3250): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] is available
,I/jxcore-log( 3250): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"G3s-1","peerAvailable":true}]
I/jxcore-log( 3250): 
I/jxcore-log( 3250): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 3250): 
,I/jxcore-log( 3250): timeout now
I/jxcore-log( 3250): 
I/jxcore-log( 3250): weAreDoneNow
I/jxcore-log( 3250): 
I/jxcore-log( 3250): done, now sending data to server
I/jxcore-log( 3250): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3250): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3250): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3250): setState: RESTARTING
,I/wpa_supplicant( 1036): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1036): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1036): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1036): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1036): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3250): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3250): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3250): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3250): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3250): onP2pDeviceListChanged: 0 device(s) discovered
,I/jxcore-log( 3250): teardown
I/jxcore-log( 3250): 
,I/jxcore-log( 3250): testFindPeers stopped
I/jxcore-log( 3250): 
I/io.jxcore.node.ConnectionHelper( 3250): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3250): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3250): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3250): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3250): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3250): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3250): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3250): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3250): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3250): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3250): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3250): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3250): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3250): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3250): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3250): setState: NOT_STARTED
I/jxcore-log( 3250): StopBroadcasting went ok
I/jxcore-log( 3250): 
,I/chromium( 3250): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3250): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3250): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3250): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3250): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3250): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3250): teardown
I/jxcore-log( 3250): 
,E/jxcore  ( 3250): Error!: self.currentTest is null
E/jxcore  ( 3250): Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"169","_columnNumber":"5","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:169:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"263","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"221","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"333","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:7"}]
I/chromium( 3250): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)

```
