#### Test 50650278b2f31ec_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/Icing   ( 1642): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/art     ( 1642): WaitForGcToComplete blocked for 6.746ms for cause DisableMovingGc
I/Icing   ( 1642): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1642): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1642): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3232): 
D/AndroidRuntime( 3232): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3232): CheckJNI is OFF
D/AndroidRuntime( 3232): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  736): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  736): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3253 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3232): Shutting down VM
V/ActivityManager(  736): Display changed displayId=0
I/ActivityManager(  736): Killing 2628:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
W/libprocessgroup(  736): failed to open /acct/uid_10045/pid_2628/cgroup.procs: No such file or directory
I/WebViewFactory( 3253): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3253): Time to load native libraries: 1 ms (timestamps 6908-6909)
I/LibraryLoader( 3253): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3253): Binding Chromium to main looper Looper (main, tid 1) {ccf7560}
I/LibraryLoader( 3253): Expected native library version number "",actual native library version number ""
I/chromium( 3253): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3253): Initializing chromium process, singleProcess=true
W/art     ( 3253): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3253): ApplicationContext is null in ApplicationStatus
W/chromium( 3253): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3253): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3253): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3253): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  736): Message: 20
D/BluetoothManagerService(  736): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24c958d:true
,W/art     ( 3253): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3253): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3253): CordovaWebView is running on device made by: LGE
,W/art     ( 3253): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3253): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3253): Render dirty regions requested: true
,D/Atlas   ( 3253): Validating map...
,W/chromium( 3253): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3253): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3253): Enabling debug mode 0
,W/BindingManager( 3253): Cannot call determinedVisibility() - never saw a connection for the pid: 3253
,W/IInputConnectionWrapper( 3253): showStatusIcon on inactive InputConnection
I/ActivityManager(  736): Displayed com.test.thalitest/.MainActivity: +443ms (total +57s309ms)
,D/JsMessageQueue( 3253): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3253): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1404477696
D/JX-Cordova( 3253): jxcore cordova android initializing
,W/jxcore-log( 3253): Initializing JXcore engine
W/jxcore-log( 3253): JXcore engine is ready
W/jxcore-log( 3253): Starting JXcore engine
,W/.test.thalitest( 3253): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7866]" dev="sockfs" ino=7866 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3253): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 3253): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8438]" dev="sockfs" ino=8438 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3253): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20798]" dev="sockfs" ino=20798 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3253): Platform android
W/jxcore-log( 3253): 
,W/jxcore-log( 3253): Process ARCH arm
W/jxcore-log( 3253): 
,I/jxcore-log( 3253): JXcore Cordova bridge is ready!
I/jxcore-log( 3253): 
W/jxcore-log( 3253): JXcore engine is started
,I/Choreographer( 3253): Skipped 109 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3253): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3253): Toggling radios to true
I/jxcore-log( 3253): 
,D/BluetoothAdapter( 3253): enable(): BT is already enabled..!
,D/WifiService(  736): New client listening to asynchronous messages
,D/WifiService(  736): setWifiEnabled: true pid=3253, uid=10270
E/WifiService(  736): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3253): Radios toggled
I/jxcore-log( 3253): 
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3253): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): Perf Test app loaded loaded
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): check test folder
I/jxcore-log( 3253): 
I/wpa_supplicant( 1031): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
I/jxcore-log( 3253): found test : ./testFindPeers.js
I/jxcore-log( 3253): 
,E/WifiStateMachine(  736): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  736): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
I/jxcore-log( 3253): found test : ./testSendData.js
I/jxcore-log( 3253): 
,V/NativeCrypto( 2573): Read error: ssl=0xb42e9200: I/O error during system call, Connection timed out
V/NativeCrypto( 2573): Write error: ssl=0xb42e9200: I/O error during system call, Broken pipe
V/NativeCrypto( 2573): Write error: ssl=0xb42e9200: I/O error during system call, Broken pipe
V/NativeCrypto( 2573): SSL shutdown failed: ssl=0xb42e9200: I/O error during system call, Broken pipe
,V/NativeCrypto( 1571): Read error: ssl=0x9bd01e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1571): SSL shutdown failed: ssl=0x9bd01e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  736): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Checking http://clients3.google.com/generate_204 on "NG7005g"
,E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  736): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  736): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  736): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1031): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  736): do suspend true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  736): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler( 1642): CM callback handler got msg 524292
D/Nat464Xlat(  736): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  736): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/CommandListener(  180): Clearing all IP addresses on wlan0
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Disconnected - quitting
,D/ConnectivityService(  736): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/Choreographer( 3253): Skipped 67 frames!  The application may be doing too much work on its main thread.
I/chromium( 3253): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/TelephonyNetworkFactory( 1195): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  736): NetworkAgent: NetworkAgent channel lost
,W/NetworkUtils( 1382): OkHttp exception
W/EventLoggerService( 1382): Unable to send logs Error code: 262146
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant( 1031): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1031): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1031): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1031): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  736): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  736): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
,E/WifiStateMachine(  736): Start Dhcp Watchdog 2
,E/native  (  736): do suspend false
,E/WifiStateMachine(  736): scanCount==0 - aborting
,I/dhcpcd  ( 3339): version 5.5.6 starting
,E/dhcpcd  ( 3339): get_duid: Read-only file system
,I/dhcpcd  ( 3339): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3339): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3339): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  736): do suspend true
,D/ConnectivityService(  736): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  736): Adding iface wlan0 to network 101
,E/ConnectivityService(  736): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  736): Adding Route [fe80::/64 -> :: wlan0] to network 101
,E/WifiStateMachine(  736): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService(  736): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  736): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  736): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  736): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  736): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  736): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  736): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  736):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  736): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  736): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  736): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1642): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 14 Dec 2015 14:38:36 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450103916450], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450103916432]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Validated
D/ConnectivityService(  736): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  736): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  736): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  736): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1642): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1195): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/Nat464Xlat(  736): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  736): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1642): CM callback handler got msg 524295
,D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  736): MasterInitialState.processMessage what=3
,D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  736): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2778): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2778): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2778): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1642): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1642): onCreate
,D/SystemUpdateService( 1642): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1642): active receiver: enabled
,I/SystemUpdateService( 1642): showing system update notification
,I/ValidateNoPeople(  736): skipping global notification
,V/SystemUpdateService( 1642): retry (wakeup: false) in 3599973 ms
,I/ActivityManager(  736): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3434 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1642): onDestroy
,E/GpsLocationProvider(  736): No APN found to select.
,E/ActivityThread( 1642): Failed to find provider info for com.android.contacts.metadata
,E/GpsLocationProvider(  736): No APN found to select.
,D/SyncManager(  736): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 60158, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  736): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 143654, reason: UserStart
,D/ConnectivityService(  736): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/GAv4    ( 3434): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3434):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3434):   adb logcat -s GAv4
,W/GAv4    ( 3434): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3434): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3434): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3434): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3434): Time to load native libraries: 1 ms (timestamps 3920-3921)
I/LibraryLoader( 3434): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3434): Binding Chromium to main looper Looper (main, tid 1) {329d8652}
,I/LibraryLoader( 3434): Expected native library version number "",actual native library version number ""
,I/chromium( 3434): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3434): Initializing chromium process, singleProcess=true
,W/art     ( 3434): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3434): ApplicationContext is null in ApplicationStatus
,W/chromium( 3434): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3434): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3434): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3434): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3434): Requires BLUETOOTH permission
,I/NSApplication( 3434): Starting up...
,I/ActivityManager(  736): Killing 2750:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10003/pid_2750/cgroup.procs: No such file or directory
,V/MusicLeanback( 2778): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1642): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1642): onCreate
,D/SystemUpdateService( 1642): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1642): active receiver: enabled
,I/SystemUpdateService( 1642): showing system update notification
,I/ValidateNoPeople(  736): skipping global notification
,V/SystemUpdateService( 1642): retry (wakeup: false) in 3599965 ms
,D/SystemUpdateService( 1642): onDestroy
,I/jxcore-log( 3253): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 3253): 
,D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  736): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2778): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2778): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1642): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1642): onCreate
,D/SystemUpdateService( 1642): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1642): active receiver: enabled
,I/SystemUpdateService( 1642): showing system update notification
,E/GpsLocationProvider(  736): No APN found to select.
,I/ValidateNoPeople(  736): skipping global notification
,V/SystemUpdateService( 1642): retry (wakeup: false) in 3599977 ms
,D/SystemUpdateService( 1642): onDestroy
,D/Finsky  ( 2654): [265] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2654): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/art     (  736): Explicit concurrent mark sweep GC freed 53467(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 978us total 58.255ms
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1571): Vacuum at: now=1450103929513 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1571): disconnect managed GoogleApiClient
,I/EventLogService( 1642): Aggregate from 1450102152100 (log), 1450102152100 (data)
,I/jxcore-log( 3253): Connected to the server!
I/jxcore-log( 3253): 
,I/chromium( 3253): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3253): --- start :testFindPeers.js---
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): testFindPeers created [object Object]
I/jxcore-log( 3253): 
I/jxcore-log( 3253): serverPort is 8876
I/jxcore-log( 3253): 
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): initialize: 34:FC:EF:11:AE:67 LGE-Nexus 5_PT4491
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3253): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): setState: INITIALIZED
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3253): start: OK
I/jxcore-log( 3253): StartBroadcasting started ok
I/jxcore-log( 3253): 
I/chromium( 3253): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): startWifiPeerDiscovery: Already started
,I/io.jxcore.node.ConnectionHelper( 3253): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/io.jxcore.node.ConnectionHelper( 3253): onConnectionManagerStateChanged: RUNNING
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Waiting for incoming connections...
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3253): Ignored { when=-22ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-11ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT164"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT164 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT164"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT164"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT164"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT164"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT164, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: , Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
,I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Adding peer with ID B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3253): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"HTC-HTC Desire 820_PT164","peerAvailable":true}]
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): weAreDoneNow
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): done, now sending data to server
I/jxcore-log( 3253): 
,W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT164"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT164"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT164"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT164"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT164"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
,D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test's G2 36:fc:ef:de:0a:e2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,D/WifiP2pManager( 3253): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3578","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3578 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3578","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3578","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3578","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: samsung-SM-A500FU_PT3578, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:37:96:ac
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5671"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT5671 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5671"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5671"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5671"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT5671, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: Thali Test's G2, Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Adding peer with ID 34:FC:EF:9D:93:0B
,W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/jxcore-log( 3253): --- start :testFindPeers.js---
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): testFindPeers created [object Object]
I/jxcore-log( 3253): 
I/jxcore-log( 3253): serverPort is 8876
I/jxcore-log( 3253): 
I/jxcore-log( 3253): weAreDoneNow
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): done, now sending data to server
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): done, now sending data to server
I/jxcore-log( 3253): 
I/chromium( 3253): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3253): teardown
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): testFindPeers stopped
I/jxcore-log( 3253): 
,I/io.jxcore.node.ConnectionHelper( 3253): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Socket is null
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): setState: NOT_INITIALIZED
,I/jxcore-log( 3253): StopBroadcasting went ok
I/jxcore-log( 3253): 
,I/chromium( 3253): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3253): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 3253): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/jxcore-log( 3253): --- start :testSendData.js---
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":23}bt-address length : 0
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): daya100000
I/jxcore-log( 3253): 
I/jxcore-log( 3253): check server
I/jxcore-log( 3253): 
I/jxcore-log( 3253): serverPort is 33708
I/jxcore-log( 3253): 
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): initialize: 34:FC:EF:11:AE:67 LGE-Nexus 5_PT4491
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3253): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): setState: INITIALIZED
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): setState: RUNNING
I/jxcore-log( 3253): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"HTC-HTC Desire 820_PT164","peerAvailable":true},{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT3578","peerAvailable":true},{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"LGE-LG-D802_PT5671","peerAvailable":true}]
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : HTC-HTC Desire 820_PT164, Available: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : samsung-SM-A500FU_PT3578, Available: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : LGE-LG-D802_PT5671, Available: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): startWithNextDevice
I/jxcore-log( 3253): 
I/jxcore-log( 3253): device[1]: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:43:57.886Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:43:57.887Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:43:57.887Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to null in address B4:CE:F6:AB:A4:6A
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: null B4:CE:F6:AB:A4:6A
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to null in address B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: B4:CE:F6:AB:A4:6A)
I/io.jxcore.node.ConnectionHelper( 3253): start: OK
I/jxcore-log( 3253): StartBroadcasting started ok
I/jxcore-log( 3253): 
I/jxcore-log( 3253): null
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:43:57.892Z SendDataTCPServer.js: TCP/IP server is bound to port: 33708
I/jxcore-log( 3253): 
,I/chromium( 3253): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address B4:CE:F6:AB:A4:6A (thread ID: 314)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 3253): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
I/io.jxcore.node.ConnectionHelper( 3253): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3253): teardown
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): testSendData stopped
I/jxcore-log( 3253): 
,I/io.jxcore.node.ConnectionHelper( 3253): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onServerStopped
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 2058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2058): Entering PendingCommandState State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2058): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/BluetoothBondStateMachine( 2058): StableState(): Entering Off State
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:6, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 6
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
,W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,D/BluetoothManagerService(  736): Message: 20
D/BluetoothManagerService(  736): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22712e72:true
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: XT1072
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 2058): L2CAP - con rsp - bad ID. Exp: 5 Got: 3
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 7
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 314)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): setState: NOT_INITIALIZED
I/jxcore-log( 3253): StopBroadcasting went ok
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:44:24.632Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3253): 
D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID B4:CE:F6:AB:A4:6A
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: B4:CE:F6:AB:A4:6A), either no such connection or failed to close the connection
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/jxcore-log( 3253): 2015-12-14T14:44:24.642Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:44:24.687Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3253): 
I/chromium( 3253): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Cannot start, because not initialized
I/io.jxcore.node.ConnectionHelper( 3253): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 3253): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/jxcore-log( 3253): --- start :testSendData.js---
I/jxcore-log( 3253): 
I/jxcore-log( 3253): testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":23}bt-address length : 0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): daya100000
I/jxcore-log( 3253): 
I/jxcore-log( 3253): check server
I/jxcore-log( 3253): 
I/jxcore-log( 3253): serverPort is 60048
I/jxcore-log( 3253): 
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): initialize: 34:FC:EF:11:AE:67 LGE-Nexus 5_PT4491
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3253): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): setState: INITIALIZED
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): setState: RUNNING
I/jxcore-log( 3253): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"HTC-HTC Desire 820_PT164","peerAvailable":true},{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT3578","peerAvailable":true},{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"LGE-LG-D802_PT5671","peerAvailable":true}]
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : HTC-HTC Desire 820_PT164, Available: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : samsung-SM-A500FU_PT3578, Available: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : LGE-LG-D802_PT5671, Available: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): startWithNextDevice
I/jxcore-log( 3253): 
I/jxcore-log( 3253): device[1]: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:44:24.721Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:44:24.721Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:44:24.721Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to null in address B4:CE:F6:AB:A4:6A
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: null B4:CE:F6:AB:A4:6A
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to null in address B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: B4:CE:F6:AB:A4:6A)
I/io.jxcore.node.ConnectionHelper( 3253): start: OK
I/jxcore-log( 3253): StartBroadcasting started ok
I/jxcore-log( 3253): 
I/jxcore-log( 3253): null
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:44:24.728Z SendDataTCPServer.js: TCP/IP server is bound to port: 60048
I/jxcore-log( 3253): 
I/chromium( 3253): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 3253): onConnectionManagerStateChanged: INITIALIZED
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3253): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address B4:CE:F6:AB:A4:6A (thread ID: 316)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Waiting for incoming connections...
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:9, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 9
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 10
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 316)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 316)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 11
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 12
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 316)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 316)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Cannot start, because not initialized
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 13
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 14
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 316)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 316)
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3253): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 15
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 16
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 316)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 316)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:17, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 17
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:18, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 18
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 316)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Maximum number of retries (5) reached, giving up... (thread ID: 316)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 316)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT164 B4:CE:F6:AB:A4:6A]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
I/jxcore-log( 3253): 2015-12-14T14:44:35.870Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:44:35.871Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:44:35.877Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3253): 2015-12-14T14:44:40.879Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:44:40.880Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID B4:CE:F6:AB:A4:6A
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: B4:CE:F6:AB:A4:6A), either no such connection or failed to close the connection
I/jxcore-log( 3253): 2015-12-14T14:44:45.886Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:44:45.887Z SendDataConnector.js: Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:44:45.888Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:44:45.888Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to null in address B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: null B4:CE:F6:AB:A4:6A
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to null in address B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: B4:CE:F6:AB:A4:6A)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address B4:CE:F6:AB:A4:6A (thread ID: 317)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:19, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 19
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 20
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 317)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 21
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 22
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 23
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 24
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 25
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 26
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 27
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:28, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 28
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Maximum number of retries (5) reached, giving up... (thread ID: 317)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 317)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT164 B4:CE:F6:AB:A4:6A]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
I/jxcore-log( 3253): 2015-12-14T14:44:58.888Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:44:58.889Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:44:58.890Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
,W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,I/jxcore-log( 3253): 2015-12-14T14:45:03.891Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:03.892Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID B4:CE:F6:AB:A4:6A
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: B4:CE:F6:AB:A4:6A), either no such connection or failed to close the connection
I/jxcore-log( 3253): 2015-12-14T14:45:08.896Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:08.897Z SendDataConnector.js: Connect (retry count 2) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:08.897Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:08.898Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to null in address B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: null B4:CE:F6:AB:A4:6A
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to null in address B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: B4:CE:F6:AB:A4:6A)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address B4:CE:F6:AB:A4:6A (thread ID: 318)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 29
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 30
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 318)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 318)
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 31
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 32
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 318)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 318)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 33
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 34
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 318)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 318)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 35
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 36
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 318)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 318)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 37
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 38
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 318)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Maximum number of retries (5) reached, giving up... (thread ID: 318)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 318)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT164 B4:CE:F6:AB:A4:6A]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
I/jxcore-log( 3253): 2015-12-14T14:45:12.733Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:12.734Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:12.734Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3253): 2015-12-14T14:45:17.736Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:17.737Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [44:80:eb:7b:5a:05]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: XT1072
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:255
W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Incoming connection initialized (thread ID: 319)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Entering thread (ID: 319)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): onBytesRead: Read 81 bytes successfully (thread ID: 319)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Got valid identity from [44:80:EB:7B:5A:05 motorola-XT1072_PT9551 44:80:EB:7B:5A:05]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): onBytesWritten: 77 bytes successfully written (thread ID: 319)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): removeThreadFromList: Removing thread with ID 319
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Handshake thread disposed (thread ID: 319)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onIncomingConnectionConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT9551 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT9551 44:80:EB:7B:5A:05]
I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Incoming connection, peer ID: 44:80:EB:7B:5A:05, name: motorola-XT1072_PT9551, Bluetooth address: 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Exiting thread (ID: 319)
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Adding peer with ID 44:80:EB:7B:5A:05
I/jxcore-log( 3253): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"motorola-XT1072_PT9551","peerAvailable":true}]
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): Found peer : motorola-XT1072_PT9551, Available: true
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Incoming socket thread, for peer with ID 44:80:EB:7B:5A:05, created successfully
D/io.jxcore.node.ConnectionHelper( 3253): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3253): Entering thread (ID: 320)
,I/io.jxcore.node.IncomingSocketThread( 3253): Local host address: localhost/127.0.0.1, port: 60048
,I/jxcore-log( 3253): 2015-12-14T14:45:20.274Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3253): 
,D/io.jxcore.node.IncomingSocketThread( 3253): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3253): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3253): Exiting thread (ID: 320)
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 321, name: Sender)
I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 322, name: Receiver)
,I/jxcore-log( 3253): 2015-12-14T14:45:21.213Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.221Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.231Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.242Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.250Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.297Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.326Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.388Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.414Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.443Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.478Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.491Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.526Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.539Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.581Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.593Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.604Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.634Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.668Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.698Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.713Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.726Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.755Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.768Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.804Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.810Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.838Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.877Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.898Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:21.927Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:22.053Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:22.059Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:22.093Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:22.356Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:22.366Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:22.475Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3253): 
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID B4:CE:F6:AB:A4:6A
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: B4:CE:F6:AB:A4:6A), either no such connection or failed to close the connection
,I/jxcore-log( 3253): 2015-12-14T14:45:22.742Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:22.746Z SendDataConnector.js: Connect (retry count 3) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:22.749Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:22.751Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
,I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to null in address B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: null B4:CE:F6:AB:A4:6A
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to null in address B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: B4:CE:F6:AB:A4:6A)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address B4:CE:F6:AB:A4:6A (thread ID: 323)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2058): invalid rfc slot id: 8
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 322, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3253): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Incoming connection, peer with ID 44:80:EB:7B:5A:05 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 320
I/io.jxcore.node.IncomingSocketThread( 3253): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 322
I/io.jxcore.node.IncomingSocketThread( 3253): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 321
I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 321, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Incoming connection, peer with ID 44:80:EB:7B:5A:05 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3253): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 321, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 322, name: Receiver)
,I/jxcore-log( 3253): 2015-12-14T14:45:24.839Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3253): 
,W/bt-rfcomm( 2058): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 2058): RFCOMM_DisconnectInd LCID:0x42
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [b4:ce:f6:ab:a4:6a]: 0, 0, 0
E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 40
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 41
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 323)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 323)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 42
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:43, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 43
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 323)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 323)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: XT1072
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:44, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 44
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 45
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 323)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 323)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 46
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 47
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 323)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 323)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:48, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 48
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 49
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 323)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Maximum number of retries (5) reached, giving up... (thread ID: 323)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 323)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT164 B4:CE:F6:AB:A4:6A]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
,I/jxcore-log( 3253): 2015-12-14T14:45:30.442Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:30.445Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:30.448Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3253): 2015-12-14T14:45:35.455Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:35.455Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID B4:CE:F6:AB:A4:6A
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: B4:CE:F6:AB:A4:6A), either no such connection or failed to close the connection
I/jxcore-log( 3253): 2015-12-14T14:45:40.457Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:40.457Z SendDataConnector.js: Connect (retry count 4) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:40.457Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:40.457Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to null in address B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: null B4:CE:F6:AB:A4:6A
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to null in address B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: B4:CE:F6:AB:A4:6A)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address B4:CE:F6:AB:A4:6A (thread ID: 324)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2058): info:x10,
,D/        ( 2058): remote version info [b4:ce:f6:ab:a4:6a]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 50
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 51
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:52, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 52
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:53, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 53
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 54
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 55
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:56, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 56
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 57
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 58
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 59
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Maximum number of retries (5) reached, giving up... (thread ID: 324)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 324)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT164 B4:CE:F6:AB:A4:6A]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
I/jxcore-log( 3253): 2015-12-14T14:45:43.021Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:43.022Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): oneRoundDownNow
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:43.029Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3253): 
D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID B4:CE:F6:AB:A4:6A
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: B4:CE:F6:AB:A4:6A), either no such connection or failed to close the connection
,I/jxcore-log( 3253): 2015-12-14T14:45:43.032Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3253): 
I/jxcore-log( 3253): ---- round done--------
I/jxcore-log( 3253): 
I/jxcore-log( 3253): startWithNextDevice
I/jxcore-log( 3253): 
I/jxcore-log( 3253): device[2]: 7C:F9:0E:37:96:AB
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:43.040Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:43.041Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:43.041Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
,I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 325)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=1
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 2058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2058): Entering PendingCommandState State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
D/BluetoothAdapterProperties( 2058): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2058): StableState(): Entering Off State
W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onSocketConnected: Authenticating next: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3578 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 325)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): onBytesWritten: 77 bytes successfully written (thread ID: 326)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Outgoing connection initialized (*handshake* thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 325)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Entering thread (ID: 326)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): onBytesRead: Read 83 bytes successfully (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Handshake succeeded with [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3578 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onAuthenticated: Fully connected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3578 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Exiting thread (ID: 326)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3578 7C:F9:0E:37:96:AB]
I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Outgoing connection, peer ID: 7C:F9:0E:37:96:AB, name: samsung-SM-A500FU_PT3578, Bluetooth address: 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Outgoing socket thread, for peer with ID 7C:F9:0E:37:96:AB, created successfully
D/io.jxcore.node.ConnectionHelper( 3253): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3253): Entering thread (ID: 327)
D/io.jxcore.node.OutgoingSocketThread( 3253): Server socket local port: 51903
I/io.jxcore.node.OutgoingSocketThread( 3253): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3253): onListeningForIncomingConnections: Outgoing connection is using port 51903 (peer ID: 7C:F9:0E:37:96:AB)
I/jxcore-log( 3253): 2015-12-14T14:45:44.320Z SendDataConnector.js: CLIENT connected to 51903, error: null
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:44.321Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3253): 
,I/io.jxcore.node.OutgoingSocketThread( 3253): Incoming data from address: /127.0.0.1, port: 51903
D/io.jxcore.node.OutgoingSocketThread( 3253): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3253): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3253): Exiting thread (ID: 327)
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 329, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 328, name: Sender)
,I/jxcore-log( 3253): 2015-12-14T14:45:44.372Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3253): 
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3253): 2015-12-14T14:45:45.076Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3253): 
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:15796
,I/jxcore-log( 3253): 2015-12-14T14:45:45.118Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:45.126Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3253): 
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 3253): 2015-12-14T14:45:45.221Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:45.226Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:45.288Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:45.375Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:45:45.389Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3253): 2015-12-14T14:45:45.446Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3253): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/jxcore-log( 3253): 2015-12-14T14:45:45.468Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:45.483Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3253): 
I/jxcore-log( 3253): oneRoundDownNow
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:45.485Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:45.485Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3253): 
D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
I/io.jxcore.node.OutgoingSocketThread( 3253): close
I/io.jxcore.node.OutgoingSocketThread( 3253): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 329
I/io.jxcore.node.OutgoingSocketThread( 3253): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 328
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 328, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 329, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 328, name: Sender)
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 329, name: Receiver)
,I/jxcore-log( 3253): 2015-12-14T14:45:45.522Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): ---- round done--------
I/jxcore-log( 3253): 
I/jxcore-log( 3253): startWithNextDevice
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): device[3]: 34:FC:EF:9D:93:0B
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:45.524Z SendDataConnector.js: Start called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:45.524Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:45:45.524Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: Thali Test's G2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to null in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: null 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to null in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 330)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2058): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=0
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3253): Ignored { when=-14ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,W/bt-btm  ( 2058): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=2
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=1
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: A5-1
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 2058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2058): Entering PendingCommandState State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,W/bt-rfcomm( 2058): PORT_StartCnf failed result:5
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2058): invalid rfc slot id: 61
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,E/bt-btif ( 2058): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 9 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 2058): Failed to remove device: 34:FC:EF:9D:93:0B
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2058): StableState(): Entering Off State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
E/bt-btif ( 2058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2058): Entering PendingCommandState State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 2058): Failed to remove device: 7C:F9:0E:51:18:22
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2058): StableState(): Entering Off State
,E/BluetoothEventManager( 2728): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:255
W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Incoming connection initialized (thread ID: 331)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Waiting for incoming connections...
,W/bt-btif ( 2058): invalid rfc slot id: 39
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Entering thread (ID: 331)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Disconnected: bt socket closed, read return: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): removeThreadFromList: Removing thread with ID 331
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Handshake failed (thread ID: 331)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Exiting thread (ID: 331)
,W/bt-rfcomm( 2058): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 2058): RFCOMM_DisconnectInd LCID:0x4b
,W/bt-btif ( 2058): No ag scb for peer addr
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa405124c rs_disc_pending=0
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: Thali Test (Galaxy A5)
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Connection timeout
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: Thali Test (Galaxy A5)
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:255
W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Incoming connection initialized (thread ID: 332)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Entering thread (ID: 332)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): onBytesRead: Read 83 bytes successfully (thread ID: 332)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3493 7C:F9:0E:51:18:22]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): onBytesWritten: 77 bytes successfully written (thread ID: 332)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): removeThreadFromList: Removing thread with ID 332
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Handshake thread disposed (thread ID: 332)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3493 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Exiting thread (ID: 332)
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2058): dm_pm_timer expires
W/bt-btif ( 2058): dm_pm_timer expires 0
,W/bt-btif ( 2058): proc dm_pm_timer expires
,W/bt-btif ( 2058): invalid rfc slot id: 63
,W/bt-rfcomm( 2058): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 2058): RFCOMM_DisconnectInd LCID:0x4d
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: Thali Test (Galaxy A5)
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: Thali Test (Galaxy A5)
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:255
W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Incoming connection initialized (thread ID: 333)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Entering thread (ID: 333)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): onBytesRead: Read 83 bytes successfully (thread ID: 333)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3493 7C:F9:0E:51:18:22]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): onBytesWritten: 77 bytes successfully written (thread ID: 333)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): removeThreadFromList: Removing thread with ID 333
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Handshake thread disposed (thread ID: 333)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3493 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Exiting thread (ID: 333)
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2058): invalid rfc slot id: 64
,W/bt-rfcomm( 2058): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 2058): RFCOMM_DisconnectInd LCID:0x42
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: Thali Test (Galaxy A5)
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 62
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Cancelled: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 330)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 330)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3493 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3493 7C:F9:0E:51:18:22]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:9D:93:0B LGE-LG-D802_PT5671 34:FC:EF:9D:93:0B]
,I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Incoming connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT3493, Bluetooth address: 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:51:18:22
,I/jxcore-log( 3253): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT3493","peerAvailable":true}]
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : samsung-SM-A500FU_PT3493, Available: true
I/jxcore-log( 3253): 
,I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Incoming socket thread, for peer with ID 7C:F9:0E:51:18:22, created successfully
D/io.jxcore.node.ConnectionHelper( 3253): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Incoming connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT3493, Bluetooth address: 7C:F9:0E:51:18:22
,D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: We have an incoming connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 3253): onConnected: Already connected with peer (ID: 7C:F9:0E:51:18:22), continuing anyway...
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Incoming socket thread, for peer with ID 7C:F9:0E:51:18:22, created successfully
D/io.jxcore.node.ConnectionHelper( 3253): onConnected: The total number of connections is now 2
I/jxcore-log( 3253): 2015-12-14T14:46:50.935Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:46:50.935Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:46:50.935Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
D/io.jxcore.node.IncomingSocketThread( 3253): Entering thread (ID: 335)
D/io.jxcore.node.IncomingSocketThread( 3253): Entering thread (ID: 334)
I/io.jxcore.node.IncomingSocketThread( 3253): Local host address: localhost/127.0.0.1, port: 60048
D/io.jxcore.node.IncomingSocketThread( 3253): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/jxcore-log( 3253): 2015-12-14T14:46:50.952Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3253): 
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3253): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3253): Exiting thread (ID: 335)
I/io.jxcore.node.IncomingSocketThread( 3253): Local host address: localhost/127.0.0.1, port: 60048
D/io.jxcore.node.IncomingSocketThread( 3253): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3253): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3253): Exiting thread (ID: 334)
I/jxcore-log( 3253): 2015-12-14T14:46:50.956Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3253): 
I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 339, name: Receiver)
I/jxcore-log( 3253): 2015-12-14T14:46:50.959Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3253): 
I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 337, name: Receiver)
I/jxcore-log( 3253): 2015-12-14T14:46:50.963Z SendDataTCPServer.js: TCP/IP server has received 81920 bytes of data
I/jxcore-log( 3253): 
I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 336, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 338, name: Sender)
W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 338, thread name: Sender): Broken pipe
E/io.jxcore.node.IncomingSocketThread( 3253): The sending thread failed with error: Either failed to read from the output stream or write to the input stream: Broken pipe
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Either failed to read from the output stream or write to the input stream: Broken pipe
I/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 334
I/io.jxcore.node.IncomingSocketThread( 3253): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 339
I/io.jxcore.node.IncomingSocketThread( 3253): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 338
I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 339, name: Receiver)
W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 336, thread name: Sender): Broken pipe
E/io.jxcore.node.IncomingSocketThread( 3253): The sending thread failed with error: Either failed to read from the output stream or write to the input stream: Broken pipe
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Either failed to read from the output stream or write to the input stream: Broken pipe
I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3253): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 338, name: Sender)
I/jxcore-log( 3253): 2015-12-14T14:46:50.972Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 335
I/io.jxcore.node.IncomingSocketThread( 3253): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 337
I/io.jxcore.node.IncomingSocketThread( 3253): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 336
I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3253): closeBluetoothSocketAndStreams
I/jxcore-log( 3253): 2015-12-14T14:46:50.974Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3253): 
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 337, name: Receiver)
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 336, name: Sender)
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 330)
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: Thali Test (Galaxy A5)
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa405124c rs_disc_pending=1
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:255
W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Incoming connection initialized (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Entering thread (ID: 340)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): onBytesRead: Read 83 bytes successfully (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3493 7C:F9:0E:51:18:22]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): onBytesWritten: 77 bytes successfully written (thread ID: 340)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): removeThreadFromList: Removing thread with ID 340
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Handshake thread disposed (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3493 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3493 7C:F9:0E:51:18:22]
,I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Incoming connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT3493, Bluetooth address: 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
,I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Incoming socket thread, for peer with ID 7C:F9:0E:51:18:22, created successfully
D/io.jxcore.node.ConnectionHelper( 3253): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Exiting thread (ID: 340)
,D/io.jxcore.node.IncomingSocketThread( 3253): Entering thread (ID: 341)
,I/io.jxcore.node.IncomingSocketThread( 3253): Local host address: localhost/127.0.0.1, port: 60048
D/io.jxcore.node.IncomingSocketThread( 3253): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3253): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3253): Exiting thread (ID: 341)
,I/jxcore-log( 3253): 2015-12-14T14:46:52.680Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3253): 
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 343, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 342, name: Sender)
,I/jxcore-log( 3253): 2015-12-14T14:46:53.420Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.466Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.474Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.494Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.503Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.511Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.525Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.554Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.568Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.613Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.644Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.662Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.698Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.709Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.749Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.767Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.804Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.817Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.855Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.873Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.904Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.922Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.929Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.938Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.956Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.963Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:53.974Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:46:54.006Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3253): 
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa405124c rs_disc_pending=0
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2058): invalid rfc slot id: 65
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 343, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3253): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 341
I/io.jxcore.node.IncomingSocketThread( 3253): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 343
I/io.jxcore.node.IncomingSocketThread( 3253): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 342
I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 342, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3253): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 342, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 343, name: Receiver)
,I/jxcore-log( 3253): 2015-12-14T14:46:54.374Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3253): 
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa405124c rs_disc_pending=1
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2058): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 2058): RFCOMM_DisconnectInd LCID:0x41
,I/jxcore-log( 3253): 2015-12-14T14:46:55.936Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:46:55.937Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3253): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Cannot start, because not initialized
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT5202 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT5202, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: , Wi-Fi Direct address: f4:f1:e1:5c:43:c8
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Adding peer with ID F4:F1:E1:5C:3B:E2
I/jxcore-log( 3253): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"motorola-XT1039_PT5202","peerAvailable":true}]
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : motorola-XT1039_PT5202, Available: true
I/jxcore-log( 3253): 
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
I/jxcore-log( 3253): 2015-12-14T14:47:00.941Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:47:00.942Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:47:00.948Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:47:00.951Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
,I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: Thali Test's G2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: Thali Test's G2 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 344)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT5202 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT5202, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: , Wi-Fi Direct address: f4:f1:e1:5c:43:c8
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT652","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT652 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT652","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT652","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT652","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT652, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: Thali Test (Galaxy A3), Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Adding peer with ID 08:EC:A9:50:76:27
I/jxcore-log( 3253): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT652","peerAvailable":true}]
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : samsung-SM-A300FU_PT652, Available: true
I/jxcore-log( 3253): 
,W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9795","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT9795 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9795","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9795","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9795","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: F8:95:C7:87:85:54, peer name: LGE-LG-D722_PT9795, peer ID: F8:95:C7:87:85:54, Wi-Fi Direct device name: , Wi-Fi Direct address: a2:39:f7:70:12:80
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Adding peer with ID F8:95:C7:87:85:54
I/jxcore-log( 3253): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT9795","peerAvailable":true}]
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : LGE-LG-D722_PT9795, Available: true
I/jxcore-log( 3253): 
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT8535 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT8535, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Adding peer with ID 00:F4:6F:30:E0:6C
I/jxcore-log( 3253): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"samsung-SM-G800F_PT8535","peerAvailable":true}]
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : samsung-SM-G800F_PT8535, Available: true
I/jxcore-log( 3253): 
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Connection timeout
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x22  CID 0x40
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 67
,E/bt-btif ( 2058): Do not find the bg connection mask for the remote device
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapService( 2058): onReceive
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: Thali Test's G2
,W/bt-btif ( 2058): No ag scb for peer addr
,I/ActivityManager(  736): Killing 2248:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10070/pid_2248/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Cancelled: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 344)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 344)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: true
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:9D:93:0B LGE-LG-D802_PT5671 34:FC:EF:9D:93:0B]
,W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/jxcore-log( 3253): 2015-12-14T14:48:33.071Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:48:33.071Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:48:33.073Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local services cleared successfully
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 344)
,I/jxcore-log( 3253): 2015-12-14T14:48:38.075Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:48:38.075Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
I/jxcore-log( 3253): 2015-12-14T14:48:43.080Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:48:43.081Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:48:43.081Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:48:43.082Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
,I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: Thali Test's G2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: Thali Test's G2 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 345)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Connection timeout
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x22  CID 0x45
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 69
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x9  CID 0x46
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 70
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 345)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 345)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:9D:93:0B LGE-LG-D802_PT5671 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/jxcore-log( 3253): 2015-12-14T14:49:14.478Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:49:14.478Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:49:14.478Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
,W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 345)
,I/jxcore-log( 3253): 2015-12-14T14:49:19.479Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:49:19.480Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3253): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
I/jxcore-log( 3253): 2015-12-14T14:49:24.486Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:49:24.487Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:49:24.489Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:49:24.489Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: Thali Test's G2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: Thali Test's G2 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 346)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5671"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT5671 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5671"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT5671, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: , Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x9  CID 0x47
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:71, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 71
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x9  CID 0x43
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:72, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 72
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 346)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 346)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x9  CID 0x48
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:73, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 73
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x9  CID 0x4a
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:74, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 74
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 346)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 346)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x9  CID 0x4b
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:75, failed to find channle,                                       status:1, scn:0
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,W/bt-btif ( 2058): invalid rfc slot id: 75
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3253): Connected to the server!
I/jxcore-log( 3253): 
,I/chromium( 3253): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Connection timeout
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x22  CID 0x4c
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 76
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 346)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 346)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:9D:93:0B LGE-LG-D802_PT5671 34:FC:EF:9D:93:0B]
,I/jxcore-log( 3253): 2015-12-14T14:50:04.535Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:50:04.536Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:50:04.536Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 346)
,I/jxcore-log( 3253): 2015-12-14T14:50:09.537Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:50:09.537Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3253): 
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
,I/jxcore-log( 3253): 2015-12-14T14:50:14.542Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:50:14.548Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:50:14.551Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:50:14.556Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: Thali Test's G2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: Thali Test's G2 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 347)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x9  CID 0x4d
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:77, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 77
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x9  CID 0x4e
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:78, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 78
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 347)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 347)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x9  CID 0x42
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:79, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 79
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x9  CID 0x49
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:80, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 80
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 347)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 347)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x9  CID 0x4f
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:81, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 81
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Connection timeout
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  736): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3708 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3708): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3708):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3708):   adb logcat -s GAv4
,W/GAv4    ( 3708): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3708): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3708): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  736): Killing 1947:com.google.android.calendar/u0a31 (adj 15): empty #17
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/libprocessgroup(  736): failed to open /acct/uid_10031/pid_1947/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x22  CID 0x41
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:82, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2058): invalid rfc slot id: 82
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 347)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 347)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:9D:93:0B LGE-LG-D802_PT5671 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: Note3-1 ea:50:8b:de:28:a3
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 9: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: Note3-1 ea:50:8b:de:28:a3
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 9: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 9: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 9: S5mini-1 02:f4:6f:30:e0:6d
,I/jxcore-log( 3253): 2015-12-14T14:50:58.242Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:50:58.243Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): oneRoundDownNow
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:50:58.243Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3253): 
D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
I/jxcore-log( 3253): 2015-12-14T14:50:58.243Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3253): 
I/jxcore-log( 3253): ---- round done--------
I/jxcore-log( 3253): 
I/jxcore-log( 3253): startWithNextDevice
I/jxcore-log( 3253): 
I/jxcore-log( 3253): device[4]: 44:80:EB:7B:5A:05
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:50:58.244Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:50:58.244Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:50:58.244Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: XT1072 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 348)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 9: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 9: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 9: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 9: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 9: S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 347)
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:83, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 83
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:84, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 84
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 348)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 348)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [44:80:eb:7b:5a:05]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: XT1072
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onSocketConnected: Authenticating next: [44:80:EB:7B:5A:05 motorola-XT1072_PT9551 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Socket connection succeeded using port (1), total number of attempts: 2 (thread ID: 348)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): onBytesWritten: 77 bytes successfully written (thread ID: 349)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Outgoing connection initialized (*handshake* thread ID: 349)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 348)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Entering thread (ID: 349)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): onBytesRead: Read 81 bytes successfully (thread ID: 349)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT9551 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onAuthenticated: Fully connected: [44:80:EB:7B:5A:05 motorola-XT1072_PT9551 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT9551 44:80:EB:7B:5A:05]
I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Outgoing connection, peer ID: 44:80:EB:7B:5A:05, name: motorola-XT1072_PT9551, Bluetooth address: 44:80:EB:7B:5A:05
,D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 44:80:EB:7B:5A:05 already in the list
,I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Outgoing socket thread, for peer with ID 44:80:EB:7B:5A:05, created successfully
D/io.jxcore.node.ConnectionHelper( 3253): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Exiting thread (ID: 349)
,D/io.jxcore.node.OutgoingSocketThread( 3253): Entering thread (ID: 350)
,D/io.jxcore.node.OutgoingSocketThread( 3253): Server socket local port: 44701
I/io.jxcore.node.OutgoingSocketThread( 3253): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3253): onListeningForIncomingConnections: Outgoing connection is using port 44701 (peer ID: 44:80:EB:7B:5A:05)
,I/jxcore-log( 3253): 2015-12-14T14:51:13.212Z SendDataConnector.js: CLIENT connected to 44701, error: null
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:51:13.215Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3253): 
,I/io.jxcore.node.OutgoingSocketThread( 3253): Incoming data from address: /127.0.0.1, port: 44701
D/io.jxcore.node.OutgoingSocketThread( 3253): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3253): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3253): Exiting thread (ID: 350)
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 352, name: Receiver)
,I/jxcore-log( 3253): 2015-12-14T14:51:13.256Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3253): 
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 351, name: Sender)
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3253): 2015-12-14T14:51:13.956Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3253): 
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:17776
,I/jxcore-log( 3253): 2015-12-14T14:51:14.050Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:51:14.104Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3253): 
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7876
,I/jxcore-log( 3253): 2015-12-14T14:51:14.208Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:51:14.279Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:51:14.377Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:51:14.506Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:51:14.569Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:51:14.578Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:51:15.207Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:51:15.208Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3253): 
I/jxcore-log( 3253): oneRoundDownNow
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:51:15.209Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:51:15.210Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3253): 
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 44:80:EB:7B:5A:05
I/io.jxcore.node.OutgoingSocketThread( 3253): close
I/io.jxcore.node.OutgoingSocketThread( 3253): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 352
I/io.jxcore.node.OutgoingSocketThread( 3253): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 351
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 351, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Outgoing connection, peer with ID 44:80:EB:7B:5A:05 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3253): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 352, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Outgoing connection, peer with ID 44:80:EB:7B:5A:05 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Successfully disconnected (peer ID: 44:80:EB:7B:5A:05
,E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 352, name: Receiver)
,W/bt-btif ( 2058): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 351, name: Sender)
,I/jxcore-log( 3253): 2015-12-14T14:51:15.269Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3253): 
I/jxcore-log( 3253): ---- round done--------
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): startWithNextDevice
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): device[5]: 7C:F9:0E:51:18:22
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:51:15.278Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:51:15.279Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:51:15.280Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 353)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: XT1072
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Connection timeout
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [7c:f9:0e:51:18:22]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: Thali Test (Galaxy A5)
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onSocketConnected: Authenticating next: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3493 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 353)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 353)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3493 7C:F9:0E:51:18:22]
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3253): 2015-12-14T14:51:48.915Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:51:48.915Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:51:48.917Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,W/bt-btif ( 2058): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT8535 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT8535, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/jxcore-log( 3253): 2015-12-14T14:51:53.919Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:51:53.920Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3251","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3251 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT3251, peer ID: E0:DB:10:14:E2:C0, Wi-Fi Direct device name: , Wi-Fi Direct address: 92:b6:86:43:73:1c
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Adding peer with ID E0:DB:10:14:E2:C0
I/jxcore-log( 3253): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT3251","peerAvailable":true}]
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : samsung-SM-N910C_PT3251, Available: true
I/jxcore-log( 3253): 
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
,D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
,I/jxcore-log( 3253): 2015-12-14T14:51:58.935Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:51:58.936Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:51:58.936Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:51:58.937Z SendDataConnector.js: do connect now
,I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 354)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: Thali Test (Galaxy A5)
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onSocketConnected: Authenticating next: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3493 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 354)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): onBytesWritten: 77 bytes successfully written (thread ID: 355)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Outgoing connection initialized (*handshake* thread ID: 355)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 354)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Entering thread (ID: 355)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): onBytesRead: Read 83 bytes successfully (thread ID: 355)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3493 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onAuthenticated: Fully connected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3493 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3493 7C:F9:0E:51:18:22]
,I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Outgoing connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT3493, Bluetooth address: 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
,I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Outgoing socket thread, for peer with ID 7C:F9:0E:51:18:22, created successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Exiting thread (ID: 355)
,D/io.jxcore.node.ConnectionHelper( 3253): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3253): Entering thread (ID: 356)
,D/io.jxcore.node.OutgoingSocketThread( 3253): Server socket local port: 43765
I/io.jxcore.node.OutgoingSocketThread( 3253): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3253): onListeningForIncomingConnections: Outgoing connection is using port 43765 (peer ID: 7C:F9:0E:51:18:22)
I/jxcore-log( 3253): 2015-12-14T14:52:00.010Z SendDataConnector.js: CLIENT connected to 43765, error: null
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:52:00.010Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3253): 
,I/io.jxcore.node.OutgoingSocketThread( 3253): Incoming data from address: /127.0.0.1, port: 43765
D/io.jxcore.node.OutgoingSocketThread( 3253): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3253): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3253): Exiting thread (ID: 356)
,I/jxcore-log( 3253): 2015-12-14T14:52:00.035Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3253): 
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 357, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 358, name: Receiver)
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3253): 2015-12-14T14:52:00.934Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:52:00.964Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3253): 
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11836
,I/jxcore-log( 3253): 2015-12-14T14:52:01.011Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3253): 
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4906
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2926
,I/jxcore-log( 3253): 2015-12-14T14:52:01.059Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:52:01.066Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:52:01.121Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:52:01.167Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:52:01.202Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:52:01.413Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:52:01.520Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:52:01.520Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3253): 
I/jxcore-log( 3253): oneRoundDownNow
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:52:01.522Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:52:01.526Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3253): 
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 3253): close
I/io.jxcore.node.OutgoingSocketThread( 3253): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 358
I/io.jxcore.node.OutgoingSocketThread( 3253): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 357
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 357, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 358, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:51:18:22
,E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
,D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 357, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 358, name: Receiver)
,I/jxcore-log( 3253): 2015-12-14T14:52:01.578Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3253): 
I/jxcore-log( 3253): ---- round done--------
I/jxcore-log( 3253): 
I/jxcore-log( 3253): startWithNextDevice
I/jxcore-log( 3253): 
I/jxcore-log( 3253): device[6]: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:52:01.581Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:52:01.582Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:52:01.590Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
,I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: null F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 359)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2058): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9551","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT9551 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
,I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT9551, peer ID: 44:80:EB:7B:5A:05, Wi-Fi Direct device name: , Wi-Fi Direct address: 44:80:eb:7b:5a:07
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 44:80:EB:7B:5A:05 already in the list
,W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3493","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3493 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT3493, peer ID: 7C:F9:0E:51:18:22, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:51:18:23
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3578","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3578 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: samsung-SM-A500FU_PT3578, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:37:96:ac
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Connection timeout
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 2058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2058): Entering PendingCommandState State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 2058): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2058): StableState(): Entering Off State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Cancelled: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1076"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT1076 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Cancelled: Connection timeout [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT5202 F4:F1:E1:5C:3B:E2]
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 34:FC:EF:11:B1:66, peer name: LGE-Nexus 5_PT1076, peer ID: 34:FC:EF:11:B1:66, Wi-Fi Direct device name: , Wi-Fi Direct address: 52:55:27:f0:ff:f0
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Adding peer with ID 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onSocketConnected: Authenticating next: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT5202 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 359)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 359)
,I/jxcore-log( 3253): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:B1:66","peerName":"LGE-Nexus 5_PT1076","peerAvailable":true}]
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): Found peer : LGE-Nexus 5_PT1076, Available: true
I/jxcore-log( 3253): 
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 6 peer(s), but doing nothing with that list
,I/jxcore-log( 3253): 2015-12-14T14:52:22.430Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:52:22.431Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:52:22.432Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
,W/bt-btif ( 2058): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: XT1039
,I/jxcore-log( 3253): 2015-12-14T14:52:27.440Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:52:27.441Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3253): 
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8079","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT8079 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 7 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT8079, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: A3-1, Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Adding peer with ID 08:EC:A9:50:75:41
I/jxcore-log( 3253): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT8079","peerAvailable":true}]
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : samsung-SM-A300FU_PT8079, Available: true
I/jxcore-log( 3253): 
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 7 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5184","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5184 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 8 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT5184, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: G3-1, Wi-Fi Direct address: 02:9a:02:7b:60:ac
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Adding peer with ID 58:3F:54:73:64:C0
,I/jxcore-log( 3253): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"LGE-LG-D855_PT5184","peerAvailable":true}]
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : LGE-LG-D855_PT5184, Available: true
I/jxcore-log( 3253): 
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 3253): 2015-12-14T14:52:32.448Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:52:32.448Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:52:32.449Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:52:32.449Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 360)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:89, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 89
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:90, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 90
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 360)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 360)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Connection timeout
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:91, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2058): invalid rfc slot id: 91
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0xd  CID 0x41
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:92, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 92
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 360)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 360)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Cancelled: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Cancelled: Connection timeout [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT5202 F4:F1:E1:5C:3B:E2]
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/jxcore-log( 3253): 2015-12-14T14:52:58.742Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:52:58.742Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:52:58.742Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 360)
,I/jxcore-log( 3253): 2015-12-14T14:53:03.744Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:53:03.746Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Android_2dc2 52:55:27:f0:ff:f0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Android_2dc2 52:55:27:f0:ff:f0
,D/WifiP2pManager( 3253): Ignored { when=-12ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3253): Ignored { when=-11ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
,I/jxcore-log( 3253): 2015-12-14T14:53:08.752Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:53:08.758Z SendDataConnector.js: Connect (retry count 2) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:53:08.761Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:53:08.764Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
,I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 361)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onSocketConnected: Authenticating next: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT5202 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 361)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): onBytesWritten: 77 bytes successfully written (thread ID: 362)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Outgoing connection initialized (*handshake* thread ID: 362)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 361)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Entering thread (ID: 362)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): onBytesRead: Read 81 bytes successfully (thread ID: 362)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Handshake succeeded with [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT5202 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onAuthenticated: Fully connected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT5202 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Exiting thread (ID: 362)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT5202 F4:F1:E1:5C:3B:E2]
I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Outgoing connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT5202, Bluetooth address: F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Outgoing socket thread, for peer with ID F4:F1:E1:5C:3B:E2, created successfully
D/io.jxcore.node.ConnectionHelper( 3253): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3253): Entering thread (ID: 363)
D/io.jxcore.node.OutgoingSocketThread( 3253): Server socket local port: 54053
I/io.jxcore.node.OutgoingSocketThread( 3253): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3253): onListeningForIncomingConnections: Outgoing connection is using port 54053 (peer ID: F4:F1:E1:5C:3B:E2)
,I/jxcore-log( 3253): 2015-12-14T14:53:10.799Z SendDataConnector.js: CLIENT connected to 54053, error: null
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:53:10.800Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3253): 
,I/io.jxcore.node.OutgoingSocketThread( 3253): Incoming data from address: /127.0.0.1, port: 54053
D/io.jxcore.node.OutgoingSocketThread( 3253): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3253): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3253): Exiting thread (ID: 363)
,I/jxcore-log( 3253): 2015-12-14T14:53:10.826Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3253): 
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 364, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 365, name: Receiver)
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3253): 2015-12-14T14:53:13.952Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:53:15.346Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3253): 
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 3253): 2015-12-14T14:53:16.267Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3253): 
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa40517a4 rs_disc_pending=0
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3253): 2015-12-14T14:53:17.317Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3253): 
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3253): 2015-12-14T14:53:17.426Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:53:17.559Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:53:17.622Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:53:17.704Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:53:17.894Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:53:17.944Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:53:17.944Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3253): 
I/jxcore-log( 3253): oneRoundDownNow
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:53:17.946Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:53:17.947Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3253): 
D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F4:F1:E1:5C:3B:E2
I/io.jxcore.node.OutgoingSocketThread( 3253): close
I/io.jxcore.node.OutgoingSocketThread( 3253): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 365
I/io.jxcore.node.OutgoingSocketThread( 3253): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 364
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 364, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Outgoing connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local output stream...
,I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 365, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Outgoing connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Successfully disconnected (peer ID: F4:F1:E1:5C:3B:E2
,E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 365, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 364, name: Sender)
,W/bt-btif ( 2058): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,I/jxcore-log( 3253): 2015-12-14T14:53:17.999Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3253): 
I/jxcore-log( 3253): ---- round done--------
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): startWithNextDevice
I/jxcore-log( 3253): 
I/jxcore-log( 3253): device[7]: 08:EC:A9:50:76:27
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:53:18.000Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:53:18.000Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:53:18.000Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: Thali Test (Galaxy A3)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 366)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa40517a4 rs_disc_pending=1
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:94, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 94
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:95, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 95
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 366)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 366)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Connection timeout
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:96, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 96
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/ActivityManager(  736): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3807 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 3807): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3807): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 1571): Explicit concurrent mark sweep GC freed 53255(3MB) AllocSpace objects, 10(160KB) LOS objects, 39% free, 21MB/36MB, paused 10.700ms total 75.608ms
,V/JNIHelp ( 3807): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 3807): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3807): Installed default security provider GmsCore_OpenSSL
,I/PhenotypeConfigurator( 1571): Scheduling Phenotype for one-off execution 10979 seconds from now (1450104818584)
,D/GetConfigurationSnapshotOperation( 1571): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1571): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1571): Using platform SSLCertificateSocketFactory
,E/YouTube MDX( 3807): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 3863): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1813626220.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads1813626220.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3863): dex2oat took 39.502ms (threads: 4)
,W/InstanceID/Rpc( 3807): Found 10008
,I/ActivityManager(  736): Killing 2846:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10002/pid_2846/cgroup.procs: No such file or directory
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 2058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2058): Entering PendingCommandState State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 2058): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2058): StableState(): Entering Off State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onSocketConnected: Authenticating next: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT652 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Cancelled: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:76:27 samsung-SM-A300FU_PT652 08:EC:A9:50:76:27]
,I/jxcore-log( 3253): 2015-12-14T14:53:42.017Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 3253): 
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/jxcore-log( 3253): 2015-12-14T14:53:42.017Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:53:42.019Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Socket connection succeeded using system decided port, total number of attempts: 2 (thread ID: 366)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 366)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/bt-btif ( 2058): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 3253): 2015-12-14T14:53:47.020Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:53:47.021Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3253): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT8535 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT8535, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT5202 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT5202, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: , Wi-Fi Direct address: f4:f1:e1:5c:43:c8
,I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8079","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT8079 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8079","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8079","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT8079, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: , Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 3253): 2015-12-14T14:53:52.026Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:53:52.026Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:53:52.027Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:53:52.027Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: Thali Test (Galaxy A3)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: Thali Test (Galaxy A3) 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 367)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT5202 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT5202, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: , Wi-Fi Direct address: f4:f1:e1:5c:43:c8
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8079","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8079","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8079","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Connection timeout
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x8  CID 0x4a
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:98, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 98
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:99, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 99
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 367)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:76:27 samsung-SM-A300FU_PT652 08:EC:A9:50:76:27]
,I/jxcore-log( 3253): 2015-12-14T14:54:27.993Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:54:27.994Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:54:27.994Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:54:32.995Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:54:32.996Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3253): 
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 3253): 2015-12-14T14:54:38.000Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:54:38.000Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:54:38.001Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:54:38.002Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
,I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: Thali Test (Galaxy A3)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: Thali Test (Galaxy A3) 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 368)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:100, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 100
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onSocketConnected: Authenticating next: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT652 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 368)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): onBytesWritten: 77 bytes successfully written (thread ID: 369)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Outgoing connection initialized (*handshake* thread ID: 369)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 368)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Entering thread (ID: 369)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): onBytesRead: Read 82 bytes successfully (thread ID: 369)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Handshake succeeded with [08:EC:A9:50:76:27 samsung-SM-A300FU_PT652 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onAuthenticated: Fully connected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT652 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT652 08:EC:A9:50:76:27]
I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT652, Bluetooth address: 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
,I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Outgoing socket thread, for peer with ID 08:EC:A9:50:76:27, created successfully
D/io.jxcore.node.ConnectionHelper( 3253): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Exiting thread (ID: 369)
,D/io.jxcore.node.OutgoingSocketThread( 3253): Entering thread (ID: 370)
,D/io.jxcore.node.OutgoingSocketThread( 3253): Server socket local port: 60101
I/io.jxcore.node.OutgoingSocketThread( 3253): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3253): onListeningForIncomingConnections: Outgoing connection is using port 60101 (peer ID: 08:EC:A9:50:76:27)
I/jxcore-log( 3253): 2015-12-14T14:54:44.489Z SendDataConnector.js: CLIENT connected to 60101, error: null
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:54:44.490Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3253): 
,I/io.jxcore.node.OutgoingSocketThread( 3253): Incoming data from address: /127.0.0.1, port: 60101
D/io.jxcore.node.OutgoingSocketThread( 3253): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3253): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3253): Exiting thread (ID: 370)
,I/jxcore-log( 3253): 2015-12-14T14:54:44.515Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3253): 
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 371, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 372, name: Receiver)
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11836
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: true
,W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
,W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,W/bt-btif ( 2058): dm_pm_timer expires
,W/bt-btif ( 2058): dm_pm_timer expires 0
,W/bt-btif ( 2058): proc dm_pm_timer expires
,I/art     (  736): Explicit concurrent mark sweep GC freed 82774(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 1.028ms total 102.846ms
,I/jxcore-log( 3253): 2015-12-14T14:54:51.545Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:54:51.545Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3253): 
I/jxcore-log( 3253): oneRoundDownNow
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:54:51.546Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:54:51.546Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3253): 
D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 3253): close
I/io.jxcore.node.OutgoingSocketThread( 3253): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 372
I/io.jxcore.node.OutgoingSocketThread( 3253): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 371
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 371, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:76:27 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 372, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:76:27 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:76:27
,E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 371, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 372, name: Receiver)
,I/jxcore-log( 3253): 2015-12-14T14:54:51.552Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3253): 
I/jxcore-log( 3253): ---- round done--------
I/jxcore-log( 3253): 
I/jxcore-log( 3253): startWithNextDevice
I/jxcore-log( 3253): 
I/jxcore-log( 3253): device[8]: F8:95:C7:87:85:54
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:54:51.553Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:54:51.554Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:54:51.554Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: null F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 373)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa405196c rs_disc_pending=1
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2058): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2058): Entering PendingCommandState State
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
E/BluetoothEventManager( 2728): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2058): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2058): StableState(): Entering Off State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onSocketConnected: Authenticating next: [F8:95:C7:87:85:54 LGE-LG-D722_PT9795 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 373)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): onBytesWritten: 77 bytes successfully written (thread ID: 374)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Outgoing connection initialized (*handshake* thread ID: 374)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 373)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Entering thread (ID: 374)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): onBytesRead: Read 77 bytes successfully (thread ID: 374)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Handshake succeeded with [F8:95:C7:87:85:54 LGE-LG-D722_PT9795 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onAuthenticated: Fully connected: [F8:95:C7:87:85:54 LGE-LG-D722_PT9795 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Exiting thread (ID: 374)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT9795 F8:95:C7:87:85:54]
I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Outgoing connection, peer ID: F8:95:C7:87:85:54, name: LGE-LG-D722_PT9795, Bluetooth address: F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Outgoing socket thread, for peer with ID F8:95:C7:87:85:54, created successfully
D/io.jxcore.node.ConnectionHelper( 3253): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 3253): Entering thread (ID: 375)
D/io.jxcore.node.OutgoingSocketThread( 3253): Server socket local port: 35088
I/io.jxcore.node.OutgoingSocketThread( 3253): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3253): onListeningForIncomingConnections: Outgoing connection is using port 35088 (peer ID: F8:95:C7:87:85:54)
I/jxcore-log( 3253): 2015-12-14T14:54:55.817Z SendDataConnector.js: CLIENT connected to 35088, error: null
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:54:55.818Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3253): 
,I/io.jxcore.node.OutgoingSocketThread( 3253): Incoming data from address: /127.0.0.1, port: 35088
D/io.jxcore.node.OutgoingSocketThread( 3253): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 3253): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3253): Exiting thread (ID: 375)
,I/jxcore-log( 3253): 2015-12-14T14:54:55.850Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3253): 
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 376, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 377, name: Receiver)
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa405196c rs_disc_pending=1
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3253): 2015-12-14T14:54:56.466Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:54:56.555Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:54:56.621Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:54:56.690Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:54:56.781Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:54:56.793Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:54:56.872Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3253): 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3253): 2015-12-14T14:54:56.991Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3253): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/jxcore-log( 3253): 2015-12-14T14:54:57.093Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3253): 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3253): 2015-12-14T14:54:57.218Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:54:57.218Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3253): 
I/jxcore-log( 3253): oneRoundDownNow
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:54:57.218Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:54:57.218Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3253): 
D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:85:54
I/io.jxcore.node.OutgoingSocketThread( 3253): close
I/io.jxcore.node.OutgoingSocketThread( 3253): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 377
I/io.jxcore.node.OutgoingSocketThread( 3253): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 376
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 376, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Outgoing connection, peer with ID F8:95:C7:87:85:54 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 377, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Outgoing connection, peer with ID F8:95:C7:87:85:54 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:85:54
,E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 376, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 377, name: Receiver)
,I/jxcore-log( 3253): 2015-12-14T14:54:57.237Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3253): 
I/jxcore-log( 3253): ---- round done--------
I/jxcore-log( 3253): 
I/jxcore-log( 3253): startWithNextDevice
I/jxcore-log( 3253): 
I/jxcore-log( 3253): device[9]: 00:F4:6F:30:E0:6C
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:54:57.241Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:54:57.242Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:54:57.245Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
,I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: S5mini-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 378)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,W/bt-btif ( 2058): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3253): Ignored { when=-10ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa405196c rs_disc_pending=1
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa4051cfc rs_disc_pending=0
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
,E/bt-btif ( 2058): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 2058): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2058): Entering PendingCommandState State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: G3s-1
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 2058): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2058): StableState(): Entering Off State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Connection timeout
,W/bt-btif ( 2058): invalid rfc slot id: 103
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa4051cfc rs_disc_pending=1
,E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:104, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 104
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,W/bt-l2cap( 2058): L2CAP got sec_comp for unknown BD_ADDR
,W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 378)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 378)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): stop: Stopping services
,D/BluetoothMapService( 2058): onReceive
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: true
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Cancelled: Connection timeout [00:F4:6F:30:E0:6C samsung-SM-G800F_PT8535 00:F4:6F:30:E0:6C]
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/jxcore-log( 3253): 2015-12-14T14:56:11.611Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:56:11.611Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 00:F4:6F:30:E0:6C failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:56:11.611Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local service added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
I/BluetoothClassifier( 1382): Bluetooth Device Name: S5mini-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 378)
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/jxcore-log( 3253): 2015-12-14T14:56:16.612Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:56:16.612Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,D/WifiP2pManager( 3253): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 7 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 7 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 3253): 2015-12-14T14:56:21.617Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:56:21.618Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:56:21.618Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:56:21.619Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: S5mini-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 379)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [00:f4:6f:30:e0:6c]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
E/bt-btif ( 2058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2058): Entering PendingCommandState State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 2058): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2058): StableState(): Entering Off State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onSocketConnected: Authenticating next: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT8535 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 379)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): onBytesWritten: 77 bytes successfully written (thread ID: 380)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Outgoing connection initialized (*handshake* thread ID: 380)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 379)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Entering thread (ID: 380)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): onBytesRead: Read 82 bytes successfully (thread ID: 380)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT8535 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onAuthenticated: Fully connected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT8535 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Exiting thread (ID: 380)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT8535 00:F4:6F:30:E0:6C]
I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Outgoing connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT8535, Bluetooth address: 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
,I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Outgoing socket thread, for peer with ID 00:F4:6F:30:E0:6C, created successfully
D/io.jxcore.node.ConnectionHelper( 3253): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3253): Entering thread (ID: 381)
D/io.jxcore.node.OutgoingSocketThread( 3253): Server socket local port: 57148
,I/io.jxcore.node.OutgoingSocketThread( 3253): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3253): onListeningForIncomingConnections: Outgoing connection is using port 57148 (peer ID: 00:F4:6F:30:E0:6C)
,I/jxcore-log( 3253): 2015-12-14T14:56:28.196Z SendDataConnector.js: CLIENT connected to 57148, error: null
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:56:28.197Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3253): 
,I/io.jxcore.node.OutgoingSocketThread( 3253): Incoming data from address: /127.0.0.1, port: 57148
D/io.jxcore.node.OutgoingSocketThread( 3253): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3253): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3253): Exiting thread (ID: 381)
,I/jxcore-log( 3253): 2015-12-14T14:56:28.221Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3253): 
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 383, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 382, name: Sender)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT3132"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [38:94:96:B5:06:DC samsung-SM-G800H_PT3132 38:94:96:B5:06:DC]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT3132"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT3132"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT3132"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT3132"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT3132"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 38:94:96:B5:06:DC, peer name: samsung-SM-G800H_PT3132, peer ID: 38:94:96:B5:06:DC, Wi-Fi Direct device name: Galaxy S5-2, Wi-Fi Direct address: 3a:94:96:b5:06:dd
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Adding peer with ID 38:94:96:B5:06:DC
I/jxcore-log( 3253): peerAvailabilityChanged [{"peerIdentifier":"38:94:96:B5:06:DC","peerName":"samsung-SM-G800H_PT3132","peerAvailable":true}]
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : samsung-SM-G800H_PT3132, Available: true
I/jxcore-log( 3253): 
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/jxcore-log( 3253): 2015-12-14T14:56:29.300Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:56:29.732Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:56:30.301Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:56:31.316Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3253): 
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3253): 2015-12-14T14:56:31.703Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:56:32.095Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:56:32.401Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:56:32.464Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:56:32.735Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:56:33.012Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:56:33.013Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3253): 
I/jxcore-log( 3253): oneRoundDownNow
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:56:33.014Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:56:33.015Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3253): 
D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 3253): close
I/io.jxcore.node.OutgoingSocketThread( 3253): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 383
I/io.jxcore.node.OutgoingSocketThread( 3253): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 382
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 382, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Outgoing connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3253): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 383, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Outgoing connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:F4:6F:30:E0:6C
,E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
,D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 383, name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 382, name: Sender)
,I/jxcore-log( 3253): 2015-12-14T14:56:33.061Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): ---- round done--------
I/jxcore-log( 3253): 
I/jxcore-log( 3253): startWithNextDevice
I/jxcore-log( 3253): 
I/jxcore-log( 3253): device[10]: E0:DB:10:14:E2:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:56:33.062Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:56:33.062Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:56:33.062Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: null E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to null in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 384)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2058): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa4051cfc rs_disc_pending=1
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa4051cfc rs_disc_pending=0
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:106, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 106
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:107, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 107
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 384)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 384)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Connection timeout
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:108, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 108
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:109, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 109
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Cancelled: Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Cancelled: Connection timeout [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3251 E0:DB:10:14:E2:C0]
I/jxcore-log( 3253): 2015-12-14T14:56:54.459Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:56:54.460Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:56:54.460Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 384)
,I/jxcore-log( 3253): 2015-12-14T14:56:59.462Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:56:59.464Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3253): 
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: E0:DB:10:14:E2:C0), either no such connection or failed to close the connection
I/jxcore-log( 3253): 2015-12-14T14:57:04.468Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:57:04.468Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:57:04.469Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:57:04.470Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: null E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to null in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 385)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:110, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 110
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:111, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 111
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 385)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 385)
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 2058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2058): Entering PendingCommandState State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2058): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2058): StableState(): Entering Off State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa405208c rs_disc_pending=1
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:255
W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Incoming connection initialized (thread ID: 386)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Entering thread (ID: 386)
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa405208c rs_disc_pending=0
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Connection timeout
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): onBytesRead: Read 82 bytes successfully (thread ID: 386)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Got valid identity from [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8970 7C:F9:0E:34:8A:A0]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): onBytesWritten: 77 bytes successfully written (thread ID: 386)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): removeThreadFromList: Removing thread with ID 386
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Handshake thread disposed (thread ID: 386)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onIncomingConnectionConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8970 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Exiting thread (ID: 386)
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:112, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 112
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa405208c rs_disc_pending=1
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:114, failed to find channle,                                       status:1, scn:0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 385)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 385)
,W/bt-btif ( 2058): invalid rfc slot id: 114
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Cancelled: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8970 7C:F9:0E:34:8A:A0]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Cancelled: Connection timeout [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3251 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Incoming connection, peer ID: 7C:F9:0E:34:8A:A0, name: samsung-SM-G900F_PT8970, Bluetooth address: 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:34:8A:A0
I/jxcore-log( 3253): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT8970","peerAvailable":true}]
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : samsung-SM-G900F_PT8970, Available: true
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Incoming socket thread, for peer with ID 7C:F9:0E:34:8A:A0, created successfully
D/io.jxcore.node.ConnectionHelper( 3253): onConnected: The total number of connections is now 1
I/jxcore-log( 3253): 2015-12-14T14:57:26.342Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:57:26.342Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:57:26.342Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
,W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,D/io.jxcore.node.IncomingSocketThread( 3253): Entering thread (ID: 387)
,I/io.jxcore.node.IncomingSocketThread( 3253): Local host address: localhost/127.0.0.1, port: 60048
D/io.jxcore.node.IncomingSocketThread( 3253): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3253): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3253): Exiting thread (ID: 387)
,I/jxcore-log( 3253): 2015-12-14T14:57:26.358Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3253): 
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 389, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 388, name: Sender)
,I/jxcore-log( 3253): 2015-12-14T14:57:26.363Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:57:26.452Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:57:26.483Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 385)
,I/jxcore-log( 3253): 2015-12-14T14:57:26.796Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:57:26.807Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:57:26.866Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:57:26.896Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:57:26.934Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:57:26.974Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:57:27.011Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:57:27.027Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:57:27.084Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:57:27.093Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:57:27.100Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3253): 
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa405208c rs_disc_pending=0
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2058): invalid rfc slot id: 66
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 389, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3253): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:34:8A:A0 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 387
I/io.jxcore.node.IncomingSocketThread( 3253): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 389
I/io.jxcore.node.IncomingSocketThread( 3253): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 388
I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 388, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:34:8A:A0 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3253): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 388, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 389, name: Receiver)
,I/jxcore-log( 3253): 2015-12-14T14:57:27.796Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3253): 
,W/bt-rfcomm( 2058): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 2058): RFCOMM_DisconnectInd LCID:0x49
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: S5-1
,I/jxcore-log( 3253): 2015-12-14T14:57:31.344Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:57:31.344Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/UsageStatsService(  736): User[0] Flushing usage stats to disk
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pManager( 3253): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT652","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT652 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT652","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT652, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: , Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: E0:DB:10:14:E2:C0), either no such connection or failed to close the connection
,I/jxcore-log( 3253): 2015-12-14T14:57:36.352Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:57:36.359Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:57:36.360Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:57:36.363Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: null E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to null in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 390)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:115, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 115
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:116, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 116
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 390)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 390)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Connection timeout
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:117, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 117
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:118, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 118
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 390)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 390)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Cancelled: Connection timeout [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3251 E0:DB:10:14:E2:C0]
,I/jxcore-log( 3253): 2015-12-14T14:57:57.273Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:57:57.274Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:57:57.275Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 390)
,I/jxcore-log( 3253): 2015-12-14T14:58:02.276Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:58:02.277Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3253): 
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: E0:DB:10:14:E2:C0), either no such connection or failed to close the connection
I/jxcore-log( 3253): 2015-12-14T14:58:07.281Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:58:07.282Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:58:07.288Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:58:07.289Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
,I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: null E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to null in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 391)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:119, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 119
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:120, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 120
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 391)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 391)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Connection timeout
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:121, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 121
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:122, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 122
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 391)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 391)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Cancelled: Connection timeout [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3251 E0:DB:10:14:E2:C0]
I/jxcore-log( 3253): 2015-12-14T14:58:28.201Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:58:28.207Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:58:28.210Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 391)
,I/jxcore-log( 3253): 2015-12-14T14:58:33.216Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:58:33.217Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: E0:DB:10:14:E2:C0), either no such connection or failed to close the connection
I/jxcore-log( 3253): 2015-12-14T14:58:38.221Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:58:38.222Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:58:38.226Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:58:38.230Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
,I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: null E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to null in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 392)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:123, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 123
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:124, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 124
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 392)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 392)
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Connection timeout
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:125, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 125
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:126, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 126
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 392)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 392)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): cancel: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Cancelled: Connection timeout [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3251 E0:DB:10:14:E2:C0]
,I/jxcore-log( 3253): 2015-12-14T14:58:59.142Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:58:59.143Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): oneRoundDownNow
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:58:59.144Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3253): 
D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: E0:DB:10:14:E2:C0), either no such connection or failed to close the connection
I/jxcore-log( 3253): 2015-12-14T14:58:59.148Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): ---- round done--------
I/jxcore-log( 3253): 
I/jxcore-log( 3253): startWithNextDevice
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): device[11]: 34:FC:EF:11:B1:66
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:58:59.159Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:58:59.160Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:58:59.161Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
,I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to null in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: null 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to null in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 393)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 392)
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
E/bt-btif ( 2058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2058): Entering PendingCommandState State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothAdapterProperties( 2058): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,D/WifiP2pManager( 3253): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/BluetoothBondStateMachine( 2058): StableState(): Entering Off State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onSocketConnected: Authenticating next: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT1076 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 393)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): onBytesWritten: 77 bytes successfully written (thread ID: 394)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Outgoing connection initialized (*handshake* thread ID: 394)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 393)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Entering thread (ID: 394)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): onBytesRead: Read 77 bytes successfully (thread ID: 394)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Handshake succeeded with [34:FC:EF:11:B1:66 LGE-Nexus 5_PT1076 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onAuthenticated: Fully connected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT1076 34:FC:EF:11:B1:66]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT1076 34:FC:EF:11:B1:66]
I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Outgoing connection, peer ID: 34:FC:EF:11:B1:66, name: LGE-Nexus 5_PT1076, Bluetooth address: 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:11:B1:66 already in the list
,I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Outgoing socket thread, for peer with ID 34:FC:EF:11:B1:66, created successfully
D/io.jxcore.node.ConnectionHelper( 3253): onConnected: The total number of connections is now 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Exiting thread (ID: 394)
D/io.jxcore.node.OutgoingSocketThread( 3253): Entering thread (ID: 395)
,D/io.jxcore.node.OutgoingSocketThread( 3253): Server socket local port: 36878
I/io.jxcore.node.OutgoingSocketThread( 3253): Now accepting connections...
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/io.jxcore.node.ConnectionHelper( 3253): onListeningForIncomingConnections: Outgoing connection is using port 36878 (peer ID: 34:FC:EF:11:B1:66)
,I/jxcore-log( 3253): 2015-12-14T14:59:00.965Z SendDataConnector.js: CLIENT connected to 36878, error: null
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:59:00.966Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3253): 
,I/io.jxcore.node.OutgoingSocketThread( 3253): Incoming data from address: /127.0.0.1, port: 36878
D/io.jxcore.node.OutgoingSocketThread( 3253): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3253): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3253): Exiting thread (ID: 395)
,I/jxcore-log( 3253): 2015-12-14T14:59:00.994Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3253): 
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 397, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 396, name: Sender)
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,D/WifiP2pManager( 3253): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa4052254 rs_disc_pending=0
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3253): 2015-12-14T14:59:02.761Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:02.909Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3253): 
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12826
,I/jxcore-log( 3253): 2015-12-14T14:59:02.997Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:03.064Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3253): 
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2926
,I/jxcore-log( 3253): 2015-12-14T14:59:03.235Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:03.267Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:03.375Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:03.494Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5671"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT5671 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5671"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5671"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5671"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5671"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5671"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT5671, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: Thali Test's G2, Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3253): 2015-12-14T14:59:08.163Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:10.090Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:59:10.091Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3253): 
I/jxcore-log( 3253): oneRoundDownNow
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:10.096Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:59:10.097Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3253): 
D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:11:B1:66
I/io.jxcore.node.OutgoingSocketThread( 3253): close
I/io.jxcore.node.OutgoingSocketThread( 3253): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 397
I/io.jxcore.node.OutgoingSocketThread( 3253): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 396
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 396, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Outgoing connection, peer with ID 34:FC:EF:11:B1:66 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 397, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Outgoing connection, peer with ID 34:FC:EF:11:B1:66 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Successfully disconnected (peer ID: 34:FC:EF:11:B1:66
,E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 396, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 397, name: Receiver)
,I/jxcore-log( 3253): 2015-12-14T14:59:10.137Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3253): 
I/jxcore-log( 3253): ---- round done--------
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): startWithNextDevice
I/jxcore-log( 3253): 
I/jxcore-log( 3253): device[12]: 08:EC:A9:50:75:41
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:59:10.139Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:59:10.139Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:59:10.139Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
,I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: A3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 398)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,W/bt-btif ( 2058): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa4052254 rs_disc_pending=1
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa405241c rs_disc_pending=1
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: Nexus 5,
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 2058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2058): Entering PendingCommandState State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2058): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2058): StableState(): Entering Off State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 2058): PORT_StartCnf failed result:5
E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2058): invalid rfc slot id: 128
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapService( 2058): onReceive
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: A3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Connection timeout
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x1f  CID 0x44
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:129, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 129
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 398)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 398)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:75:41 samsung-SM-A300FU_PT8079 08:EC:A9:50:75:41]
,I/jxcore-log( 3253): 2015-12-14T14:59:31.598Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:75:41 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:59:31.598Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:75:41 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:59:31.599Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 398)
,I/jxcore-log( 3253): 2015-12-14T14:59:36.600Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:59:36.601Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3253): 
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
I/jxcore-log( 3253): 2015-12-14T14:59:41.606Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:59:41.607Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:59:41.609Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:59:41.609Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: A3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: A3-1 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 399)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [08:ec:a9:50:75:41]: 6, f, 6109
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: A3-1
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onSocketConnected: Authenticating next: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT8079 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 399)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): onBytesWritten: 77 bytes successfully written (thread ID: 400)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Outgoing connection initialized (*handshake* thread ID: 400)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 399)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Entering thread (ID: 400)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): onBytesRead: Read 83 bytes successfully (thread ID: 400)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT8079 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onAuthenticated: Fully connected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT8079 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Exiting thread (ID: 400)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT8079 08:EC:A9:50:75:41]
I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:75:41, name: samsung-SM-A300FU_PT8079, Bluetooth address: 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Outgoing socket thread, for peer with ID 08:EC:A9:50:75:41, created successfully
D/io.jxcore.node.ConnectionHelper( 3253): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3253): Entering thread (ID: 401)
D/io.jxcore.node.OutgoingSocketThread( 3253): Server socket local port: 36790
I/io.jxcore.node.OutgoingSocketThread( 3253): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3253): onListeningForIncomingConnections: Outgoing connection is using port 36790 (peer ID: 08:EC:A9:50:75:41)
I/jxcore-log( 3253): 2015-12-14T14:59:43.268Z SendDataConnector.js: CLIENT connected to 36790, error: null
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:59:43.268Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:43.270Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3253): 
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa405241c rs_disc_pending=0
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,I/io.jxcore.node.OutgoingSocketThread( 3253): Incoming data from address: /127.0.0.1, port: 36790
D/io.jxcore.node.OutgoingSocketThread( 3253): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3253): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3253): Exiting thread (ID: 401)
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 402, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 403, name: Receiver)
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3253): 2015-12-14T14:59:44.185Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:44.674Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3253): 
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 3253): 2015-12-14T14:59:44.859Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:45.219Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3253): 
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3253): 2015-12-14T14:59:45.393Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3253): 
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [f8:95:c7:87:85:54]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa405241c rs_disc_pending=1
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3253): 2015-12-14T14:59:45.957Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:46.287Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:46.518Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:46.620Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3253): 
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3253): 2015-12-14T14:59:46.883Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:59:46.884Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3253): 
I/jxcore-log( 3253): oneRoundDownNow
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:59:46.884Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:59:46.884Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3253): 
D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
I/io.jxcore.node.OutgoingSocketThread( 3253): close
I/io.jxcore.node.OutgoingSocketThread( 3253): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 403
I/io.jxcore.node.OutgoingSocketThread( 3253): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 402
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 402, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:75:41 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 403, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:75:41 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:75:41
,E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 402, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 403, name: Receiver)
,I/jxcore-log( 3253): 2015-12-14T14:59:46.891Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3253): 
I/jxcore-log( 3253): ---- round done--------
I/jxcore-log( 3253): 
I/jxcore-log( 3253): startWithNextDevice
I/jxcore-log( 3253): 
I/jxcore-log( 3253): device[13]: 58:3F:54:73:64:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:59:46.892Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:59:46.892Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T14:59:46.892Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
,I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: G3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: null 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to null in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 404)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=1
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2058): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa405241c rs_disc_pending=0
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2058): Entering PendingCommandState State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2058): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2058): StableState(): Entering Off State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,E/BluetoothEventManager( 2728): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: A3-1
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:131, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 131
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=1
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:255
W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Incoming connection accepted,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Incoming connection initialized (thread ID: 405)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Entering thread (ID: 405)
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): onBytesRead: Read 77 bytes successfully (thread ID: 405)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT9795 F8:95:C7:87:85:54]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): onBytesWritten: 77 bytes successfully written (thread ID: 405)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): removeThreadFromList: Removing thread with ID 405
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3253): Handshake thread disposed (thread ID: 405)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT9795 F8:95:C7:87:85:54]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Exiting thread (ID: 405)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT9795 F8:95:C7:87:85:54]
,I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Incoming connection, peer ID: F8:95:C7:87:85:54, name: LGE-LG-D722_PT9795, Bluetooth address: F8:95:C7:87:85:54
,D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
,I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
,I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Incoming socket thread, for peer with ID F8:95:C7:87:85:54, created successfully
D/io.jxcore.node.ConnectionHelper( 3253): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3253): Entering thread (ID: 406)
,I/io.jxcore.node.IncomingSocketThread( 3253): Local host address: localhost/127.0.0.1, port: 60048
D/io.jxcore.node.IncomingSocketThread( 3253): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3253): 2015-12-14T14:59:54.580Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3253): 
,I/io.jxcore.node.IncomingSocketThread( 3253): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3253): Exiting thread (ID: 406)
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 408, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 407, name: Sender)
,I/jxcore-log( 3253): 2015-12-14T14:59:55.650Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:55.657Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:55.705Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:55.711Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:55.737Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:55.787Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:55.823Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:55.906Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:55.937Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:55.985Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:56.009Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:56.044Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:56.063Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:56.069Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:56.200Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:56.345Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:56.454Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:56.515Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:56.730Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:56.742Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:56.844Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:56.890Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:56.923Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:56.944Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:57.085Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:57.094Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:57.225Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:57.285Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:57.446Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:57.455Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:57.641Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:57.863Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:57.895Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:58.077Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:58.083Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:58.218Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:58.230Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:58.309Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:58.355Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:58.386Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:58.471Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:58.478Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:58.520Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3253): ,
,I/jxcore-log( 3253): 2015-12-14T14:59:58.548Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:58.558Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:58.633Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:58.715Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:58.720Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T14:59:58.771Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3253): 
,W/bt-btif ( 2058): invalid rfc slot id: 113
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 408, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3253): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Incoming connection, peer with ID F8:95:C7:87:85:54 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 406
I/io.jxcore.node.IncomingSocketThread( 3253): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 408
I/io.jxcore.node.IncomingSocketThread( 3253): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 407
I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 407, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Incoming connection, peer with ID F8:95:C7:87:85:54 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3253): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 3253): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 407, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 408, name: Receiver)
,I/jxcore-log( 3253): 2015-12-14T14:59:58.916Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3253): 
,W/bt-rfcomm( 2058): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 2058): RFCOMM_DisconnectInd LCID:0x4a
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: true
,W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Connection timeout
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: G3s-1
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0xd  CID 0x48
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:132, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 132
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Cancelled: Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Cancelled: Connection timeout [58:3F:54:73:64:C0 LGE-LG-D855_PT5184 58:3F:54:73:64:C0]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 404)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 404)
,I/jxcore-log( 3253): 2015-12-14T15:00:04.285Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 58:3F:54:73:64:C0 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:00:04.286Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 58:3F:54:73:64:C0 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:00:04.286Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 404)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/jxcore-log( 3253): 2015-12-14T15:00:09.288Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:00:09.289Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3253): 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:3F:54:73:64:C0), either no such connection or failed to close the connection
I/jxcore-log( 3253): 2015-12-14T15:00:14.300Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:00:14.301Z SendDataConnector.js: Connect (retry count 1) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:00:14.302Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T15:00:14.302Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
,I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
,D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: G3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: null 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to null in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 409)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9551","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT9551 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT9551, peer ID: 44:80:EB:7B:5A:05, Wi-Fi Direct device name: XT1072_23d5, Wi-Fi Direct address: 44:80:eb:7b:5a:07
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 44:80:EB:7B:5A:05 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT3806","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT3806 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
,I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT3806, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
,I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Adding peer with ID F8:95:C7:87:3C:51
,I/jxcore-log( 3253): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT3806","peerAvailable":true}]
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : LGE-LG-H815_PT3806, Available: true
I/jxcore-log( 3253): 
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3578","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3578 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: samsung-SM-A500FU_PT3578, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:37:96:ac
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3493","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3493 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT3493, peer ID: 7C:F9:0E:51:18:22, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:51:18:23
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT3132"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [38:94:96:B5:06:DC samsung-SM-G800H_PT3132 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 38:94:96:B5:06:DC, peer name: samsung-SM-G800H_PT3132, peer ID: 38:94:96:B5:06:DC, Wi-Fi Direct device name: , Wi-Fi Direct address: 3a:94:96:b5:06:dd
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 38:94:96:B5:06:DC already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7543"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT7543 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 6 services discovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
,I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT7543, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: Android_63cc, Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Adding peer with ID 80:01:84:8A:B3:68
,I/jxcore-log( 3253): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"HTC-HTC Desire 820_PT7543","peerAvailable":true}]
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): Found peer : HTC-HTC Desire 820_PT7543, Available: true
I/jxcore-log( 3253): 
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 6 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Connection timeout
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2058): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 2058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2058): Entering PendingCommandState State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,W/bt-rfcomm( 2058): PORT_StartCnf failed result:5
,W/bt-btif ( 2058): invalid rfc slot id: 134
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 2058): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 9 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2058): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2058): StableState(): Entering Off State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa40525e4 rs_disc_pending=0
W/bt-btif ( 2058): bta_dm_check_av:0
W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 2058): tBTM_SEC_DEV:0xa40525e4 rs_disc_pending=0
W/bt-btif ( 2058): bta_dm_check_av:0
,W/bt-btif ( 2058): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 2058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2058): Entering PendingCommandState State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2058): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2058): StableState(): Entering Off State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onSocketConnected: Authenticating next: [58:3F:54:73:64:C0 LGE-LG-D855_PT5184 58:3F:54:73:64:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 409)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 409)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5671"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT5671 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 7 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9177","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9177 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 8 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Cancelled: Connection timeout [58:3F:54:73:64:C0 LGE-LG-D855_PT5184 58:3F:54:73:64:C0]
,I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT5671, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: , Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: B0:C5:59:3F:75:69, peer name: samsung-SM-G900F_PT9177, peer ID: B0:C5:59:3F:75:69, Wi-Fi Direct device name: , Wi-Fi Direct address: ee:1f:72:18:8b:78
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Adding peer with ID B0:C5:59:3F:75:69
I/jxcore-log( 3253): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT9177","peerAvailable":true}]
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : samsung-SM-G900F_PT9177, Available: true
I/jxcore-log( 3253): 
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
I/jxcore-log( 3253): 2015-12-14T15:00:41.099Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 58:3F:54:73:64:C0 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:00:41.099Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 58:3F:54:73:64:C0 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:00:41.100Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2058): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 2058): Do not find the bg connection mask for the remote device
,D/BluetoothMapService( 2058): onReceive
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: G3-1
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3253): 2015-12-14T15:00:46.101Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T15:00:46.109Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3253): 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:3F:54:73:64:C0), either no such connection or failed to close the connection
,I/jxcore-log( 3253): 2015-12-14T15:00:51.117Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:00:51.118Z SendDataConnector.js: Connect (retry count 2) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:00:51.119Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:00:51.119Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: G3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to G3-1 in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: G3-1 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to G3-1 in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 410)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3253): timeout now
I/jxcore-log( 3253): 
I/jxcore-log( 3253): weAreDoneNow, resultArray.length: 12
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): sendReportNow
I/jxcore-log( 3253): 
I/jxcore-log( 3253): done, now sending data to server
I/jxcore-log( 3253): 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3253): 2015-12-14T15:01:04.793Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3253): 
D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:3F:54:73:64:C0), either no such connection or failed to close the connection
I/jxcore-log( 3253): 2015-12-14T15:01:04.794Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8079","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT8079 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 9 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT8079, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: , Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 9 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Connection timeout
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: G3-1
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 2058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2058): Entering PendingCommandState State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2058): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2058): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 2058): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2058): StableState(): Entering Off State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onSocketConnected: Authenticating next: [58:3F:54:73:64:C0 LGE-LG-D855_PT5184 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5861","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5861 E0:DB:10:1F:C9:5E]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 410)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 410)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Cancelled: Connection timeout [58:3F:54:73:64:C0 LGE-LG-D855_PT5184 58:3F:54:73:64:C0]
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/bt-btif ( 2058): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT5861, peer ID: E0:DB:10:1F:C9:5E, Wi-Fi Direct device name: Note3-1, Wi-Fi Direct address: ea:50:8b:de:28:a3
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Adding peer with ID E0:DB:10:1F:C9:5E
I/jxcore-log( 3253): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"samsung-SM-N9005_PT5861","peerAvailable":true}]
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : samsung-SM-N9005_PT5861, Available: true
I/jxcore-log( 3253): 
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
I/jxcore-log( 3253): 2015-12-14T15:01:15.628Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 58:3F:54:73:64:C0 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:01:15.628Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 58:3F:54:73:64:C0 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:01:15.628Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
,W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: G3-1
,I/jxcore-log( 3253): 2015-12-14T15:01:20.629Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:01:20.630Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pManager( 3253): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully,
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:3F:54:73:64:C0), either no such connection or failed to close the connection
I/jxcore-log( 3253): 2015-12-14T15:01:25.631Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:01:25.631Z SendDataConnector.js: Connect (retry count 3) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T15:01:25.631Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:01:25.632Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: G3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to G3-1 in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: G3-1 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to G3-1 in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 411)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:137, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 137
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:138, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 138
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 411)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 411)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-smp  ( 2058): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2058): Plain text(LSB ~ MSB) = 77 92 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2058): Encrypted text(LSB ~ MSB) = b4 d4 62 30 a9 4f e8 cc 42 dd 85 53 b1 e0 3c 34 
W/bt-btm  ( 2058): Stopping oneshot timer
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8970","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8970 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8970","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8970","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8970","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 7C:F9:0E:34:8A:A0, peer name: samsung-SM-G900F_PT8970, peer ID: 7C:F9:0E:34:8A:A0, Wi-Fi Direct device name: S5-1, Wi-Fi Direct address: ee:1f:72:63:11:86
,I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:34:8A:A0 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x1f  CID 0x40
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:139, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 139
,W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): Connection timeout
,W/bt-sdp  ( 2058): SDP - Rcvd conn cnf with error: 0x1f  CID 0x44
E/bt-btif ( 2058): DISCOVERY_COMP_EVT slot id:140, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2058): invalid rfc slot id: 140
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 411)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect again in 300 ms... (thread ID: 411)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnectionFailed: Cancelled: Connection timeout [58:3F:54:73:64:C0 LGE-LG-D855_PT5184 58:3F:54:73:64:C0]
I/jxcore-log( 3253): 2015-12-14T15:01:51.098Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 58:3F:54:73:64:C0 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:01:51.099Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 58:3F:54:73:64:C0 failed
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:01:51.101Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3253): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 411)
,I/jxcore-log( 3253): 2015-12-14T15:01:56.102Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:01:56.103Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3253): 
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:3F:54:73:64:C0), either no such connection or failed to close the connection
I/jxcore-log( 3253): 2015-12-14T15:02:01.107Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:02:01.108Z SendDataConnector.js: Connect (retry count 4) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T15:02:01.109Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:02:01.109Z SendDataConnector.js: do connect now
I/jxcore-log( 3253): 
I/io.jxcore.node.ConnectionHelper( 3253): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): connect: G3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Trying to start connecting to G3-1 in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnecting: G3-1 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): connect: Started connecting to G3-1 in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3253): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 412)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3253): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3253): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2058): info:x10
,D/        ( 2058): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: G3-1
,W/bt-sdp  ( 2058): process_service_search_attr_rsp
,W/bt-btif ( 2058): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2058): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onSocketConnected: Authenticating next: [58:3F:54:73:64:C0 LGE-LG-D855_PT5184 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 412)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): onBytesWritten: 77 bytes successfully written (thread ID: 413)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Outgoing connection initialized (*handshake* thread ID: 413)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Exiting thread (thread ID: 412)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Entering thread (ID: 413)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): onBytesRead: Read 77 bytes successfully (thread ID: 413)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3253): Handshake succeeded with [58:3F:54:73:64:C0 LGE-LG-D855_PT5184 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3253): onAuthenticated: Fully connected: [58:3F:54:73:64:C0 LGE-LG-D855_PT5184 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3253): Exiting thread (ID: 413)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT5184 58:3F:54:73:64:C0]
I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Outgoing connection, peer ID: 58:3F:54:73:64:C0, name: LGE-LG-D855_PT5184, Bluetooth address: 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3253): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
,I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 58:3F:54:73:64:C0 already in the list
I/io.jxcore.node.ConnectionHelper( 3253): onConnected: Outgoing socket thread, for peer with ID 58:3F:54:73:64:C0, created successfully
D/io.jxcore.node.ConnectionHelper( 3253): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3253): Entering thread (ID: 414)
D/io.jxcore.node.OutgoingSocketThread( 3253): Server socket local port: 52714
I/io.jxcore.node.OutgoingSocketThread( 3253): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3253): onListeningForIncomingConnections: Outgoing connection is using port 52714 (peer ID: 58:3F:54:73:64:C0)
I/jxcore-log( 3253): 2015-12-14T15:02:03.676Z SendDataConnector.js: CLIENT connected to 52714, error: null
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:02:03.676Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3253): 
,I/io.jxcore.node.OutgoingSocketThread( 3253): Incoming data from address: /127.0.0.1, port: 52714
D/io.jxcore.node.OutgoingSocketThread( 3253): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3253): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3253): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3253): Exiting thread (ID: 414)
,I/jxcore-log( 3253): 2015-12-14T15:02:03.708Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3253): 
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 416, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3253): Entering thread (ID: 415, name: Sender)
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3253): 2015-12-14T15:02:04.285Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3253): 
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:15796
,I/jxcore-log( 3253): 2015-12-14T15:02:04.339Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T15:02:04.342Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3253): 
,D/        ( 2058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:5896
,I/jxcore-log( 3253): 2015-12-14T15:02:04.384Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T15:02:04.395Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T15:02:04.444Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T15:02:04.498Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T15:02:04.502Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T15:02:04.569Z SendDataConnector.js: CLIENT is data received : 90000,
I/jxcore-log( 3253): 
,I/jxcore-log( 3253): 2015-12-14T15:02:04.578Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:02:04.579Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3253): 
I/jxcore-log( 3253): oneRoundDownNow
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:02:04.580Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3253): 
I/jxcore-log( 3253): 2015-12-14T15:02:04.580Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3253): 
,D/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 58:3F:54:73:64:C0
I/io.jxcore.node.OutgoingSocketThread( 3253): close
I/io.jxcore.node.OutgoingSocketThread( 3253): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 416
I/io.jxcore.node.OutgoingSocketThread( 3253): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3253): doStop: Thread ID: 415
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 415, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Outgoing connection, peer with ID 58:3F:54:73:64:C0 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3253): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3253): Either failed to read from the output stream or write to the input stream (thread ID: 416, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3253): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3253): onDisconnected: Outgoing connection, peer with ID 58:3F:54:73:64:C0 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3253): disconnectOutgoingConnection: Successfully disconnected (peer ID: 58:3F:54:73:64:C0
,E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 415, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
,D/io.jxcore.node.ConnectionHelper( 3253): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3253): Exiting thread (ID: 416, name: Receiver)
,I/jxcore-log( 3253): 2015-12-14T15:02:04.627Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3253): 
,W/bt-btif ( 2058): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,D/btif_config_util( 2058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2058): onReceive
,I/BTConnectionReceiver( 1382): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1382): Bluetooth Device Name: G3-1
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3253): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: XT1039_8c05 f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 8 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: XT1039_8c05 f4:f1:e1:5c:43:c8
D/WifiP2pManager( 3253): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,D/WifiP2pManager( 3253): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9177","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9177 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9177","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9177","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9177","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9177","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9177","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9177","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: B0:C5:59:3F:75:69, peer name: samsung-SM-G900F_PT9177, peer ID: B0:C5:59:3F:75:69, Wi-Fi Direct device name: Thali Test (Galaxy S5), Wi-Fi Direct address: ee:1f:72:18:8b:78
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID B0:C5:59:3F:75:69 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3251","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3251 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3251","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3251","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3251","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local.",
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3251","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3251","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local.",
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT3251, peer ID: E0:DB:10:14:E2:C0, Wi-Fi Direct device name: Note4-1, Wi-Fi Direct address: 92:b6:86:43:73:1c,
,I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID E0:DB:10:14:E2:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3251","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
,W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 7 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1651","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1651 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1651","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT1651, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: Android_50a5, Wi-Fi Direct address: fa:cf:c5:d9:e5:62
,I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Adding peer with ID F8:CF:C5:D9:E5:61
I/jxcore-log( 3253): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"motorola-Nexus 6_PT1651","peerAvailable":true}]
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : motorola-Nexus 6_PT1651, Available: true
I/jxcore-log( 3253): 
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7543"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT7543 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT7543, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: , Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7543"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8079","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT8079 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8079","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT8079, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: , Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9551","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT9551 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9551","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT9551, peer ID: 44:80:EB:7B:5A:05, Wi-Fi Direct device name: , Wi-Fi Direct address: 44:80:eb:7b:5a:07
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 44:80:EB:7B:5A:05 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9177","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9177 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9177","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: B0:C5:59:3F:75:69, peer name: samsung-SM-G900F_PT9177, peer ID: B0:C5:59:3F:75:69, Wi-Fi Direct device name: , Wi-Fi Direct address: ee:1f:72:18:8b:78
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID B0:C5:59:3F:75:69 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT5202 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT5202, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: XT1039_8c05, Wi-Fi Direct address: f4:f1:e1:5c:43:c8
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 6 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT3554","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT3554 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 7 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT3554","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 90:E7:C4:F6:69:77, peer name: HTC-HTC One M8s_PT3554, peer ID: 90:E7:C4:F6:69:77, Wi-Fi Direct device name: Android_608e, Wi-Fi Direct address: 92:e7:c4:e6:4c:f8
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Adding peer with ID 90:E7:C4:F6:69:77
I/jxcore-log( 3253): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC-HTC One M8s_PT3554","peerAvailable":true}]
I/jxcore-log( 3253): 
I/jxcore-log( 3253): Found peer : HTC-HTC One M8s_PT3554, Available: true
I/jxcore-log( 3253): 
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 7 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT3132"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [38:94:96:B5:06:DC samsung-SM-G800H_PT3132 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 8 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT3132"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 38:94:96:B5:06:DC, peer name: samsung-SM-G800H_PT3132, peer ID: 38:94:96:B5:06:DC, Wi-Fi Direct device name: Galaxy S5-2, Wi-Fi Direct address: 3a:94:96:b5:06:dd
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 38:94:96:B5:06:DC already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8970","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8970 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 9 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8970","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 7C:F9:0E:34:8A:A0, peer name: samsung-SM-G900F_PT8970, peer ID: 7C:F9:0E:34:8A:A0, Wi-Fi Direct device name: S5-1, Wi-Fi Direct address: ee:1f:72:63:11:86
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:34:8A:A0 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 9 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3251","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3251 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 10 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3251","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT3251, peer ID: E0:DB:10:14:E2:C0, Wi-Fi Direct device name: Note4-1, Wi-Fi Direct address: 92:b6:86:43:73:1c
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID E0:DB:10:14:E2:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 10 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT8535 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 11 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT8535, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 11 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9795","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT9795 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 12 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9795","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: F8:95:C7:87:85:54, peer name: LGE-LG-D722_PT9795, peer ID: F8:95:C7:87:85:54, Wi-Fi Direct device name: G3s-1, Wi-Fi Direct address: a2:39:f7:70:12:80
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 12 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3578","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3578 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 13 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3578","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: samsung-SM-A500FU_PT3578, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:37:96:ac
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 13 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT8535 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT8535, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT8535 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT8535, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
,I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 4 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Android_50a5 fa:cf:c5:d9:e5:62
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: Android_50a5 fa:cf:c5:d9:e5:62
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: Android_50a5 fa:cf:c5:d9:e5:62
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: Android_50a5 fa:cf:c5:d9:e5:62
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3253): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,D/WifiP2pManager( 3253): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5184","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5184 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5184","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5184","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5184","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5184","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT5184, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: G3-1, Wi-Fi Direct address: 02:9a:02:7b:60:ac
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 58:3F:54:73:64:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5184","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8079","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT8079 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 2 services discovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8079","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8079","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT8079, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: A3-1, Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8079","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8079","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8079","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7543"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT7543 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT7543, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: Android_63cc, Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7543"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7543"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7543"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7543"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT7543"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT652","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT652 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT652, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: , Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT652","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT652","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT652","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT652","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT652","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9795","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT9795 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: F8:95:C7:87:85:54, peer name: LGE-LG-D722_PT9795, peer ID: F8:95:C7:87:85:54, Wi-Fi Direct device name: , Wi-Fi Direct address: a2:39:f7:70:12:80
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9795","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9795","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9795","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9795","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9795","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT8535 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT8535, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8535"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 7 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Android_50a5 fa:cf:c5:d9:e5:62
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 7 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 7 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT5202 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5202"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT5202, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: XT1039_8c05, Wi-Fi Direct address: f4:f1:e1:5c:43:c8
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 0 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): stopServiceDiscovery
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1031): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4491","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3253): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery stopped successfully
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): start: Starting peer discovery...
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 7 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 7 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 7 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,D/WifiP2pManager( 3253): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 5: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pManager( 3253): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
D/WifiP2pManager( 3253): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1031): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3493","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3493 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3253): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3253): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3493","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3493","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3493","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3493","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3493","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3493","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3493","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3493","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3253): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3253): onPeerDiscovered: Bluetooth address: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT3493, peer ID: 7C:F9:0E:51:18:22, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:51:18:23
I/io.jxcore.node.ConnectionHelper( 3253): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
W/io.jxcore.node.ConnectionHelper( 3253): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/ActivityManager(  736): Killing 2573:com.google.android.apps.docs/u0a40 (adj 13): empty for 1800s
,I/ActivityManager(  736): Killing 3105:com.android.defcontainer/u0a5 (adj 13): empty for 1807s
,I/ActivityManager(  736): Killing 3178:com.android.musicfx/u0a15 (adj 13): empty for 1810s
,I/ActivityManager(  736): Killing 2225:com.google.android.partnersetup/u0a13 (adj 15): empty for 1810s
,I/ActivityManager(  736): Killing 2910:android.process.acore/u0a4 (adj 15): empty for 1810s
,I/ActivityManager(  736): Killing 3050:com.google.android.gms:car/u0a8 (adj 15): empty for 1817s
,I/ProcessStatsService(  736): Prepared write state in 3ms
,W/libprocessgroup(  736): failed to open /acct/uid_10005/pid_3105/cgroup.procs: No such file or directory
,W/libprocessgroup(  736): failed to open /acct/uid_10008/pid_3050/cgroup.procs: No such file or directory
,W/libprocessgroup(  736): failed to open /acct/uid_10040/pid_2573/cgroup.procs: No such file or directory
,W/libprocessgroup(  736): failed to open /acct/uid_10015/pid_3178/cgroup.procs: No such file or directory
,W/libprocessgroup(  736): failed to open /acct/uid_10013/pid_2225/cgroup.procs: No such file or directory
,W/libprocessgroup(  736): failed to open /acct/uid_10004/pid_2910/cgroup.procs: No such file or directory
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  736): Pruning old procstats: /data/system/procstats/state-2015-12-13-14-39-35.bin
,TIME-OUT KILL (timeout was 1800000ms),I/ActivityManager(  736): Killing 2778:com.google.android.music:main/u0a60 (adj 15): empty for 1804s
W/libprocessgroup(  736): failed to open /acct/uid_10060/pid_2778/cgroup.procs: No such file or directory
D/AndroidRuntime( 4137): 
D/AndroidRuntime( 4137): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4137): CheckJNI is OFF
D/AndroidRuntime( 4137): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  736): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  736): Killing 3253:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
W/PackageSettings(  736): Skipping PackageSetting{adda9f4 com.example.hello/10277} due to missing metadata
I/WindowState(  736): WIN DEATH: Window{355afbfd u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  736): Client connection lost with reason: 4
I/ActivityManager(  736):   Force finishing activity ActivityRecord{172184de u0 com.test.thalitest/.MainActivity t214}
I/ActivityManager(  736): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
W/ActivityManager(  736): Spurious death for ProcessRecord{60abc1 3253:com.test.thalitest/u0a270}, curProc for 3253: null
I/InputReader(  736): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1571): Ignoring removeGeofence because network location is disabled.
I/ActivityManager(  736): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4162 uid=10004 gids={50004, 9997} abi=armeabi-v7a
I/Keyboard.Facilitator( 1071): resetDictionaries() : en_US
I/art     ( 1285): Explicit concurrent mark sweep GC freed 3931(293KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 5.535ms total 59.804ms
I/Keyboard.Facilitator.DecoderInitializer( 1071): run()
I/art     ( 1382): Explicit concurrent mark sweep GC freed 60501(2MB) AllocSpace objects, 12(192KB) LOS objects, 24% free, 19MB/25MB, paused 313us total 90.531ms
I/Decoder ( 1071): createOrResetDecoder
I/art     (  736): Explicit concurrent mark sweep GC freed 122652(5MB) AllocSpace objects, 10(244KB) LOS objects, 33% free, 28MB/43MB, paused 1.103ms total 88.992ms
I/art     (  736): WaitForGcToComplete blocked for 44.268ms for cause Explicit
I/art     ( 1642): Explicit concurrent mark sweep GC freed 27212(1441KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 23MB/31MB, paused 4.098ms total 128.817ms
I/ConfigService( 1571): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1071): run()
D/BackupManagerService(  736): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  736): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  736): removeObsoleteFile: deleting file=214_task.xml
E/ActivityThread(  947): Performing stop of activity that is not resumed: {com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity}
E/ActivityThread(  947): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity}
E/ActivityThread(  947): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3309)
E/ActivityThread(  947): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3390)
E/ActivityThread(  947): 	at android.app.ActivityThread.access$1100(ActivityThread.java:144)
E/ActivityThread(  947): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1307)
E/ActivityThread(  947): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  947): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread(  947): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread(  947): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  947): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  947): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread(  947): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
I/Keyboard.Facilitator.MainLanguageModelLoader( 1071): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1071): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1071): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1071): run()
I/StatsUtilsManager( 1071): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1071): shouldRecordStats() = Too Soon
I/ActivityManager(  736): Activity reported stop, but no longer stopping: ActivityRecord{344e379b u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity t212}
I/art     (  736): Explicit concurrent mark sweep GC freed 20350(1034KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 1.763ms total 141.376ms
D/VoicemailCleanupService( 4162): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  736): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=4197 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
I/ContactLocale( 4162): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/Launcher( 1285): Deferring update until onResume
D/AndroidRuntime( 4137): Shutting down VM
W/ResourcesManager( 1285): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  736): Killing 1885:com.google.android.talk/u0a54 (adj 15): empty for 1805s
W/ResourcesManager( 1285): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/UpdateIcingCorporaServi( 1382): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/Launcher( 1285): Deferring update until onResume
W/libprocessgroup(  736): failed to open /acct/uid_10054/pid_1885/cgroup.procs: No such file or directory
W/Launcher( 1285): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@12586a19 new=com.google.android.velvet.VelvetApplication@12586a19
I/ActivityManager(  736): Killing 3434:com.google.android.apps.magazines/u0a61 (adj 15): empty for 1805s
I/ActivityManager(  736): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4219 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
W/libprocessgroup(  736): failed to open /acct/uid_10061/pid_3434/cgroup.procs: No such file or directory
I/UpdateIcingCorporaServi( 1382): UpdateCorporaTask done [took 258 ms] updated apps [took 258 ms] 
W/ContextImpl( 4219): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
D/PackageBroadcastService( 1642): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1642): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1642): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1642): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1642): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1642): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1642): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1571): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1571): Shutting down VM
I/LocationSettingsChecker( 1642): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1642): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 1571): FATAL EXCEPTION: main
E/AndroidRuntime( 1571): Process: com.google.android.gms.persistent, PID: 1571
E/AndroidRuntime( 1571): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1571): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
E/AndroidRuntime( 1571): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1571): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/AndroidRuntime( 1571): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1571): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1571): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/AndroidRuntime( 1571): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1571): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1571): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/AndroidRuntime( 1571): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/AndroidRuntime( 1571): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1571): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1571): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1571): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1571): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1571): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1571): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1571): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1571): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1571): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/AndroidRuntime( 1571): 	... 9 more
E/DriveAsyncService( 1642): disk I/O error (code 3850)
E/DriveAsyncService( 1642): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1642): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1642): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1642): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1642): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1642): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1642): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1642): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1642): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1642): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1642): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1642): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1642): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1642): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1642): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1642): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4219): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4219): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4219): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4219): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4219): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4219): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4219): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4219): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4219): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4219): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4219): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4219): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 4219): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4219): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4219): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4219): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase( 4219): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase( 4219): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4219): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4219): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4219): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 4219): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4219): Process: com.android.keychain, PID: 4219
E/AndroidRuntime( 4219): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4219): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4219): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4219): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4219): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4219): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4219): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4219): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4219): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4219): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4219): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/AndroidRuntime( 4219): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 4219): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4219): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4219): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime( 4219): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/AndroidRuntime( 4219): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4219): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4219): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4219): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  736): Can't write: system_app_crash
E/DropBoxManagerService(  736): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  736): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  736): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  736): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  736): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  736): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  736): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  736): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  736): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  736): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  736): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  736): 	... 5 more
I/Process ( 1571): Sending signal. PID: 1571 SIG: 9
E/DropBoxManagerService(  736): Can't write: system_app_crash
E/DropBoxManagerService(  736): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  736): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  736): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  736): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  736): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  736): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  736): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  736): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  736): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  736): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  736): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  736): 	... 5 more
I/Process ( 4219): Sending signal. PID: 4219 SIG: 9
E/AndroidRuntime( 1642): FATAL EXCEPTION: PlayGamesAsyncThread2
E/AndroidRuntime( 1642): Process: com.google.android.gms, PID: 1642
E/AndroidRuntime( 1642): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1642): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1642): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1642): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1642): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1642): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1642): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 1642): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1642): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1642): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1642): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/AndroidRuntime( 1642): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 1642): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 1642): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1642): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 1642): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1642): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1642): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1642): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 1642): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1642): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1642): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1642): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1642): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1642): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1642): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1642): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1642): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1642): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 1642): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1642): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1642): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1642): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1642): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1642): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1642): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1642): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1642): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1642): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1642): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1642): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1642): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1642): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1642): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1642): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1642): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1642): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1642): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1642): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1642): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1642): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1642): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1642): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1642): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteOpenHelper( 1642): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1642): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1642): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1642): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1642): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1642): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1642): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1642): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1642): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1642): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1642): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 1642): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 1642): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1642): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1642): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PhenotypeInitializer( 1642): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PhenotypeInitializer( 1642): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1642): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1642): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1642): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/PhenotypeInitializer( 1642): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/PhenotypeInitializer( 1642): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PhenotypeInitializer( 1642): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/PhenotypeInitializer( 1642): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/PhenotypeInitializer( 1642): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/PhenotypeInitializer( 1642): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 1642): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 1642): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1642): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1642): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1642): 	at android.os.Looper.loop(Looper.java:135)
E/PhenotypeInitializer( 1642): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  736): Process com.google.android.gms has crashed too many times: killing!
I/ActivityManager(  736): Killing 1642:com.google.android.gms/u0a8 (adj 5): crash
E/DropBoxManagerService(  736): Can't write: system_app_crash
E/DropBoxManagerService(  736): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  736): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  736): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  736): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  736): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  736): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  736): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  736): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  736): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  736): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  736): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  736): 	... 5 more
D/GpsStatusListenerHelper(  736): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@321af60c

```
