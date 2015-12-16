#### Test 506502789b39735_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3153): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3153):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3153):   adb logcat -s GAv4
W/GAv4    ( 3153): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3153): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3153): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3153): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2633): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  740): Killing 2051:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/ResourcesManager( 3153): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3153): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  740): failed to open /acct/uid_10038/pid_2051/cgroup.procs: No such file or directory
V/JNIHelp ( 3153): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3153): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3153): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1653): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1653): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1653): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1653): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/ActivityManager(  740): Killing 2581:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  740): failed to open /acct/uid_10069/pid_2581/cgroup.procs: No such file or directory
D/AndroidRuntime( 3218): 
D/AndroidRuntime( 3218): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3218): CheckJNI is OFF
D/AndroidRuntime( 3218): Calling main entry com.android.commands.am.Am
I/ActivityManager(  740): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  740): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3232 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3218): Shutting down VM
V/ActivityManager(  740): Display changed displayId=0
I/WebViewFactory( 3232): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3232): Time to load native libraries: 2 ms (timestamps 47-49)
I/LibraryLoader( 3232): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3232): Binding Chromium to main looper Looper (main, tid 1) {3742cb48}
I/LibraryLoader( 3232): Expected native library version number "",actual native library version number ""
I/chromium( 3232): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3232): Initializing chromium process, singleProcess=true
W/art     ( 3232): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3232): ApplicationContext is null in ApplicationStatus
W/chromium( 3232): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3232): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3232): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3232): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  740): Message: 20
D/BluetoothManagerService(  740): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@203c34d4:true
,W/art     ( 3232): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3232): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3232): CordovaWebView is running on device made by: LGE
,W/art     ( 3232): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3232): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3232): Render dirty regions requested: true
,D/Atlas   ( 3232): Validating map...
,W/chromium( 3232): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3232): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3232): Enabling debug mode 0
,W/BindingManager( 3232): Cannot call determinedVisibility() - never saw a connection for the pid: 3232
,W/IInputConnectionWrapper( 3232): showStatusIcon on inactive InputConnection
I/ActivityManager(  740): Displayed com.test.thalitest/.MainActivity: +426ms (total +60s98ms)
,D/JsMessageQueue( 3232): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3232): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257343360
D/JX-Cordova( 3232): jxcore cordova android initializing
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/jxcore-log( 3232): Initializing JXcore engine
W/jxcore-log( 3232): JXcore engine is ready
,W/jxcore-log( 3232): Starting JXcore engine
,W/.test.thalitest( 3232): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6538]" dev="sockfs" ino=6538 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3232): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3232): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6766]" dev="sockfs" ino=6766 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3232): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19870]" dev="sockfs" ino=19870 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3232): Platform android
W/jxcore-log( 3232): 
,W/jxcore-log( 3232): Process ARCH arm
W/jxcore-log( 3232): 
,I/jxcore-log( 3232): JXcore Cordova bridge is ready!
I/jxcore-log( 3232): 
W/jxcore-log( 3232): JXcore engine is started
I/Choreographer( 3232): Skipped 108 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3232): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  740): Killing 2522:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  740): failed to open /acct/uid_10045/pid_2522/cgroup.procs: No such file or directory
,I/jxcore-log( 3232): Toggling radios to true
I/jxcore-log( 3232): 
,D/BluetoothAdapter( 3232): enable(): BT is already enabled..!
,D/WifiService(  740): New client listening to asynchronous messages
,D/WifiService(  740): setWifiEnabled: true pid=3232, uid=10270
E/WifiService(  740): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3232): Radios toggled
I/jxcore-log( 3232): 
,D/BluetoothManagerService(  740): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3232): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3232): 
I/jxcore-log( 3232): Perf Test app loaded loaded
I/jxcore-log( 3232): 
,I/jxcore-log( 3232): check test folder
I/jxcore-log( 3232): 
I/jxcore-log( 3232): found test : ./testFindPeers.js
I/jxcore-log( 3232): 
I/wpa_supplicant(  988): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  740): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  740): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  740): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,I/jxcore-log( 3232): found test : ./testSendData.js
I/jxcore-log( 3232): 
,V/NativeCrypto( 1605): Read error: ssl=0xaf566e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1605): SSL shutdown failed: ssl=0xaf566e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  740): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): ValidatedState{ when=-3ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): DefaultState{ when=-3ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  740): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  740): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  740): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  740): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  988): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  740): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/ConnectivityService(  740): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524292
D/Nat464Xlat(  740): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  740): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  740): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1653): CM callback handler got msg 524292
D/ConnectivityService(  740): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  740): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1289): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): Disconnected - quitting
,I/Choreographer( 3232): Skipped 69 frames!  The application may be doing too much work on its main thread.
I/chromium( 3232): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiNetworkAgent(  740): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  988): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  988): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  988): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  988): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  740): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  740): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  740): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  740): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
E/WifiStateMachine(  740): Start Dhcp Watchdog 2
,E/native  (  740): do suspend false
,E/WifiStateMachine(  740): scanCount==0 - aborting
,I/dhcpcd  ( 3344): version 5.5.6 starting
,E/dhcpcd  ( 3344): get_duid: Read-only file system
,I/dhcpcd  ( 3344): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3344): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3344): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  740): do suspend true
,D/ConnectivityService(  740): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  740): Adding iface wlan0 to network 101
E/WifiStateMachine(  740): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  740): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  740): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  740): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  740): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  740): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  740): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  740): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  740): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  740): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  740):    accepting network in place of null
,D/CSLegacyTypeTracker(  740): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  740): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  740): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  740): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1653): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 01:33:43 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450229623134], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450229623115]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): Validated
D/ConnectivityService(  740): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  740): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  740): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  740): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  740): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1289): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1653): CM callback handler got msg 524290
,D/ConnectivityService(  740): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  740): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  740): MasterInitialState.processMessage what=3
,D/Tethering(  740): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2739): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 2739): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2739): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  740): No APN found to select.
,E/GpsLocationProvider(  740): No APN found to select.
,I/SystemUpdateService( 1653): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1653): onCreate
,D/SystemUpdateService( 1653): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/ActivityManager(  740): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3388 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SystemUpdateService( 1653): active receiver: enabled
,I/SystemUpdateService( 1653): showing system update notification
,I/ValidateNoPeople(  740): skipping global notification
,V/SystemUpdateService( 1653): retry (wakeup: false) in 3599967 ms
,D/SystemUpdateService( 1653): onDestroy
,I/GAv4    ( 3388): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3388):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3388):   adb logcat -s GAv4
,W/GAv4    ( 3388): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3388): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3388): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3388): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/Nat464Xlat(  740): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  740): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1653): CM callback handler got msg 524295
,I/LibraryLoader( 3388): Time to load native libraries: 3 ms (timestamps 6938-6941)
,I/LibraryLoader( 3388): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3388): Binding Chromium to main looper Looper (main, tid 1) {118747fa}
,I/LibraryLoader( 3388): Expected native library version number "",actual native library version number ""
,I/chromium( 3388): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3388): Initializing chromium process, singleProcess=true
,W/art     ( 3388): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3388): ApplicationContext is null in ApplicationStatus
,W/chromium( 3388): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3388): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3388): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3388): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/ConnectivityService(  740): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/AudioManagerAndroid( 3388): Requires BLUETOOTH permission
,I/NSApplication( 3388): Starting up...
,I/ActivityManager(  740): Killing 2717:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  740): failed to open /acct/uid_10003/pid_2717/cgroup.procs: No such file or directory
,V/MusicLeanback( 2739): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1653): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1653): onCreate
,D/SystemUpdateService( 1653): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1653): active receiver: enabled
,I/SystemUpdateService( 1653): showing system update notification
,I/ValidateNoPeople(  740): skipping global notification
,V/SystemUpdateService( 1653): retry (wakeup: false) in 3599989 ms
,D/SystemUpdateService( 1653): onDestroy
,I/jxcore-log( 3232): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3232): 
,D/ConnectivityService(  740): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  740): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2739): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2739): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1653): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1653): onCreate
,D/SystemUpdateService( 1653): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1653): active receiver: enabled
,I/SystemUpdateService( 1653): showing system update notification
,I/ValidateNoPeople(  740): skipping global notification
,V/SystemUpdateService( 1653): retry (wakeup: false) in 3599954 ms
,D/SystemUpdateService( 1653): onDestroy
,I/art     (  740): Explicit concurrent mark sweep GC freed 43823(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 896us total 58.967ms
,E/GpsLocationProvider(  740): No APN found to select.
,D/Finsky  ( 2633): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2633): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1605): Vacuum at: now=1450229638541 tag=VacuumService
,I/PhenotypeConfigurator( 1605): Scheduling Phenotype for one-off execution 6081 seconds from now (1450229638870)
,D/GetConfigurationSnapshotOperation( 1605): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1605): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1605): Using platform SSLCertificateSocketFactory
,I/ClearcutLoggerApiImpl( 1605): disconnect managed GoogleApiClient
,I/jxcore-log( 3232): Connected to the server!
I/jxcore-log( 3232): 
,I/chromium( 3232): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager(  740): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3588 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,W/bt-smp  ( 2078): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2078): Plain text(LSB ~ MSB) = e9 92 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2078): Encrypted text(LSB ~ MSB) = e0 f5 6d fa cf 96 41 26 0b 8f ac 6e a1 22 4a 5e 
W/bt-btm  ( 2078): Stopping oneshot timer
,I/EventLogService( 1653): Aggregate from 1450229373214 (log), 1450228150859 (data)
,I/GAv4    ( 3588): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3588):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3588):   adb logcat -s GAv4
,W/GAv4    ( 3588): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3588): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3588): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  740): Killing 2692:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  740): Client connection lost with reason: 4
,W/libprocessgroup(  740): failed to open /acct/uid_1000/pid_2692/cgroup.procs: No such file or directory
,I/UsageStatsService(  740): User[0] Flushing usage stats to disk
,I/ProcessStatsService(  740): Prepared write state in 11ms
,I/ProcessStatsService(  740): Prepared write state in 3ms
,W/bt-smp  ( 2078): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2078): Plain text(LSB ~ MSB) = 99 6a 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2078): Encrypted text(LSB ~ MSB) = c0 2a d0 5a 3c 03 d2 2c 7f 83 6f 7f 3a 48 57 b8 
W/bt-btm  ( 2078): Stopping oneshot timer
,I/ProcessStatsService(  740): Pruning old procstats: /data/system/procstats/state-2015-12-15-15-43-29.bin
,TIME-OUT KILL (timeout was 1800000ms),I/ActivityManager(  740): Killing 3117:com.android.musicfx/u0a15 (adj 13): empty for 1814s
I/ActivityManager(  740): Killing 1497:com.google.android.partnersetup/u0a13 (adj 13): empty for 1814s
I/ActivityManager(  740): Killing 2003:com.android.providers.calendar/u0a2 (adj 13): empty for 1819s
I/ActivityManager(  740): Killing 3033:com.google.android.gms:car/u0a8 (adj 13): empty for 1820s
I/ActivityManager(  740): Killing 1983:com.google.android.calendar/u0a31 (adj 15): empty for 1850s
I/ActivityManager(  740): Killing 2548:com.google.android.gm/u0a70 (adj 15): empty for 1850s
W/libprocessgroup(  740): failed to open /acct/uid_10015/pid_3117/cgroup.procs: No such file or directory
W/libprocessgroup(  740): failed to open /acct/uid_10002/pid_2003/cgroup.procs: No such file or directory
W/libprocessgroup(  740): failed to open /acct/uid_10008/pid_3033/cgroup.procs: No such file or directory
W/libprocessgroup(  740): failed to open /acct/uid_10031/pid_1983/cgroup.procs: No such file or directory
W/libprocessgroup(  740): failed to open /acct/uid_10070/pid_2548/cgroup.procs: No such file or directory
W/libprocessgroup(  740): failed to open /acct/uid_10013/pid_1497/cgroup.procs: No such file or directory
V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  740): Killing 3153:com.google.android.apps.docs/u0a40 (adj 15): empty for 1814s
W/libprocessgroup(  740): failed to open /acct/uid_10040/pid_3153/cgroup.procs: No such file or directory
D/AndroidRuntime( 3711): 
D/AndroidRuntime( 3711): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3711): CheckJNI is OFF
D/AndroidRuntime( 3711): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  740): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  740): Killing 3232:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  740): WIN DEATH: Window{3407b04 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  740): Client connection lost with reason: 4
W/PackageSettings(  740): Skipping PackageSetting{3f14715c com.example.hello/10278} due to missing metadata
I/ActivityManager(  740):   Force finishing activity ActivityRecord{157cfd10 u0 com.test.thalitest/.MainActivity t214}
W/ActivityManager(  740): Spurious death for ProcessRecord{d3c31a7 3232:com.test.thalitest/u0a270}, curProc for 3232: null
I/ActivityManager(  740): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/art     ( 1653): Explicit concurrent mark sweep GC freed 14747(768KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 22MB/30MB, paused 518us total 52.107ms
I/art     ( 1355): Explicit concurrent mark sweep GC freed 3969(294KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 771us total 18.544ms
I/art     ( 1412): Explicit concurrent mark sweep GC freed 15728(1089KB) AllocSpace objects, 1(39KB) LOS objects, 25% free, 18MB/25MB, paused 326us total 22.535ms
W/GeofencerStateMachine( 1605): Ignoring removeGeofence because network location is disabled.
I/InputReader(  740): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1113): resetDictionaries() : en_US
I/Adreno-EGL(  947): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  947): Initialized EGL, version 1.4
I/ActivityManager(  740): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=3752 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
D/OpenGLRenderer(  947): Enabling debug mode 0
I/Keyboard.Facilitator.DecoderInitializer( 1113): run()
D/VoicemailCleanupService( 1406): Cleaning up data for package: com.test.thalitest
I/art     (  740): Explicit concurrent mark sweep GC freed 30520(1777KB) AllocSpace objects, 11(250KB) LOS objects, 33% free, 27MB/41MB, paused 1.581ms total 98.332ms
I/art     (  740): WaitForGcToComplete blocked for 55.922ms for cause Explicit
I/Decoder ( 1113): createOrResetDecoder
W/InputMethodManagerService(  740): Got RemoteException sending setActive(false) notification to pid 3232 uid 10270
I/Keyboard.Facilitator( 1113): onFinishInput()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1113): run()
D/BackupManagerService(  740): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  740): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  740): removeObsoleteFile: deleting file=214_task.xml
I/UpdateIcingCorporaServi( 1412): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  740): Killing 2995:com.android.defcontainer/u0a5 (adj 15): empty for 1814s
I/Keyboard.Facilitator.MainLanguageModelLoader( 1113): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1113): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1113): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1113): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1113): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1113): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1113): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1113): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1113): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1113): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1113): run()
I/StatsUtilsManager( 1113): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1113): shouldRecordStats() = Too Soon
W/Launcher( 1355): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2310ade1 new=com.google.android.velvet.VelvetApplication@2310ade1
I/art     (  740): Explicit concurrent mark sweep GC freed 7751(427KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.136ms total 158.080ms
W/libprocessgroup(  740): failed to open /acct/uid_10005/pid_2995/cgroup.procs: No such file or directory
I/Launcher( 1355): Deferring update until onResume
W/ResourcesManager( 1355): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  740): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3785 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
W/ResourcesManager( 1355): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1355): Deferring update until onResume
D/AndroidRuntime( 3711): Shutting down VM
I/UpdateIcingCorporaServi( 1412): UpdateCorporaTask done [took 176 ms] updated apps [took 176 ms] 
W/ContextImpl( 3785): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
D/PackageBroadcastService( 1653): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1653): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1653): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1653): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1653): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1653): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1653): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1605): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1605): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1653): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1653): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1653): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1653): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1653): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1653): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1653): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1653): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1653): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1653): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1653): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1653): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1653): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  740): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3811 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
W/BaseAppContext( 1653): Using Auth Proxy for data requests.
W/BaseAppContext( 1653): Using Auth Proxy for data requests.
I/GMPM-SVC( 1653): App measurement is starting up, version: 8489
I/GMPM-SVC( 1653): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/Icing   ( 1653): doRemovePackageData com.test.thalitest
I/GAv4    ( 3811): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3811):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3811):   adb logcat -s GAv4
W/GAv4    ( 3811): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3811): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 3811): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3811): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 3811): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 3811): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 3811): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
E/SQLiteDatabase( 3811): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 3811): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3811): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3811): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3811): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3811): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3811): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3811): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3811): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3811): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 3811): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 3811): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3811): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3811): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 3811): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 3811): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 3811): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 3811): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 3811): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 3811): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3811): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3811): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3811): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3811): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3811): 	at gir$c.run(Unknown Source)
E/GAv4    ( 3811): Opening the database failed, dropping the table and recreating it

```
