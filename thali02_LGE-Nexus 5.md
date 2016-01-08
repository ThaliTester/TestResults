#### Test 5546736337bcedb_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1676): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1676): Module APK com.google.android.play.games already loaded
I/Icing   ( 1676): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1676): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1676): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1676): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,--------- beginning of system
I/ActivityManager(  760): Killing 2639:com.google.android.gm/u0a70 (adj 15): empty #17
W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2639/cgroup.procs: No such file or directory
D/AndroidRuntime( 3556): 
D/AndroidRuntime( 3556): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3556): CheckJNI is OFF
D/AndroidRuntime( 3556): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3577 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3556): Shutting down VM
V/ActivityManager(  760): Display changed displayId=0
I/WebViewFactory( 3577): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3577): Time to load native libraries: 2 ms (timestamps 8164-8166)
I/LibraryLoader( 3577): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3577): Binding Chromium to main looper Looper (main, tid 1) {2f14d56b}
I/LibraryLoader( 3577): Expected native library version number "",actual native library version number ""
I/chromium( 3577): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3577): Initializing chromium process, singleProcess=true
W/art     ( 3577): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3577): ApplicationContext is null in ApplicationStatus
W/chromium( 3577): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3577): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3577): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3577): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2cf09a50:true
,W/art     ( 3577): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3577): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3577): CordovaWebView is running on device made by: LGE
,W/art     ( 3577): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3577): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3577): Render dirty regions requested: true
,D/Atlas   ( 3577): Validating map...
,W/chromium( 3577): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3577): Initialized EGL, version 1.4
D/OpenGLRenderer( 3577): Enabling debug mode 0
,I/Keyboard.Facilitator( 1059): onFinishInput()
,W/IInputConnectionWrapper( 3577): showStatusIcon on inactive InputConnection
,I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +453ms (total +55s464ms)
,W/BindingManager( 3577): Cannot call determinedVisibility() - never saw a connection for the pid: 3577
,D/JsMessageQueue( 3577): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3577): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1405519232
D/JX-Cordova( 3577): jxcore cordova android initializing
,W/jxcore-log( 3577): Initializing JXcore engine
W/jxcore-log( 3577): JXcore engine is ready
,W/jxcore-log( 3577): Starting JXcore engine
,W/.test.thalitest( 3577): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8392]" dev="sockfs" ino=8392 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3577): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3577): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6485]" dev="sockfs" ino=6485 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3577): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[22725]" dev="sockfs" ino=22725 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3577): Platform android
W/jxcore-log( 3577): 
,W/jxcore-log( 3577): Process ARCH arm
W/jxcore-log( 3577): 
,I/jxcore-log( 3577): JXcore Cordova bridge is ready!
I/jxcore-log( 3577): 
W/jxcore-log( 3577): JXcore engine is started
I/Choreographer( 3577): Skipped 112 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3577): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3577): Toggling radios to true
I/jxcore-log( 3577): 
,D/BluetoothAdapter( 3577): enable(): BT is already enabled..!
,D/WifiService(  760): New client listening to asynchronous messages
,D/WifiService(  760): setWifiEnabled: true pid=3577, uid=10270
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3577): Radios toggled
I/jxcore-log( 3577): 
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3577): Received device characteristics:
I/jxcore-log( 3577): Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3577): Bluetooth name: Nexus 5
I/jxcore-log( 3577): Device name: LGE-Nexus 5
I/jxcore-log( 3577): 
,I/wpa_supplicant( 1005): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
I/jxcore-log( 3577): Perf Test app loaded loaded
I/jxcore-log( 3577): 
,E/WifiStateMachine(  760): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  760): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,I/Choreographer( 3577): Skipped 68 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 3577): check test folder
I/jxcore-log( 3577): 
I/jxcore-log( 3577): found test : ./testFindPeers.js
I/jxcore-log( 3577): 
,V/NativeCrypto( 1610): Read error: ssl=0xa422fe00: I/O error during system call, Connection timed out
I/jxcore-log( 3577): found test : ./testSendData.js
I/jxcore-log( 3577): 
,V/NativeCrypto( 1610): SSL shutdown failed: ssl=0xa422fe00: I/O error during system call, Broken pipe
V/NativeCrypto( 3002): Read error: ssl=0xb3e46200: I/O error during system call, Connection timed out
D/ConnectivityService(  760): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  760): Start Disconnecting Watchdog 1
,V/NativeCrypto( 3002): Read error: ssl=0xb3e46a00: I/O error during system call, Connection timed out
,E/native  (  760): do suspend true
,V/NativeCrypto( 3002): Write error: ssl=0xb3e46a00: I/O error during system call, Broken pipe
,V/NativeCrypto( 3002): Write error: ssl=0xb3e46a00: I/O error during system call, Broken pipe
V/NativeCrypto( 3002): SSL shutdown failed: ssl=0xb3e46a00: I/O error during system call, Broken pipe
V/NativeCrypto( 3002): Write error: ssl=0xb3e46200: I/O error during system call, Broken pipe
,V/NativeCrypto( 3002): Write error: ssl=0xb3e46200: I/O error during system call, Broken pipe
V/NativeCrypto( 3002): SSL shutdown failed: ssl=0xb3e46200: I/O error during system call, Broken pipe
,I/wpa_supplicant( 1005): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/CommandListener(  179): Clearing all IP addresses on wlan0
D/ConnectivityService(  760): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
D/Nat464Xlat(  760): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  760): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Disconnected - quitting
D/ConnectivityService(  760): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  760): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory( 1222): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1676): CM callback handler got msg 524292
,D/WifiNetworkAgent(  760): NetworkAgent: NetworkAgent channel lost
,I/chromium( 3577): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 1005): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1005): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1005): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1005): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  760): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  760): Start Dhcp Watchdog 2
,V/GLSActivity( 1610): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1610): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/native  (  760): do suspend false
,E/WifiStateMachine(  760): scanCount==0 - aborting
,W/NetworkUtils( 1403): OkHttp exception
,W/EventLoggerService( 1403): Unable to send logs Error code: 262146
,I/dhcpcd  ( 3670): version 5.5.6 starting
,E/dhcpcd  ( 3670): get_duid: Read-only file system
,I/dhcpcd  ( 3670): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3670): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3670): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2829): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1676): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1676): onCreate
,D/SystemUpdateService( 1676): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1676): active receiver: enabled
,I/iu.Environment( 1676): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1676): num queued entries: 0
I/iu.UploadsManager( 1676): num updated entries: 0
,I/iu.SyncManager( 1676): NEXT; no task
,I/SystemUpdateService( 1676): showing system update notification
,I/Babel   ( 1967): connection state changed from CONNECTED to DISCONNECTED
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1676): retry (wakeup: false) in 3599978 ms
,I/ActivityManager(  760): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3713 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  760): No APN found to select.
,D/SystemUpdateService( 1676): onDestroy
,E/GpsLocationProvider(  760): No APN found to select.
,E/native  (  760): do suspend true
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  760): Adding iface wlan0 to network 101
,E/WifiStateMachine(  760): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  760): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  760): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  760): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  760): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  760): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  760): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  760): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::5255:27ff:fef0:fd0b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1676): CM callback handler got msg 524290
,I/GAv4    ( 3713): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3713):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3713):   adb logcat -s GAv4
,W/GAv4    ( 3713): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 14:49:24 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452264564112], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452264564097]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Validated
,D/ConnectivityService(  760): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  760): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1676): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1222): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/GAv4    ( 3713): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3713): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3713): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3713): Time to load native libraries: 1 ms (timestamps 5333-5334)
,I/LibraryLoader( 3713): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3713): Binding Chromium to main looper Looper (main, tid 1) {86861a5}
,I/LibraryLoader( 3713): Expected native library version number "",actual native library version number ""
,I/chromium( 3713): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3713): Initializing chromium process, singleProcess=true
,W/art     ( 3713): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3713): ApplicationContext is null in ApplicationStatus
,W/chromium( 3713): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3713): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3713): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3713): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3713): Requires BLUETOOTH permission
,I/NSApplication( 3713): Starting up...
,I/ActivityManager(  760): Killing 3199:com.google.android.apps.cloudprint/u0a35 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10035/pid_3199/cgroup.procs: No such file or directory
,V/MusicLeanback( 2829): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1676): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1676): onCreate
,D/SystemUpdateService( 1676): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1676): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1676): num queued entries: 0
I/iu.UploadsManager( 1676): num updated entries: 0
,I/iu.SyncManager( 1676): NEXT; no task
,I/SystemUpdateService( 1676): active receiver: enabled
,I/SystemUpdateService( 1676): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1676): retry (wakeup: false) in 3599989 ms
,D/SystemUpdateService( 1676): onDestroy
,I/Babel   ( 1967): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  760): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3577): BLE is supported
I/jxcore-log( 3577): 
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2829): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2829): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1676): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1676): onCreate
,D/SystemUpdateService( 1676): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1676): active receiver: enabled
,I/SystemUpdateService( 1676): showing system update notification
,E/GpsLocationProvider(  760): No APN found to select.
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1676): retry (wakeup: false) in 3599960 ms
,D/SystemUpdateService( 1676): onDestroy
,D/Finsky  ( 2698): [265] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2698): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/art     (  760): Explicit concurrent mark sweep GC freed 45164(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 28MB/42MB, paused 1.276ms total 76.946ms
,V/GLSActivity( 1610): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1610): Vacuum at: now=1452264582141 tag=VacuumService
,I/PhenotypeConfigurator( 1610): Scheduling Phenotype for one-off execution 6935 seconds from now (1452264582479)
,D/GetConfigurationSnapshotOperation( 1610): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1610): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1610): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1610): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1610): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1059): run()
I/Keyboard.Facilitator( 1059): flushDynamicLanguageModels()
,I/ConfigService( 1610): onCreate
,I/ConfigService( 1610): onDestroy
,I/ClearcutLoggerApiImpl( 1676): disconnect managed GoogleApiClient
,I/ClearcutLoggerApiImpl( 1610): disconnect managed GoogleApiClient
,I/jxcore-log( 3577): Connected to the server!
I/jxcore-log( 3577): 
,I/chromium( 3577): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3577): --- start :testFindPeers.js---
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): testFindPeers created [object Object]
I/jxcore-log( 3577): 
I/jxcore-log( 3577): serverPort is 8876
I/jxcore-log( 3577): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3577): bind: Binding a new listener
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3577): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3577): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3577): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): start: OK
I/io.jxcore.node.ConnectionHelper( 3577): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3577): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3577): bind: Binding a new listener
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3577): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3577): createAdvertiseData: From: Nexus 5 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3577): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3577): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3577): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3577): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): start: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3577): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3577): start: OK
I/jxcore-log( 3577): StartBroadcasting started ok
I/jxcore-log( 3577): 
I/chromium( 3577): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3577): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): setState: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3577): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/io.jxcore.node.ConnectionHelper( 3577): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3577): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 3577): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service request added successfully
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service discovery started successfully
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): setState: RESTARTING
,I/wpa_supplicant( 1005): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1005): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1005): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): Start timer timeout, starting now...
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): restart: Restarting...
,D/WifiP2pManager( 3577): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service request added successfully
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service discovery started successfully
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Adding a new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 3577): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 3577): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] is available
,I/jxcore-log( 3577): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"G3s-1","peerAvailable":true}]
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 3577): 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): restart: Restarting...
,D/WifiP2pManager( 3577): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service request added successfully
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service discovery started successfully
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Adding a new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/io.jxcore.node.ConnectionHelper( 3577): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3577): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
I/jxcore-log( 3577): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"Thali Test (Galaxy S5)","peerAvailable":true}]
I/jxcore-log( 3577): 
I/jxcore-log( 3577): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 3577): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Adding a new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 3577): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3577): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
,I/jxcore-log( 3577): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"G4-1","peerAvailable":true}]
I/jxcore-log( 3577): 
I/jxcore-log( 3577): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 3577): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Adding a new peer: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 3577): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 3577): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 G3-1] is available
,I/jxcore-log( 3577): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"G3-1","peerAvailable":true}]
I/jxcore-log( 3577): 
I/jxcore-log( 3577): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log( 3577): 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Adding a new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 3577): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3577): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
I/jxcore-log( 3577): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"A3-1","peerAvailable":true}]
I/jxcore-log( 3577): 
I/jxcore-log( 3577): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 3577): 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): restart: Restarting...
,D/WifiP2pManager( 3577): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service request added successfully
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service discovery started successfully
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Adding a new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 3577): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
,W/io.jxcore.node.ConnectionHelper( 3577): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): restart: Restarting...,
,D/WifiP2pManager( 3577): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service request added successfully
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1005): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service discovery started successfully
,I/jxcore-log( 3577): timeout now
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): weAreDoneNow
I/jxcore-log( 3577): 
I/jxcore-log( 3577): done, now sending data to server
I/jxcore-log( 3577): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): setState: RESTARTING
,I/wpa_supplicant( 1005): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1005): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1005): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1005): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1005): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1005): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): Start timer timeout, starting now...
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1005): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3577): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service request added successfully
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service discovery started successfully
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,I/jxcore-log( 3577): teardown
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): testFindPeers stopped
I/jxcore-log( 3577): 
I/io.jxcore.node.ConnectionHelper( 3577): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3577): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3577): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3577): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3577): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): setState: NOT_STARTED
,I/jxcore-log( 3577): StopBroadcasting went ok
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): --- start :testSendData.js---
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":18}bt-address length : 17
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): daya100000
I/jxcore-log( 3577): 
I/jxcore-log( 3577): check server
I/jxcore-log( 3577): 
I/jxcore-log( 3577): serverPort is 49561
I/jxcore-log( 3577): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3577): bind: Binding a new listener
D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3577): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3577): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3577): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): start: OK
I/io.jxcore.node.ConnectionHelper( 3577): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3577): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3577): bind: Binding a new listener
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3577): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3577): createAdvertiseData: From: Nexus 5 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3577): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3577): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3577): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3577): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): start: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3577): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3577): start: OK
,I/jxcore-log( 3577): StartBroadcasting started ok
I/jxcore-log( 3577): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Waiting for incoming connections...
,I/jxcore-log( 3577): [ { address: '34:FC:EF:9D:93:0B', tryCount: 0 },
I/jxcore-log( 3577):   { address: '7C:F9:0E:37:96:AB', tryCount: 0 },
I/jxcore-log( 3577):   { address: '08:EC:A9:50:75:41', tryCount: 0 },
I/jxcore-log( 3577):   { address: '7C:F9:0E:34:8A:A0', tryCount: 0 },
I/jxcore-log( 3577):   { address: '08:EC:A9:50:76:27', tryCount: 0 },
I/jxcore-log( 3577):   { address: 'F8:95:C7:87:85:54', tryCount: 0 },
I/jxcore-log( 3577):   { address: 'F4:F1:E1:5C:3B:E2', tryCount: 0 },
I/jxcore-log( 3577):   { address: '34:FC:EF:11:B1:66', tryCount: 0 },
I/jxcore-log( 3577):   { address: '7C:F9:0E:51:18:22', tryCount: 0 },
I/jxcore-log( 3577):   { address: '44:80:EB:7B:5A:05', tryCount: 0 },
I/jxcore-log( 3577):   { address: 'B4:CE:F6:AB:A4:6A', tryCount: 0 },
I/jxcore-log( 3577):   { address: '00:F4:6F:30:E0:6C', tryCount: 0 },
I/jxcore-log( 3577):   { address: '80:01:84:8A:B3:68', tryCount: 0 },
I/jxcore-log( 3577):   { address: 'B0:C5:59:3F:75:69', tryCount: 0 },
I/jxcore-log( 3577):   { address: 'F8:95:C7:87:3C:51', tryCount: 0 },
I/jxcore-log( 3577):   { address: '58:3F:54:73:64:C0', tryCount: 0 },
I/jxcore-log( 3577):   { address: 'E0:DB:10:14:E2:C0', tryCount: 0 } ]
I/jxcore-log( 3577): 
I/jxcore-log( 3577): startWithNextDevice
I/jxcore-log( 3577): 
I/jxcore-log( 3577): do fake peer & start
I/jxcore-log( 3577): 
I/jxcore-log( 3577): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:57:10.982Z SendDataConnector.js: Start called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:57:10.982Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:57:10.982Z SendDataConnector.js: do connect now
I/jxcore-log( 3577): 
,I/io.jxcore.node.ConnectionHelper( 3577): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
W/io.jxcore.node.ConnectionHelper( 3577): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): connect: [34:FC:EF:9D:93:0B 34:FC:EF:9D:93:0B]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): connect: Trying to start connecting to null in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): setInsecureRfcommSocketPortNumber: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): onConnecting: null 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): connect: Started connecting to null in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3577): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
I/jxcore-log( 3577): 2016-01-08T14:57:10.987Z SendDataTCPServer.js: TCP/IP server is bound to port: 49561
I/jxcore-log( 3577): 
I/chromium( 3577): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3577): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3577): onDiscoveryManagerStateChanged: NOT_STARTED
I/chromium( 3577): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3577): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3577): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3577): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 340)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3577): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3577): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2138): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2138): info:x10
,D/        ( 2138): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 2138): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2138): process_service_search_attr_rsp
,W/bt-btif ( 2138): info:x10
,D/        ( 2138): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2138): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2138): info:x10
,D/        ( 2138): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2138): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2138): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 2138): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2138): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2138): Entering PendingCommandState State
,I/ActivityManager(  760): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=3902 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@368f4232:true
,I/ActivityManager(  760): Killing 3132:com.google.android.videos/u0a77 (adj 15): empty #17
,I/BluetoothBondStateMachine( 2138): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
D/BluetoothAdapterProperties( 2138): Failed to remove device: 34:FC:EF:9D:93:0B
,W/libprocessgroup(  760): failed to open /acct/uid_10077/pid_3132/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 2138): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2138): StableState(): Entering Off State
,W/bt-btif ( 2138): new conn_srvc id:26, app_id:1
W/bt-btif ( 2138): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2138): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): onSocketConnected: [34:FC:EF:9D:93:0B 34:FC:EF:9D:93:0B] (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 340)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): onBytesWritten: 66 bytes successfully written (thread ID: 341)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Outgoing connection initialized (*handshake* thread ID: 341)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Exiting thread (thread ID: 340)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3577): Entering thread (ID: 341)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): onBytesRead: Read 74 bytes successfully (thread ID: 341)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Handshake succeeded with [34:FC:EF:9D:93:0B Thali Test's G2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): onHandshakeSucceeded: [34:FC:EF:9D:93:0B Thali Test's G2] (thread ID: 340)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3577): Exiting thread (ID: 341)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): onConnected: [34:FC:EF:9D:93:0B Thali Test's G2]
,I/io.jxcore.node.ConnectionHelper( 3577): onConnected: Outgoing connection to peer [34:FC:EF:9D:93:0B Thali Test's G2]
D/io.jxcore.node.ConnectionHelper( 3577): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3577): notifyPeerAvailability: Peer [34:FC:EF:9D:93:0B Thali Test's G2] is available
,I/io.jxcore.node.ConnectionHelper( 3577): onConnected: Outgoing socket thread, for peer [34:FC:EF:9D:93:0B Thali Test's G2], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3577): setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): setConnectionTimeout: 15000
D/io.jxcore.node.ConnectionHelper( 3577): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3577): Entering thread (ID: 342)
,D/io.jxcore.node.OutgoingSocketThread( 3577): Server socket local port: 44182
I/io.jxcore.node.OutgoingSocketThread( 3577): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3577): onListeningForIncomingConnections: Outgoing connection is using port 44182 (peer ID: 34:FC:EF:9D:93:0B)
,I/jxcore-log( 3577): 2016-01-08T14:57:13.073Z SendDataConnector.js: CLIENT connected to 44182, error: null
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:57:13.076Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3577): 
,I/io.jxcore.node.OutgoingSocketThread( 3577): Incoming data from address: /127.0.0.1, port: 44182
D/io.jxcore.node.OutgoingSocketThread( 3577): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3577): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3577): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3577): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3577): Exiting thread (ID: 342)
,D/io.jxcore.node.StreamCopyingThread( 3577): Entering thread (ID: 343, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3577): Entering thread (ID: 344, name: Receiver)
,I/jxcore-log( 3577): 2016-01-08T14:57:13.139Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3577): 
,I/BluetoothBondStateMachine( 2138): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
I/BluetoothBondStateMachine( 2138): sspRequestCallback: [B@3343c135 name: [B@1cb599ca cod: 5898764 pairingVariant 0 passkey: 151819
,I/BluetoothBondStateMachine( 2138): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11,
I/BluetoothBondStateMachine( 2138): Entering PendingCommandState State
,D/        ( 2138): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:98
,I/io.jxcore.node.ConnectionHelper( 3577): lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3577): setAdvertiseMode: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3577): applySettings: Advertise mode: 0, advertise TX power level: 1, scan mode: 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3577): setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3577): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3577): setScanMode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3577): applySettings: Advertise mode: 0, advertise TX power level: 1, scan mode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3577): setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3577): setScanSettings: Mode: 0, report delay in milliseconds: 0, scan result type: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3577): Local services cleared successfully
,D/        ( 2138): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:21246
,E/bt-btm  ( 2138): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2138): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1005): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1005): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1005): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3577): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): setState: RESTARTING
,I/wpa_supplicant( 1005): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 0 device(s) discovered
,D/btif_config_util( 2138): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): Start timer timeout, starting now...
,I/wpa_supplicant( 1005): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1005): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3577): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service request added successfully
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Adding a new peer: [58:3F:54:73:64:C0 G3-1]
,I/io.jxcore.node.ConnectionHelper( 3577): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3577): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Adding a new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 3577): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3577): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3577): Powering the BLE discovery back up
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3577): setAdvertiseMode: 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3577): applySettings: Advertise mode: 1, advertise TX power level: 1, scan mode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3577): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3577): setScanSettings: Mode: 0, report delay in milliseconds: 0, scan result type: 0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3577): setScanMode: 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3577): applySettings: Advertise mode: 1, advertise TX power level: 1, scan mode: 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3577): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3577): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,I/jxcore-log( 3577): 2016-01-08T14:57:34.133Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:57:34.133Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:57:34.139Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:57:34.139Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:57:34.141Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3577): 
,E/io.jxcore.node.StreamCopyingThread( 3577): Input stream got -1 on read (thread ID: 343, thread name: Sender)
E/io.jxcore.node.OutgoingSocketThread( 3577): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 3577): onDisconnected: Outgoing connection, peer [34:FC:EF:9D:93:0B Thali Test's G2] disconnected: Input stream got -1 on read
I/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:9D:93:0B
I/io.jxcore.node.OutgoingSocketThread( 3577): close
D/io.jxcore.node.OutgoingSocketThread( 3577): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3577): doStop: Thread ID: 344
D/io.jxcore.node.OutgoingSocketThread( 3577): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3577): doStop: Thread ID: 343
D/io.jxcore.node.OutgoingSocketThread( 3577): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.OutgoingSocketThread( 3577): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 3577): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 3577): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3577): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3577): Either failed to read from the output stream or write to the input stream (thread ID: 344, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3577): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3577): onDisconnected: Outgoing connection, peer [34:FC:EF:9D:93:0B Thali Test's G2] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3577): Exiting thread (ID: 344, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3577): Exiting thread (ID: 343, name: Sender)
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): restart: Restarting...
,D/WifiP2pManager( 3577): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service request added successfully
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service discovery started successfully
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
,I/jxcore-log( 3577): 2016-01-08T14:57:39.141Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:39.145Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3577): 
,D/io.jxcore.node.ConnectionHelper( 3577): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3577): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
,I/jxcore-log( 3577): 2016-01-08T14:57:44.152Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:57:44.157Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:44.160Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:44.160Z SendDataConnector.js: do connect now
I/jxcore-log( 3577): 
,I/io.jxcore.node.ConnectionHelper( 3577): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): connect: [34:FC:EF:9D:93:0B Thali Test's G2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): connect: Trying to start connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): setInsecureRfcommSocketPortNumber: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): onConnecting: Thali Test's G2 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): connect: Started connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3577): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
,E/bt-btm  ( 2138): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 2138): Do not find the bg connection mask for the remote device
,E/bt-btif ( 2138): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2138): bondStateChangeCallback: Status: 9 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2138): Failed to remove device: 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 345)
W/BluetoothAdapter( 3577): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapService( 2138): onReceive
,D/BTIF_SOCK( 2138): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 2138): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2138): StableState(): Entering Off State
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@15b79cad:true
,I/BTConnectionReceiver( 1403): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1403): Bluetooth Device Name: G3-1
,W/bt-sdp  ( 2138): process_service_search_attr_rsp
,E/bt-rfcomm( 2138): RFCOMM_CreateConnection - already opened state:2, RFC state:4, MCB state:5
E/bt-btif ( 2138): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 345)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Maximum number of allowed retries (0) reached, giving up... (thread ID: 345)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): shutdownAndRemoveClientThread: Shutting down thread with ID 345
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:9D:93:0B Thali Test's G2]
,W/bt-btif ( 2138): invalid rfc slot id: 7
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Exiting thread (thread ID: 345)
I/jxcore-log( 3577): 2016-01-08T14:57:44.370Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [34:FC:EF:9D:93:0B Thali Test's G2] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:57:44.370Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [34:FC:EF:9D:93:0B Thali Test's G2] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:57:44.370Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3577): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3577): setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): shutdown (thread ID: 345)
,I/jxcore-log( 3577): 2016-01-08T14:57:49.370Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:57:49.371Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3577): 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): restart: Restarting...
,D/WifiP2pManager( 3577): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service request added successfully
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2138): info:x10
,D/        ( 2138): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1403): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1403): Bluetooth Device Name: G3-1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service discovery started successfully
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2138): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2138): onReceive
,I/BTConnectionReceiver( 1403): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1403): Bluetooth Device Name: G3-1
,W/bt-btif ( 2138): info:x10
,D/        ( 2138): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1403): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1403): Bluetooth Device Name: G3-1
,I/BluetoothBondStateMachine( 2138): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 2138): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2138): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2138): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2138): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2138): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 2138): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,W/bt-btif ( 2138): new conn_srvc id:26, app_id:255
W/bt-btif ( 2138): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2138): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Incoming connection initialized (thread ID: 347)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Waiting for incoming connections...
,I/BluetoothBondStateMachine( 2138): StableState(): Entering Off State
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3577): Entering thread (ID: 347)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): onBytesRead: Read 63 bytes successfully (thread ID: 347)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Got valid identity from [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): onBytesWritten: 66 bytes successfully written (thread ID: 347)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): removeThreadFromList: Removing thread with ID 347
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Handshake thread disposed (thread ID: 347)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): onIncomingConnectionConnected: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): onConnected: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 3577): onConnected: Incoming connection to peer [58:3F:54:73:64:C0 G3-1]
D/io.jxcore.node.ConnectionHelper( 3577): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper( 3577): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3577): onConnected: Incoming socket thread, for peer [58:3F:54:73:64:C0 G3-1], created successfully
D/io.jxcore.node.ConnectionHelper( 3577): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3577): Exiting thread (ID: 347)
,D/io.jxcore.node.IncomingSocketThread( 3577): Entering thread (ID: 348)
,I/io.jxcore.node.IncomingSocketThread( 3577): Local host address: localhost/127.0.0.1, port: 49561
D/io.jxcore.node.IncomingSocketThread( 3577): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3577): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3577): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3577): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3577): Exiting thread (ID: 348)
,I/jxcore-log( 3577): 2016-01-08T14:57:53.414Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3577): 
,D/io.jxcore.node.StreamCopyingThread( 3577): Entering thread (ID: 350, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3577): Entering thread (ID: 349, name: Sender)
,D/io.jxcore.node.ConnectionHelper( 3577): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3577): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
I/jxcore-log( 3577): 2016-01-08T14:57:54.376Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:57:54.377Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:57:54.378Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:57:54.378Z SendDataConnector.js: do connect now
I/jxcore-log( 3577): 
I/io.jxcore.node.ConnectionHelper( 3577): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): connect: [34:FC:EF:9D:93:0B Thali Test's G2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): connect: Trying to start connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): setInsecureRfcommSocketPortNumber: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): onConnecting: Thali Test's G2 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): connect: Started connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3577): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 351)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3577): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3577): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2138): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3577): 2016-01-08T14:57:54.899Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 3577): 
,I/io.jxcore.node.ConnectionHelper( 3577): lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3577): setAdvertiseMode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3577): applySettings: Advertise mode: 0, advertise TX power level: 1, scan mode: 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3577): setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3577): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3577): setScanMode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3577): applySettings: Advertise mode: 0, advertise TX power level: 1, scan mode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3577): setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3577): setScanSettings: Mode: 0, report delay in milliseconds: 0, scan result type: 0
,I/jxcore-log( 3577): 2016-01-08T14:57:54.919Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3577): 
,W/bt-sdp  ( 2138): process_service_search_attr_rsp
,I/jxcore-log( 3577): 2016-01-08T14:57:55.011Z SendDataTCPServer.js: TCP/IP server has received 4950 bytes of data
I/jxcore-log( 3577): 
,E/bt-rfcomm( 2138): RFCOMM_CreateConnection - already opened state:2, RFC state:4, MCB state:5
E/bt-btif ( 2138): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/bt-btif ( 2138): invalid rfc slot id: 9
,W/BluetoothAdapter( 3577): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2138): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3577): 2016-01-08T14:57:55.188Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.198Z SendDataTCPServer.js: TCP/IP server has received 6930 bytes of data
I/jxcore-log( 3577): 
,W/bt-sdp  ( 2138): process_service_search_attr_rsp
,E/bt-rfcomm( 2138): RFCOMM_CreateConnection - already opened state:2, RFC state:4, MCB state:5
E/bt-btif ( 2138): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/bt-btif ( 2138): invalid rfc slot id: 10
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 351)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Maximum number of allowed retries (0) reached, giving up... (thread ID: 351)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 351)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): shutdownAndRemoveClientThread: Shutting down thread with ID 351
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Exiting thread (thread ID: 351)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:9D:93:0B Thali Test's G2]
I/jxcore-log( 3577): 2016-01-08T14:57:55.231Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [34:FC:EF:9D:93:0B Thali Test's G2] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:57:55.231Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [34:FC:EF:9D:93:0B Thali Test's G2] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:57:55.232Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3577): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3577): setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): setConnectionTimeout: 15000
I/jxcore-log( 3577): 2016-01-08T14:57:55.246Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3577): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): shutdown (thread ID: 351)
,I/jxcore-log( 3577): 2016-01-08T14:57:55.262Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.271Z SendDataTCPServer.js: TCP/IP server has received 11162 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.278Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.313Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.414Z SendDataTCPServer.js: TCP/IP server has received 15122 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.420Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.423Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.429Z SendDataTCPServer.js: TCP/IP server has received 17374 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.436Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.445Z SendDataTCPServer.js: TCP/IP server has received 19354 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.454Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.462Z SendDataTCPServer.js: TCP/IP server has received 21334 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.494Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.588Z SendDataTCPServer.js: TCP/IP server has received 23314 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.894Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.900Z SendDataTCPServer.js: TCP/IP server has received 25294 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.907Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.913Z SendDataTCPServer.js: TCP/IP server has received 27274 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.920Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.927Z SendDataTCPServer.js: TCP/IP server has received 29254 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.934Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.940Z SendDataTCPServer.js: TCP/IP server has received 31234 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.974Z SendDataTCPServer.js: TCP/IP server has received 35194 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.995Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:55.999Z SendDataTCPServer.js: TCP/IP server has received 37174 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.003Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.010Z SendDataTCPServer.js: TCP/IP server has received 39154 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.016Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.024Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.054Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.178Z SendDataTCPServer.js: TCP/IP server has received 49054 bytes of data
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:57:56.180Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.192Z SendDataTCPServer.js: TCP/IP server has received 51034 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.229Z SendDataTCPServer.js: TCP/IP server has received 60934 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.345Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.375Z SendDataTCPServer.js: TCP/IP server has received 62914 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.403Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.453Z SendDataTCPServer.js: TCP/IP server has received 64894 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.460Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.467Z SendDataTCPServer.js: TCP/IP server has received 66874 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.478Z SendDataTCPServer.js: TCP/IP server has received 68854 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.485Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.498Z SendDataTCPServer.js: TCP/IP server has received 74794 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.502Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.533Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.536Z SendDataTCPServer.js: TCP/IP server has received 82714 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.573Z SendDataTCPServer.js: TCP/IP server has received 86674 bytes of data
I/jxcore-log( 3577): 
,D/btif_config_util( 2138): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3577): 2016-01-08T14:57:56.694Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.698Z SendDataTCPServer.js: TCP/IP server has received 88654 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.702Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.706Z SendDataTCPServer.js: TCP/IP server has received 90634 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.748Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:56.864Z SendDataTCPServer.js: TCP/IP server has received 92614 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:57.198Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:57.213Z SendDataTCPServer.js: TCP/IP server has received 94594 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:57.217Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:57:57.257Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3577): 
,W/io.jxcore.node.StreamCopyingThread( 3577): Either failed to read from the output stream or write to the input stream (thread ID: 350, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3577): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3577): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 G3-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 348
D/io.jxcore.node.IncomingSocketThread( 3577): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3577): doStop: Thread ID: 350
D/io.jxcore.node.IncomingSocketThread( 3577): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3577): doStop: Thread ID: 349
D/io.jxcore.node.IncomingSocketThread( 3577): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3577): closeLocalSocketAndStreams: Closing the local input stream...
,W/bt-btif ( 2138): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 3577): Either failed to read from the output stream or write to the input stream (thread ID: 349, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3577): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3577): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 G3-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3577): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3577): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 3577): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3577): Exiting thread (ID: 349, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3577): Exiting thread (ID: 350, name: Receiver)
,I/jxcore-log( 3577): 2016-01-08T14:57:57.342Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3577): 
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2138): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 2138): RFCOMM_DisconnectInd LCID:0x48
,E/bt-btm  ( 2138): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2138): onReceive
,I/BTConnectionReceiver( 1403): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1403): Bluetooth Device Name: G3-1
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3577): 2016-01-08T14:58:00.245Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:58:00.246Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3577): 
,D/io.jxcore.node.ConnectionHelper( 3577): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3577): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
I/jxcore-log( 3577): 2016-01-08T14:58:05.250Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:58:05.251Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:58:05.252Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:58:05.252Z SendDataConnector.js: do connect now
I/jxcore-log( 3577): 
,I/io.jxcore.node.ConnectionHelper( 3577): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): connect: [34:FC:EF:9D:93:0B Thali Test's G2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): connect: Trying to start connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): setInsecureRfcommSocketPortNumber: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): onConnecting: Thali Test's G2 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): connect: Started connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3577): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 353)
W/BluetoothAdapter( 3577): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2138): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2138): process_service_search_attr_rsp
,E/bt-rfcomm( 2138): RFCOMM_CreateConnection - already opened state:2, RFC state:4, MCB state:5
E/bt-btif ( 2138): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/bt-btif ( 2138): invalid rfc slot id: 11
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 353)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Maximum number of allowed retries (0) reached, giving up... (thread ID: 353)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 353)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): shutdownAndRemoveClientThread: Shutting down thread with ID 353
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Exiting thread (thread ID: 353)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:9D:93:0B Thali Test's G2]
I/jxcore-log( 3577): 2016-01-08T14:58:05.486Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [34:FC:EF:9D:93:0B Thali Test's G2] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:58:05.486Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [34:FC:EF:9D:93:0B Thali Test's G2] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:58:05.486Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3577): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3577): setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): shutdown (thread ID: 353)
,I/jxcore-log( 3577): 2016-01-08T14:58:10.487Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:58:10.487Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3577): 
,I/io.jxcore.node.ConnectionHelper( 3577): Powering the BLE discovery back up
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3577): setAdvertiseMode: 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3577): applySettings: Advertise mode: 1, advertise TX power level: 1, scan mode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3577): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3577): setScanSettings: Mode: 0, report delay in milliseconds: 0, scan result type: 0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3577): setScanMode: 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3577): applySettings: Advertise mode: 1, advertise TX power level: 1, scan mode: 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3577): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3577): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/io.jxcore.node.ConnectionHelper( 3577): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3577): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
I/jxcore-log( 3577): 2016-01-08T14:58:15.491Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:58:15.491Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:58:15.492Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:58:15.493Z SendDataConnector.js: do connect now
I/jxcore-log( 3577): 
,I/io.jxcore.node.ConnectionHelper( 3577): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): connect: [34:FC:EF:9D:93:0B Thali Test's G2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): connect: Trying to start connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): setInsecureRfcommSocketPortNumber: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): onConnecting: Thali Test's G2 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): connect: Started connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3577): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 355)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3577): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3577): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2138): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2138): process_service_search_attr_rsp
,E/bt-rfcomm( 2138): RFCOMM_CreateConnection - already opened state:2, RFC state:4, MCB state:5
E/bt-btif ( 2138): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/bt-btif ( 2138): invalid rfc slot id: 12
W/BluetoothAdapter( 3577): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2138): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2138): process_service_search_attr_rsp
,E/bt-rfcomm( 2138): RFCOMM_CreateConnection - already opened state:2, RFC state:4, MCB state:5
E/bt-btif ( 2138): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/bt-btif ( 2138): invalid rfc slot id: 13
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 355)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Maximum number of allowed retries (0) reached, giving up... (thread ID: 355)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 355)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): shutdownAndRemoveClientThread: Shutting down thread with ID 355
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Exiting thread (thread ID: 355)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:9D:93:0B Thali Test's G2]
I/jxcore-log( 3577): 2016-01-08T14:58:15.981Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [34:FC:EF:9D:93:0B Thali Test's G2] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:58:15.981Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [34:FC:EF:9D:93:0B Thali Test's G2] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3577): 
I/jxcore-log( 3577): oneRoundDownNow
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:58:15.983Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:58:15.986Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3577): 
D/io.jxcore.node.ConnectionHelper( 3577): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3577): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
I/jxcore-log( 3577): 2016-01-08T14:58:15.991Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3577): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): shutdown (thread ID: 355)
,I/jxcore-log( 3577): ---- round done--------
I/jxcore-log( 3577): 
I/jxcore-log( 3577): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 1
I/jxcore-log( 3577): 
I/jxcore-log( 3577): startWithNextDevice
I/jxcore-log( 3577): 
I/jxcore-log( 3577): do fake peer & start
I/jxcore-log( 3577): 
I/jxcore-log( 3577): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:58:16.010Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:58:16.011Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:58:16.011Z SendDataConnector.js: do connect now
I/jxcore-log( 3577): 
,I/io.jxcore.node.ConnectionHelper( 3577): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 3577): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): connect: [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): setInsecureRfcommSocketPortNumber: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3577): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3577): setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): setConnectionTimeout: 15000
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 357)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3577): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3577): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2138): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): setState: RESTARTING
,I/wpa_supplicant( 1005): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1005): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1005): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1005): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1005): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 0 device(s) discovered,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 0 device(s) discovered
,W/bt-btif ( 2138): info:x10
,D/        ( 2138): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2138): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2138): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2138): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 2138): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2138): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2138): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2138): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2138): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2138): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2138): StableState(): Entering Off State
,W/bt-btif ( 2138): new conn_srvc id:26, app_id:1
W/bt-btif ( 2138): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2138): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): onSocketConnected: [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB] (thread ID: 357)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 357)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): onBytesWritten: 66 bytes successfully written (thread ID: 358)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Outgoing connection initialized (*handshake* thread ID: 358)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Exiting thread (thread ID: 357)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3577): Entering thread (ID: 358)
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): onBytesRead: Read 63 bytes successfully (thread ID: 358)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Handshake succeeded with [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): onHandshakeSucceeded: [7C:F9:0E:37:96:AB A5-1] (thread ID: 357)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3577): Exiting thread (ID: 358)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): onConnected: [7C:F9:0E:37:96:AB A5-1]
,I/io.jxcore.node.ConnectionHelper( 3577): onConnected: Outgoing connection to peer [7C:F9:0E:37:96:AB A5-1]
D/io.jxcore.node.ConnectionHelper( 3577): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3577): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
,I/io.jxcore.node.ConnectionHelper( 3577): onConnected: Outgoing socket thread, for peer [7C:F9:0E:37:96:AB A5-1], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3577): setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): setConnectionTimeout: 15000
D/io.jxcore.node.ConnectionHelper( 3577): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3577): Entering thread (ID: 359)
,D/io.jxcore.node.OutgoingSocketThread( 3577): Server socket local port: 41098
I/io.jxcore.node.OutgoingSocketThread( 3577): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3577): onListeningForIncomingConnections: Outgoing connection is using port 41098 (peer ID: 7C:F9:0E:37:96:AB)
I/jxcore-log( 3577): 2016-01-08T14:58:22.896Z SendDataConnector.js: CLIENT connected to 41098, error: null
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:58:22.896Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3577): 
,I/io.jxcore.node.OutgoingSocketThread( 3577): Incoming data from address: /127.0.0.1, port: 41098
D/io.jxcore.node.OutgoingSocketThread( 3577): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3577): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3577): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3577): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3577): Exiting thread (ID: 359)
,I/jxcore-log( 3577): 2016-01-08T14:58:22.919Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3577): 
,D/io.jxcore.node.StreamCopyingThread( 3577): Entering thread (ID: 360, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3577): Entering thread (ID: 361, name: Receiver)
,I/io.jxcore.node.ConnectionHelper( 3577): lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3577): setAdvertiseMode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3577): applySettings: Advertise mode: 0, advertise TX power level: 1, scan mode: 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3577): setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3577): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3577): setScanMode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3577): applySettings: Advertise mode: 0, advertise TX power level: 1, scan mode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3577): setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3577): setScanSettings: Mode: 0, report delay in milliseconds: 0, scan result type: 0
,D/        ( 2138): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:73010
,I/jxcore-log( 3577): 2016-01-08T14:58:24.057Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3577): 
,D/        ( 2138): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:63816
,I/jxcore-log( 3577): 2016-01-08T14:58:24.111Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3577): 
,D/        ( 2138): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:52926
,I/jxcore-log( 3577): 2016-01-08T14:58:24.190Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3577): 
,D/        ( 2138): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:43026
,I/jxcore-log( 3577): 2016-01-08T14:58:24.233Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3577): 
,D/        ( 2138): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:33126
,I/jxcore-log( 3577): 2016-01-08T14:58:24.351Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3577): 
,D/        ( 2138): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23226
,D/        ( 2138): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12336
,I/jxcore-log( 3577): 2016-01-08T14:58:24.464Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3577): 
,D/        ( 2138): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:456
,I/jxcore-log( 3577): 2016-01-08T14:58:24.609Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:58:24.666Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:58:24.771Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:58:24.772Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): oneRoundDownNow
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:58:24.777Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:58:24.778Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3577): 
D/io.jxcore.node.ConnectionHelper( 3577): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
I/io.jxcore.node.OutgoingSocketThread( 3577): close
D/io.jxcore.node.OutgoingSocketThread( 3577): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3577): doStop: Thread ID: 361
D/io.jxcore.node.OutgoingSocketThread( 3577): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3577): doStop: Thread ID: 360
D/io.jxcore.node.OutgoingSocketThread( 3577): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3577): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3577): Either failed to read from the output stream or write to the input stream (thread ID: 360, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3577): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3577): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB A5-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3577): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3577): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3577): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3577): Either failed to read from the output stream or write to the input stream (thread ID: 361, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3577): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3577): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB A5-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3577): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:37:96:AB
,E/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3577): Exiting thread (ID: 360, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
,W/bt-btif ( 2138): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3577): Exiting thread (ID: 361, name: Receiver)
,I/jxcore-log( 3577): 2016-01-08T14:58:24.819Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3577): 
I/jxcore-log( 3577): ---- round done--------
I/jxcore-log( 3577): 
I/jxcore-log( 3577): startWithNextDevice
I/jxcore-log( 3577): 
I/jxcore-log( 3577): do fake peer & start
I/jxcore-log( 3577): 
I/jxcore-log( 3577): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:58:24.819Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:58:24.819Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:58:24.819Z SendDataConnector.js: do connect now
I/jxcore-log( 3577): 
I/io.jxcore.node.ConnectionHelper( 3577): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): connect: [08:EC:A9:50:75:41 A3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): setInsecureRfcommSocketPortNumber: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3577): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 362)
W/BluetoothAdapter( 3577): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2138): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2138): No ag scb for peer addr
,W/bt-btif ( 2138): info:x10
,D/        ( 2138): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2138): aclStateChangeCallback: Device is NULL
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): Start timer timeout, starting now...
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,W/bt-sdp  ( 2138): process_service_search_attr_rsp
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2138): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2138): onReceive
,I/BTConnectionReceiver( 1403): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1403): Bluetooth Device Name: A5-1
,W/bt-btif ( 2138): info:x10
,D/        ( 2138): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 2138): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1005): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 3577): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service request added successfully
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service discovery started successfully
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2138): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2138): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2138): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2138): info:x10
,D/        ( 2138): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2138): aclStateChangeCallback: Device is NULL
,I/ActivityManager(  760): Killing 3182:com.google.android.apps.cloudprint:sync/u0a35 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10035/pid_3182/cgroup.procs: No such file or directory
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14),
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14)
,I/io.jxcore.node.ConnectionHelper( 3577): Powering the BLE discovery back up
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3577): setAdvertiseMode: 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3577): applySettings: Advertise mode: 1, advertise TX power level: 1, scan mode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3577): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3577): setScanSettings: Mode: 0, report delay in milliseconds: 0, scan result type: 0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3577): setScanMode: 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3577): applySettings: Advertise mode: 1, advertise TX power level: 1, scan mode: 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3577): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3577): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2138): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2138): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2138): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2138): info:x10
,D/        ( 2138): remote version info [f8:95:c7:87:85:54]: 7, f, 2205
,E/BluetoothRemoteDevices( 2138): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2138): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2138): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2138): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1005): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1005): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
,I/jxcore-log( 3577): timeout now
I/jxcore-log( 3577): 
I/jxcore-log( 3577): weAreDoneNow, resultArray.length: 1
I/jxcore-log( 3577): 
I/jxcore-log( 3577): sendReportNow
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): done, now sending data to server
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:58:51.052Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3577): 
,D/io.jxcore.node.ConnectionHelper( 3577): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3577): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
I/jxcore-log( 3577): 2016-01-08T14:58:51.065Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3577): 
,D/WifiP2pManager( 3577): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service request added successfully
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2138): info:x10
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2138): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2138): aclStateChangeCallback: Device is NULL
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service discovery started successfully
,I/wpa_supplicant( 1005): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Adding a new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 3577): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3577): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,D/btif_config_util( 2138): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2138): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2138): aclStateChangeCallback: Device is NULL
,W/bt-rfcomm( 2138): PORT_StartCnf failed result:5
E/bt-btm  ( 2138): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 2138): Do not find the bg connection mask for the remote device
,W/bt-btif ( 2138): invalid rfc slot id: 15
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 362)
,E/bt-btif ( 2138): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2138): No record of the device:null
I/BluetoothBondStateMachine( 2138): bondStateChangeCallback: Status: 9 Address: 08:EC:A9:50:75:41 newState: 0
E/BluetoothRemoteDevices( 2138): aclStateChangeCallback: Device is NULL
,E/BluetoothBondStateMachine( 2138): In stable state, received invalid newState: 10
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Maximum number of allowed retries (0) reached, giving up... (thread ID: 362)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 362)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): shutdownAndRemoveClientThread: Shutting down thread with ID 362
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Exiting thread (thread ID: 362)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:75:41 A3-1]
,I/jxcore-log( 3577): 2016-01-08T14:58:55.600Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:75:41 A3-1] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:58:55.600Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:75:41 A3-1] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:58:55.601Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3577): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3577): setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): shutdown (thread ID: 362)
,W/bt-btif ( 2138): info:x10
,D/        ( 2138): remote version info [e0:db:10:14:e2:c0]: 6, f, 410d
,E/BluetoothRemoteDevices( 2138): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 A3-1] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: false
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): modifyListOfDiscoveredPeers: Removed peer [08:EC:A9:50:75:41 A3-1]
,I/io.jxcore.node.ConnectionHelper( 3577): onPeerLost: [08:EC:A9:50:75:41 A3-1]
D/io.jxcore.node.ConnectionHelper( 3577): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3577): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] removed
D/io.jxcore.node.ConnectionHelper( 3577): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] not available
,I/BluetoothBondStateMachine( 2138): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 2138): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2138): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2138): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2138): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2138): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 2138): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2138): StableState(): Entering Off State
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Incoming connection initialized (thread ID: 364)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Waiting for incoming connections...
,W/bt-btif ( 2138): new conn_srvc id:26, app_id:255
W/bt-btif ( 2138): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2138): bta_dm_pm_ssr:2, lat:1200
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3577): Entering thread (ID: 364)
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): onBytesRead: Read 66 bytes successfully (thread ID: 364)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Got valid identity from [E0:DB:10:14:E2:C0 Note4-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): onBytesWritten: 66 bytes successfully written (thread ID: 364)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): removeThreadFromList: Removing thread with ID 364
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Handshake thread disposed (thread ID: 364)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3577): Exiting thread (ID: 364)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): onConnected: [E0:DB:10:14:E2:C0 Note4-1]
I/io.jxcore.node.ConnectionHelper( 3577): onConnected: Incoming connection to peer [E0:DB:10:14:E2:C0 Note4-1]
D/io.jxcore.node.ConnectionHelper( 3577): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3577): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 Note4-1] is available
I/io.jxcore.node.ConnectionHelper( 3577): onConnected: Incoming socket thread, for peer [E0:DB:10:14:E2:C0 Note4-1], created successfully
D/io.jxcore.node.ConnectionHelper( 3577): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3577): Entering thread (ID: 365)
,I/jxcore-log( 3577): 2016-01-08T14:59:00.390Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3577): 
,I/io.jxcore.node.IncomingSocketThread( 3577): Local host address: localhost/127.0.0.1, port: 49561
D/io.jxcore.node.IncomingSocketThread( 3577): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3577): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3577): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3577): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3577): Exiting thread (ID: 365)
,D/io.jxcore.node.StreamCopyingThread( 3577): Entering thread (ID: 367, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3577): Entering thread (ID: 366, name: Sender)
,I/jxcore-log( 3577): 2016-01-08T14:59:00.603Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:59:00.603Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.502Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 3577): 
,I/io.jxcore.node.ConnectionHelper( 3577): lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3577): setAdvertiseMode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3577): applySettings: Advertise mode: 0, advertise TX power level: 1, scan mode: 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3577): setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3577): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3577): setScanMode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3577): applySettings: Advertise mode: 0, advertise TX power level: 1, scan mode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3577): setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3577): setScanSettings: Mode: 0, report delay in milliseconds: 0, scan result type: 0
I/jxcore-log( 3577): 2016-01-08T14:59:01.520Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.529Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.530Z SendDataTCPServer.js: TCP/IP server has received 8910 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.534Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.538Z SendDataTCPServer.js: TCP/IP server has received 10890 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.542Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.574Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.582Z SendDataTCPServer.js: TCP/IP server has received 20790 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.585Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.623Z SendDataTCPServer.js: TCP/IP server has received 26730 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.626Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.630Z SendDataTCPServer.js: TCP/IP server has received 28710 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.634Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.637Z SendDataTCPServer.js: TCP/IP server has received 30690 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.641Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.674Z SendDataTCPServer.js: TCP/IP server has received 38610 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.675Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.679Z SendDataTCPServer.js: TCP/IP server has received 40590 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.683Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.713Z SendDataTCPServer.js: TCP/IP server has received 46530 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.716Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.724Z SendDataTCPServer.js: TCP/IP server has received 48510 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.727Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.797Z SendDataTCPServer.js: TCP/IP server has received 50490 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.804Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.835Z SendDataTCPServer.js: TCP/IP server has received 52470 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.847Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.865Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.875Z SendDataTCPServer.js: TCP/IP server has received 62370 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.888Z SendDataTCPServer.js: TCP/IP server has received 64350 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.925Z SendDataTCPServer.js: TCP/IP server has received 68310 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:01.987Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:02.061Z SendDataTCPServer.js: TCP/IP server has received 70290 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:02.127Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:02.166Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:02.204Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:02.211Z SendDataTCPServer.js: TCP/IP server has received 74250 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:02.299Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:59:02.304Z SendDataTCPServer.js: TCP/IP server has received 76230 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:02.372Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:59:02.376Z SendDataTCPServer.js: TCP/IP server has received 78210 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:02.445Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:02.515Z SendDataTCPServer.js: TCP/IP server has received 80190 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:02.525Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:02.568Z SendDataTCPServer.js: TCP/IP server has received 82170 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:02.597Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:02.606Z SendDataTCPServer.js: TCP/IP server has received 90090 bytes of data
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:59:02.622Z SendDataTCPServer.js: TCP/IP server has received 92070 bytes of data
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:59:02.655Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3577): 
,W/bt-btif ( 2138): invalid rfc slot id: 8
,W/io.jxcore.node.StreamCopyingThread( 3577): Either failed to read from the output stream or write to the input stream (thread ID: 367, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3577): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3577): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 Note4-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 365
D/io.jxcore.node.IncomingSocketThread( 3577): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3577): doStop: Thread ID: 367
D/io.jxcore.node.IncomingSocketThread( 3577): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3577): doStop: Thread ID: 366
D/io.jxcore.node.IncomingSocketThread( 3577): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3577): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3577): Either failed to read from the output stream or write to the input stream (thread ID: 366, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3577): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3577): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 Note4-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3577): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3577): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3577): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3577): Exiting thread (ID: 366, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3577): Exiting thread (ID: 367, name: Receiver)
,I/jxcore-log( 3577): 2016-01-08T14:59:02.745Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3577): 
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2138): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 2138): RFCOMM_DisconnectInd LCID:0x4a
,D/btif_config_util( 2138): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/io.jxcore.node.ConnectionHelper( 3577): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3577): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
I/jxcore-log( 3577): 2016-01-08T14:59:05.607Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:59:05.607Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:59:05.608Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:59:05.609Z SendDataConnector.js: do connect now
I/jxcore-log( 3577): 
I/io.jxcore.node.ConnectionHelper( 3577): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 3577): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): connect: [08:EC:A9:50:75:41 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): setInsecureRfcommSocketPortNumber: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3577): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 368)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3577): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3577): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2138): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2138): No ag scb for peer addr
,W/bt-btif ( 2138): info:x10
,D/        ( 2138): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2138): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1,
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2138): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2138): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 2138): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2138): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2138): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2138): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2138): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2138): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2138): StableState(): Entering Off State
,E/bt-btm  ( 2138): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2138): onReceive
,I/BTConnectionReceiver( 1403): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1403): Bluetooth Device Name: Note4-1
,W/bt-btif ( 2138): info:x10
,D/        ( 2138): remote version info [f8:95:c7:87:85:54]: 7, f, 2205
E/BluetoothRemoteDevices( 2138): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Incoming connection accepted
,W/bt-btif ( 2138): new conn_srvc id:26, app_id:255
W/bt-btif ( 2138): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2138): bta_dm_pm_ssr:2, lat:1200
,W/bt-btif ( 2138): new conn_srvc id:26, app_id:1
W/bt-btif ( 2138): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2138): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2138): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): onSocketConnected: [08:EC:A9:50:75:41 08:EC:A9:50:75:41] (thread ID: 368)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 368)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Incoming connection initialized (thread ID: 369)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): onBytesWritten: 66 bytes successfully written (thread ID: 370)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Outgoing connection initialized (*handshake* thread ID: 370)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Exiting thread (thread ID: 368)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3577): Entering thread (ID: 370)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3577): Entering thread (ID: 369)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): onBytesRead: Read 63 bytes successfully (thread ID: 370)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3577): Handshake succeeded with [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): onHandshakeSucceeded: [08:EC:A9:50:75:41 A3-1] (thread ID: 368)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3577): Exiting thread (ID: 370)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): onBytesRead: Read 63 bytes successfully (thread ID: 369)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Got valid identity from [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): onBytesWritten: 66 bytes successfully written (thread ID: 369)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): removeThreadFromList: Removing thread with ID 369
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Handshake thread disposed (thread ID: 369)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): onIncomingConnectionConnected: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3577): Exiting thread (ID: 369)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): onConnected: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): onConnected: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 3577): onConnected: Outgoing connection to peer [08:EC:A9:50:75:41 A3-1]
D/io.jxcore.node.ConnectionHelper( 3577): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3577): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
I/io.jxcore.node.ConnectionHelper( 3577): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:75:41 A3-1], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3577): setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): setConnectionTimeout: 15000
D/io.jxcore.node.ConnectionHelper( 3577): onConnected: The total number of connections is now 1
I/io.jxcore.node.ConnectionHelper( 3577): onConnected: Incoming connection to peer [08:EC:A9:50:75:41 A3-1]
D/io.jxcore.node.ConnectionHelper( 3577): hasConnection: We have an outgoing connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 3577): onConnected: Already connected with peer [08:EC:A9:50:75:41 A3-1], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3577): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3577): onConnected: Incoming socket thread, for peer [08:EC:A9:50:75:41 A3-1], created successfully
D/io.jxcore.node.ConnectionHelper( 3577): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 3577): Entering thread (ID: 371)
,D/io.jxcore.node.IncomingSocketThread( 3577): Entering thread (ID: 372)
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14)
,D/io.jxcore.node.IncomingSocketThread( 3577): Server socket local port: 54740
I/io.jxcore.node.IncomingSocketThread( 3577): Now accepting connections...
,I/io.jxcore.node.IncomingSocketThread( 3577): Local host address: localhost/127.0.0.1, port: 49561
D/io.jxcore.node.IncomingSocketThread( 3577): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3577): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3577): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3577): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3577): Exiting thread (ID: 372)
,I/jxcore-log( 3577): 2016-01-08T14:59:07.751Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3577): 
,D/io.jxcore.node.StreamCopyingThread( 3577): Entering thread (ID: 373, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3577): Entering thread (ID: 374, name: Receiver)
,I/BluetoothBondStateMachine( 2138): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2138): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2138): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2138): Entering PendingCommandState State
,I/io.jxcore.node.ConnectionHelper( 3577): onListeningForIncomingConnections: Outgoing connection is using port 54740 (peer ID: 08:EC:A9:50:75:41)
I/jxcore-log( 3577): 2016-01-08T14:59:08.050Z SendDataConnector.js: CLIENT connected to 54740, error: null
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:59:08.050Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3577): 
,I/io.jxcore.node.IncomingSocketThread( 3577): Incoming data from address: /127.0.0.1, port: 54740
D/io.jxcore.node.IncomingSocketThread( 3577): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3577): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3577): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3577): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3577): Exiting thread (ID: 371)
,I/jxcore-log( 3577): 2016-01-08T14:59:08.075Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3577): 
,D/io.jxcore.node.StreamCopyingThread( 3577): Entering thread (ID: 376, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3577): Entering thread (ID: 375, name: Sender)
,I/BluetoothBondStateMachine( 2138): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2138): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2138): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2138): StableState(): Entering Off State
,W/bt-btif ( 2138): new conn_srvc id:26, app_id:255
W/bt-btif ( 2138): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2138): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Incoming connection initialized (thread ID: 377)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3577): Entering thread (ID: 377)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): onBytesRead: Read 64 bytes successfully (thread ID: 377)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Got valid identity from [F8:95:C7:87:85:54 G3s-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): onBytesWritten: 66 bytes successfully written (thread ID: 377)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): removeThreadFromList: Removing thread with ID 377
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Handshake thread disposed (thread ID: 377)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): onIncomingConnectionConnected: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3577): Exiting thread (ID: 377)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): onConnected: [F8:95:C7:87:85:54 G3s-1]
D/        ( 2138): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:61130
,I/io.jxcore.node.ConnectionHelper( 3577): onConnected: Incoming connection to peer [F8:95:C7:87:85:54 G3s-1]
D/io.jxcore.node.ConnectionHelper( 3577): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 3577): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 G3s-1] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3577): onConnected: Incoming socket thread, for peer [F8:95:C7:87:85:54 G3s-1], created successfully
D/io.jxcore.node.ConnectionHelper( 3577): onConnected: The total number of connections is now 3
,I/jxcore-log( 3577): 2016-01-08T14:59:09.050Z SendDataTCPServer.js: TCP/IP server has received 31952 bytes of data
I/jxcore-log( 3577): 
,D/io.jxcore.node.IncomingSocketThread( 3577): Entering thread (ID: 378)
,I/jxcore-log( 3577): 2016-01-08T14:59:09.052Z SendDataTCPServer.js: TCP/IP server has received 32942 bytes of data
I/jxcore-log( 3577): 
,I/io.jxcore.node.IncomingSocketThread( 3577): Local host address: localhost/127.0.0.1, port: 49561
D/io.jxcore.node.IncomingSocketThread( 3577): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 3577): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3577): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3577): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3577): Exiting thread (ID: 378)
,I/jxcore-log( 3577): 2016-01-08T14:59:09.054Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3577): 
,D/io.jxcore.node.StreamCopyingThread( 3577): Entering thread (ID: 379, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3577): Entering thread (ID: 380, name: Receiver)
,I/jxcore-log( 3577): 2016-01-08T14:59:09.083Z SendDataTCPServer.js: TCP/IP server has received 34922 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.086Z SendDataTCPServer.js: TCP/IP server has received 35912 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.152Z SendDataTCPServer.js: TCP/IP server has received 36902 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.159Z SendDataTCPServer.js: TCP/IP server has received 37892 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.166Z SendDataTCPServer.js: TCP/IP server has received 38882 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.196Z SendDataTCPServer.js: TCP/IP server has received 39872 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.211Z SendDataTCPServer.js: TCP/IP server has received 40862 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.218Z SendDataTCPServer.js: TCP/IP server has received 41852 bytes of data
I/jxcore-log( 3577): 
,D/        ( 2138): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:66624
,I/jxcore-log( 3577): 2016-01-08T14:59:09.255Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.256Z SendDataTCPServer.js: TCP/IP server has received 48782 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.259Z SendDataTCPServer.js: TCP/IP server has received 49772 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.261Z SendDataTCPServer.js: TCP/IP server has received 50762 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.307Z SendDataTCPServer.js: TCP/IP server has received 51752 bytes of data
I/jxcore-log( 3577): 
,D/        ( 2138): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:58420
,I/jxcore-log( 3577): 2016-01-08T14:59:09.340Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.349Z SendDataTCPServer.js: TCP/IP server has received 58682 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.354Z SendDataTCPServer.js: TCP/IP server has received 59672 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.356Z SendDataTCPServer.js: TCP/IP server has received 60662 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.364Z SendDataTCPServer.js: TCP/IP server has received 61652 bytes of data
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:59:09.367Z SendDataTCPServer.js: TCP/IP server has received 62642 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.412Z SendDataTCPServer.js: TCP/IP server has received 66602 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.462Z SendDataTCPServer.js: TCP/IP server has received 67592 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.474Z SendDataTCPServer.js: TCP/IP server has received 68582 bytes of data
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:59:09.476Z SendDataTCPServer.js: TCP/IP server has received 69572 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.484Z SendDataTCPServer.js: TCP/IP server has received 70562 bytes of data
I/jxcore-log( 3577): 
,D/        ( 2138): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:48520
,I/jxcore-log( 3577): 2016-01-08T14:59:09.506Z SendDataTCPServer.js: TCP/IP server has received 71552 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.518Z SendDataConnector.js: CLIENT is data received : 30000,
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.520Z SendDataTCPServer.js: TCP/IP server has received 72542 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.543Z SendDataTCPServer.js: TCP/IP server has received 75512 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.553Z SendDataTCPServer.js: TCP/IP server has received 76502 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.564Z SendDataTCPServer.js: TCP/IP server has received 77492 bytes of data
I/jxcore-log( 3577): 
,D/        ( 2138): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:38620
,I/jxcore-log( 3577): 2016-01-08T14:59:09.603Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.624Z SendDataTCPServer.js: TCP/IP server has received 78482 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.631Z SendDataTCPServer.js: TCP/IP server has received 79472 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.638Z SendDataTCPServer.js: TCP/IP server has received 80462 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.643Z SendDataTCPServer.js: TCP/IP server has received 81452 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.684Z SendDataTCPServer.js: TCP/IP server has received 86402 bytes of data
I/jxcore-log( 3577): 
,D/        ( 2138): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:28720
,I/jxcore-log( 3577): 2016-01-08T14:59:09.686Z SendDataTCPServer.js: TCP/IP server has received 87392 bytes of data
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:59:09.687Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.694Z SendDataTCPServer.js: TCP/IP server has received 88382 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.704Z SendDataTCPServer.js: TCP/IP server has received 89372 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.710Z SendDataTCPServer.js: TCP/IP server has received 90362 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.752Z SendDataTCPServer.js: TCP/IP server has received 91352 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.785Z SendDataTCPServer.js: TCP/IP server has received 94322 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.788Z SendDataTCPServer.js: TCP/IP server has received 95312 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.794Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.801Z SendDataTCPServer.js: TCP/IP server has received 2970 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.817Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.822Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3577): 
,D/        ( 2138): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18820
,I/jxcore-log( 3577): 2016-01-08T14:59:09.832Z SendDataTCPServer.js: TCP/IP server has received 96302 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.836Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.846Z SendDataTCPServer.js: TCP/IP server has received 97292 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.852Z SendDataTCPServer.js: TCP/IP server has received 98282 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.856Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.860Z SendDataTCPServer.js: TCP/IP server has received 9182 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.863Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.869Z SendDataTCPServer.js: TCP/IP server has received 11162 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.905Z SendDataTCPServer.js: TCP/IP server has received 15122 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.936Z SendDataTCPServer.js: TCP/IP server has received 99272 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.942Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3577): 
,D/        ( 2138): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:6940
,I/jxcore-log( 3577): 2016-01-08T14:59:09.950Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:09.972Z SendDataTCPServer.js: TCP/IP server has received 23314 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.000Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3577): 
,D/        ( 2138): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1990
,I/jxcore-log( 3577): 2016-01-08T14:59:10.004Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.005Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.032Z SendDataTCPServer.js: TCP/IP server has received 31234 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.063Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.090Z SendDataTCPServer.js: TCP/IP server has received 39154 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.093Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.097Z SendDataTCPServer.js: TCP/IP server has received 41134 bytes of data
I/jxcore-log( 3577): 
,W/bt-btif ( 2138): invalid rfc slot id: 16
,W/io.jxcore.node.StreamCopyingThread( 3577): Either failed to read from the output stream or write to the input stream (thread ID: 374, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3577): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3577): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 A3-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 372
D/io.jxcore.node.IncomingSocketThread( 3577): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3577): doStop: Thread ID: 374
D/io.jxcore.node.IncomingSocketThread( 3577): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3577): doStop: Thread ID: 373
D/io.jxcore.node.IncomingSocketThread( 3577): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3577): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3577): Either failed to read from the output stream or write to the input stream (thread ID: 373, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3577): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3577): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 A3-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3577): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3577): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3577): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3577): Exiting thread (ID: 374, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3577): Exiting thread (ID: 373, name: Sender)
,I/jxcore-log( 3577): 2016-01-08T14:59:10.122Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.134Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.156Z SendDataTCPServer.js: TCP/IP server has received 47074 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.161Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.167Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.174Z SendDataTCPServer.js: TCP/IP server has received 51034 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.202Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.207Z SendDataTCPServer.js: TCP/IP server has received 54994 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.221Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.224Z SendDataTCPServer.js: TCP/IP server has received 56974 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.229Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.232Z SendDataTCPServer.js: TCP/IP server has received 58954 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.237Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.243Z SendDataTCPServer.js: TCP/IP server has received 60934 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.249Z SendDataTCPServer.js: TCP/IP server has received 62914 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.286Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.291Z SendDataTCPServer.js: TCP/IP server has received 68854 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.295Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.301Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.307Z SendDataTCPServer.js: TCP/IP server has received 72814 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.345Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.350Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:59:10.350Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3577): 
I/jxcore-log( 3577): oneRoundDownNow
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:59:10.351Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:59:10.351Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3577): 
,D/io.jxcore.node.ConnectionHelper( 3577): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
,I/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
I/io.jxcore.node.IncomingSocketThread( 3577): close
D/io.jxcore.node.IncomingSocketThread( 3577): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 3577): doStop: Thread ID: 376
D/io.jxcore.node.IncomingSocketThread( 3577): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3577): doStop: Thread ID: 375
D/io.jxcore.node.IncomingSocketThread( 3577): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3577): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3577): Either failed to read from the output stream or write to the input stream (thread ID: 375, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3577): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3577): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 A3-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3577): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3577): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3577): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3577): Either failed to read from the output stream or write to the input stream (thread ID: 376, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3577): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3577): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 A3-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3577): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:75:41
,E/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3577): Exiting thread (ID: 376, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3577): Exiting thread (ID: 375, name: Sender)
,I/jxcore-log( 3577): 2016-01-08T14:59:10.384Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.391Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3577): 
,W/bt-btif ( 2138): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/jxcore-log( 3577): 2016-01-08T14:59:10.421Z SendDataTCPServer.js: TCP/IP server has received 86674 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.425Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.463Z SendDataTCPServer.js: TCP/IP server has received 92614 bytes of data
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): 2016-01-08T14:59:10.503Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3577): 
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2138): invalid rfc slot id: 18
,W/io.jxcore.node.StreamCopyingThread( 3577): Either failed to read from the output stream or write to the input stream (thread ID: 380, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3577): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3577): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 G3s-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 378
D/io.jxcore.node.IncomingSocketThread( 3577): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3577): doStop: Thread ID: 380
D/io.jxcore.node.IncomingSocketThread( 3577): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3577): doStop: Thread ID: 379
D/io.jxcore.node.IncomingSocketThread( 3577): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3577): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3577): Either failed to read from the output stream or write to the input stream (thread ID: 379, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3577): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3577): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 G3s-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3577): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3577): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3577): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3577): Exiting thread (ID: 380, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3577): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3577): Exiting thread (ID: 379, name: Sender)
,I/jxcore-log( 3577): 2016-01-08T14:59:10.762Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3577): 
,E/bt-btm  ( 2138): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 2138): bta_dm_check_av:0
,W/bt-btif ( 2138): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2138): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
W/bt-rfcomm( 2138): RFCOMM_DisconnectInd LCID:0x4f
,I/jxcore-log( 3577): teardown
I/jxcore-log( 3577): 
,I/jxcore-log( 3577): testSendData stopped
I/jxcore-log( 3577): 
I/io.jxcore.node.ConnectionHelper( 3577): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3577): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3577): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3577): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3577): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): stop: Stopping peer discovery...,
,D/BluetoothLeScanner( 3577): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3577): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 1005): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1005): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1005): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1005): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1005): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3577): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3577): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3577): setState: NOT_STARTED
,I/jxcore-log( 3577): StopBroadcasting went ok
I/jxcore-log( 3577): 
I/jxcore-log( 3577): 2016-01-08T14:59:11.038Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3577): 
I/chromium( 3577): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3577): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3577): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3577): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3577): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3577): onDiscoveryManagerStateChanged: NOT_STARTED
,D/btif_config_util( 2138): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3577): ****TEST TOOK:  ms ****
I/jxcore-log( 3577): 
I/jxcore-log( 3577): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3577): 
,D/AndroidRuntime( 4040): 
D/AndroidRuntime( 4040): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4040): CheckJNI is OFF
,D/AndroidRuntime( 4040): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  760): Killing 3577:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,W/PackageSettings(  760): Skipping PackageSetting{31ec7f4f com.example.hello/10278} due to missing metadata
,I/WindowState(  760): WIN DEATH: Window{18c73780 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  760): Client connection lost with reason: 4
,I/ActivityManager(  760):   Force finishing activity ActivityRecord{167374c u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  760): Spurious death for ProcessRecord{bb89be2 3577:com.test.thalitest/u0a270}, curProc for 3577: null
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  760):   Force finishing activity ActivityRecord{167374c u0 com.test.thalitest/.MainActivity t214 f}
,W/ActivityManager(  760): Duplicate finish request for ActivityRecord{167374c u0 com.test.thalitest/.MainActivity t214 f}
,I/art     ( 1403): Explicit concurrent mark sweep GC freed 21490(1131KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 18MB/25MB, paused 294us total 55.736ms
,I/art     ( 1676): Explicit concurrent mark sweep GC freed 10902(523KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 23MB/30MB, paused 1.069ms total 61.897ms
,W/GeofencerStateMachine( 1610): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1059): resetDictionaries() : en_US
D/NetworkChangeNotifierAutoDetect(  944): Network connectivity changed, type is: 2
,I/art     ( 1270): Explicit concurrent mark sweep GC freed 6775(519KB) AllocSpace objects, 2(253KB) LOS objects, 38% free, 25MB/41MB, paused 4.476ms total 58.768ms
,I/LibraryLoader( 1526): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
,I/Keyboard.Facilitator.DecoderInitializer( 1059): run()
,I/art     (  760): Explicit concurrent mark sweep GC freed 40886(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 1.108ms total 84.891ms
I/art     (  760): WaitForGcToComplete blocked for 93.799ms for cause Explicit
,I/UpdateIcingCorporaServi( 1403): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/VoicemailCleanupService( 1333): Cleaning up data for package: com.test.thalitest,
,I/Decoder ( 1059): createOrResetDecoder
,W/Launcher( 1270): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@20a7a8c8 new=com.google.android.velvet.VelvetApplication@20a7a8c8
,I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4078 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/LibraryLoader( 1526): Time to load native libraries: 66 ms (timestamps 3611-3677)
I/LibraryLoader( 1526): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/chromium( 1526): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 1526): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1526): Attempt to remove local handle scope entry from IRT, ignoring
I/art     (  194): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 178us total 9.457ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 179us total 7.846ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 169us total 7.748ms
,I/OpenGLRenderer(  944): Initialized EGL, version 1.4
,I/ConfigService( 1610): onCreate
,D/OpenGLRenderer(  944): Enabling debug mode 0
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     (  760): Explicit concurrent mark sweep GC freed 7020(377KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 2.824ms total 135.365ms
,D/TaskPersister(  760): removeObsoleteFile: deleting file=214_task.xml
,W/InputMethodManagerService(  760): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@e1e5052 (uid=10034 pid=944)
,I/UpdateIcingCorporaServi( 1403): UpdateCorporaTask done [took 163 ms] updated apps [took 163 ms] 
,W/ContextImpl( 4078): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1059): run()
,D/PackageBroadcastService( 1676): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1676): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1676): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1676): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1676): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1676): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1610): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1610): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/InputMethodManagerService(  760): Got RemoteException sending setActive(false) notification to pid 3577 uid 10270
,I/Keyboard.Facilitator( 1059): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1059): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1059): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1059): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1059): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1059): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1059): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1059): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1059): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1059): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1059): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1059): run()
I/StatsUtilsManager( 1059): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1059): shouldRecordStats() = Too Soon
,I/Launcher( 1270): Deferring update until onResume
,I/LocationSettingsChecker( 1676): Removing dialog suppression flag for package com.test.thalitest
,W/ResourcesManager( 1270): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/gH_CompatibleDatabase( 1676): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1676): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1676): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1676): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1676): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1676): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1676): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1676): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1676): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1676): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1676): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1676): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1676): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/ResourcesManager( 1270): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  760): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4121 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/Launcher( 1270): Deferring update until onResume
,D/AndroidRuntime( 4040): Shutting down VM
,W/art     ( 1676): No such thread id for suspend: 50
,I/GMPM-SVC( 1676): App measurement is starting up, version: 8489
I/GMPM-SVC( 1676): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1676): Using Auth Proxy for data requests.
,W/BaseAppContext( 1676): Using Auth Proxy for data requests.
,I/Icing   ( 1676): doRemovePackageData com.test.thalitest
,I/ActivityManager(  760): Killing 2044:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10031/pid_2044/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4151 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 3387:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10008/pid_3387/cgroup.procs: No such file or directory
,D/ExternalStorage( 4151): After updating volumes, found 1 active roots
,D/Documents( 4121): Update found 7 roots in 248ms
,D/Documents( 4121): Update found 7 roots in 85ms

```
