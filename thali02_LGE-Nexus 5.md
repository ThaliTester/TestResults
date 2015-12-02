#### Test 5198634075bb434_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1617): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1617): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3116): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3116):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3116):   adb logcat -s GAv4
W/GAv4    ( 3116): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3116): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3116): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3116): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
--------- beginning of system
W/ResourcesManager( 3116): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3116): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 3116): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
D/Finsky  ( 2637): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  756): Killing 2029:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/System  ( 3116): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3116): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  756): failed to open /acct/uid_10038/pid_2029/cgroup.procs: No such file or directory
V/GLSActivity( 1379): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1617): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Icing   ( 1617): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1617): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,I/ActivityManager(  756): Killing 2586:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/libprocessgroup(  756): failed to open /acct/uid_10069/pid_2586/cgroup.procs: No such file or directory
D/AndroidRuntime( 3197): 
D/AndroidRuntime( 3197): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3197): CheckJNI is OFF
D/AndroidRuntime( 3197): Calling main entry com.android.commands.am.Am
I/ActivityManager(  756): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  756): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3218 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3197): Shutting down VM
I/art     (  195): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 384us total 17.824ms
V/ActivityManager(  756): Display changed displayId=0
I/art     (  195): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 354us total 15.432ms
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 354us total 15.327ms
I/WebViewFactory( 3218): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3218): Time to load native libraries: 2 ms (timestamps 8085-8087)
I/LibraryLoader( 3218): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3218): Binding Chromium to main looper Looper (main, tid 1) {331fad33}
I/LibraryLoader( 3218): Expected native library version number "",actual native library version number ""
I/chromium( 3218): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3218): Initializing chromium process, singleProcess=true
,W/art     ( 3218): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3218): ApplicationContext is null in ApplicationStatus
,W/chromium( 3218): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3218): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3218): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3218): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  756): Message: 20
D/BluetoothManagerService(  756): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d14bda8:true
,W/art     ( 3218): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3218): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3218): CordovaWebView is running on device made by: LGE
,W/art     ( 3218): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3218): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3218): Render dirty regions requested: true
,D/Atlas   ( 3218): Validating map...
,W/chromium( 3218): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3218): Initialized EGL, version 1.4
D/OpenGLRenderer( 3218): Enabling debug mode 0
,I/Keyboard.Facilitator( 1062): onFinishInput()
,W/IInputConnectionWrapper( 3218): showStatusIcon on inactive InputConnection
,I/ActivityManager(  756): Displayed com.test.thalitest/.MainActivity: +469ms (total +55s406ms)
,W/BindingManager( 3218): Cannot call determinedVisibility() - never saw a connection for the pid: 3218
,D/JsMessageQueue( 3218): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3218): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3218): jxcore cordova android initializing
,W/jxcore-log( 3218): Initializing JXcore engine
W/jxcore-log( 3218): JXcore engine is ready
,W/jxcore-log( 3218): Starting JXcore engine
,W/.test.thalitest( 3218): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8398]" dev="sockfs" ino=8398 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3218): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3218): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8477]" dev="sockfs" ino=8477 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3218): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20064]" dev="sockfs" ino=20064 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3218): Platform android
W/jxcore-log( 3218): 
W/jxcore-log( 3218): Process ARCH arm
W/jxcore-log( 3218): 
,I/jxcore-log( 3218): JXcore Cordova bridge is ready!
I/jxcore-log( 3218): 
W/jxcore-log( 3218): JXcore engine is started
I/Choreographer( 3218): Skipped 109 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3218): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3218): Toggling radios to true
I/jxcore-log( 3218): 
,D/BluetoothAdapter( 3218): enable(): BT is already enabled..!
,D/WifiService(  756): setWifiEnabled: true pid=3218, uid=10270
E/WifiService(  756): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  756): New client listening to asynchronous messages
,I/jxcore-log( 3218): Radios toggled
I/jxcore-log( 3218): 
,I/wpa_supplicant( 1046): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  756): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  756): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1379): Read error: ssl=0x9c81ae00: I/O error during system call, Connection timed out
,D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
V/NativeCrypto( 1379): SSL shutdown failed: ssl=0x9c81ae00: I/O error during system call, Broken pipe
,D/ConnectivityService(  756): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  756): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1046): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  756): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  756): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/Nat464Xlat(  756): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  756): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  756): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1197): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): EvaluatingState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
,D/ConnectivityManager.CallbackHandler( 1617): CM callback handler got msg 524292
,D/WifiNetworkAgent(  756): NetworkAgent: NetworkAgent channel lost
E/ConnectivityService(  756): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/wpa_supplicant( 1046): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1046): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1046): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1046): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  756): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
,E/WifiStateMachine(  756): Start Dhcp Watchdog 2
,E/native  (  756): do suspend false
,E/WifiStateMachine(  756): scanCount==0 - aborting
,D/BluetoothManagerService(  756): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3218): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): my name is : LGE-Nexus 5_PT5213
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): attempting to connect to test coordinator
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): check test folder
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): found test : ./testFindPeers.js
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): found test : ./testReConnect.js
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): found test : ./testSendData.js
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): Test app app.js loaded
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/Choreographer( 3218): Skipped 114 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3218): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/dhcpcd  ( 3319): version 5.5.6 starting
,E/dhcpcd  ( 3319): get_duid: Read-only file system
,I/dhcpcd  ( 3319): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3319): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3319): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  756): do suspend true
,D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  756): Adding iface wlan0 to network 101
,E/WifiStateMachine(  756): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  756): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  756): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  756): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  756): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  756): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  756): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  756): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  756): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  756): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  756): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1617): CM callback handler got msg 524290
,D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 02 Dec 2015 13:32:10 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449063130891], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449063130871]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Validated
,D/ConnectivityService(  756): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  756): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1197): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1617): CM callback handler got msg 524290
,I/NetworkMonitor( 2743): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 2743): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  756): No APN found to select.
,V/MusicLeanback( 2743): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  756): No APN found to select.
,D/ChimeraCfgMgr( 1617): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1617): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/SystemUpdateService( 1617): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1617): onCreate
,D/SystemUpdateService( 1617): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,V/GLSActivity( 1379): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SystemUpdateService( 1617): active receiver: enabled
V/GLSActivity( 1379): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemUpdateService( 1617): showing system update notification
,I/ValidateNoPeople(  756): skipping global notification
,V/SystemUpdateService( 1617): retry (wakeup: false) in 3599976 ms
,I/ActivityManager(  756): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3382 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1617): onDestroy
,V/GLSActivity( 1379): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1379): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/GAv4    ( 3382): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3382):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3382):   adb logcat -s GAv4
,W/GAv4    ( 3382): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3382): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3382): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/Nat464Xlat(  756): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  756): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1617): CM callback handler got msg 524295
,I/WebViewFactory( 3382): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3382): Time to load native libraries: 1 ms (timestamps 4178-4179)
,I/LibraryLoader( 3382): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3382): Binding Chromium to main looper Looper (main, tid 1) {26987a2d}
,I/LibraryLoader( 3382): Expected native library version number "",actual native library version number ""
,I/chromium( 3382): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3382): Initializing chromium process, singleProcess=true
,W/art     ( 3382): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3382): ApplicationContext is null in ApplicationStatus
,W/chromium( 3382): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3382): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3382): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3382): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3382): Requires BLUETOOTH permission
,I/NSApplication( 3382): Starting up...
,I/ActivityManager(  756): Killing 2535:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10045/pid_2535/cgroup.procs: No such file or directory
,V/MusicLeanback( 2743): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ChimeraCfgMgr( 1617): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/SystemUpdateService( 1617): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1617): onCreate
,D/SystemUpdateService( 1617): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1617): active receiver: enabled
,I/SystemUpdateService( 1617): showing system update notification
,I/ValidateNoPeople(  756): skipping global notification
,V/SystemUpdateService( 1617): retry (wakeup: false) in 3599983 ms
,D/SystemUpdateService( 1617): onDestroy
,I/art     (  756): Explicit concurrent mark sweep GC freed 43575(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.406ms total 121.458ms
,V/GLSActivity( 1379): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1379): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  756): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  756): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2743): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2743): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ChimeraCfgMgr( 1617): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1617): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/SystemUpdateService( 1617): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1617): onCreate
,D/SystemUpdateService( 1617): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1617): active receiver: enabled
,I/SystemUpdateService( 1617): showing system update notification
,E/GpsLocationProvider(  756): No APN found to select.
,I/ValidateNoPeople(  756): skipping global notification
,V/GLSActivity( 1379): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/SystemUpdateService( 1617): retry (wakeup: false) in 3599965 ms
,D/SystemUpdateService( 1617): onDestroy
,V/GLSActivity( 1379): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3218): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,D/Finsky  ( 2637): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2637): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,V/GLSActivity( 1379): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1379): Vacuum at: now=1449063145992 tag=VacuumService
,D/UdcCache:FPQuery( 1617): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1379): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1379): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetConfigurationSnapshotOperation( 1379): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1379): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1379): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1379): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1379): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1379):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1379): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1379): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1379): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1379): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1379): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1379): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1062): run()
I/Keyboard.Facilitator( 1062): flushDynamicLanguageModels()
,I/ConfigService( 1379): onCreate
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/ConfigService( 1379): onDestroy
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/ClearcutLoggerApiImpl( 1379): disconnect managed GoogleApiClient
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/ClearcutLoggerApiImpl( 1569): disconnect managed GoogleApiClient
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,E/DataBuffer( 1379): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@34adbdd6)
,E/DataBuffer( 1379): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@7553857)
E/DataBuffer( 1379): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@bdaf44)
,E/DataBuffer( 1379): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2ec2882d)
E/DataBuffer( 1379): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2e1fe162)
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/ActivityManager(  756): Killing 2721:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10003/pid_2721/cgroup.procs: No such file or directory
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/ActivityManager(  756): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3582 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3582): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3582):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3582):   adb logcat -s GAv4
,W/GAv4    ( 3582): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3582): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3582): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  756): Killing 2695:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  756): Client connection lost with reason: 4
,W/libprocessgroup(  756): failed to open /acct/uid_1000/pid_2695/cgroup.procs: No such file or directory
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,W/bt-smp  ( 2073): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2073): Plain text(LSB ~ MSB) = a5 e8 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2073): Encrypted text(LSB ~ MSB) = ac 02 20 00 99 e6 cb 8e 6e 9c d5 6d c9 a3 67 0f 
,W/bt-btm  ( 2073): Stopping oneshot timer
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/UsageStatsService(  756): User[0] Flushing usage stats to disk
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,W/bt-smp  ( 2073): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2073): Plain text(LSB ~ MSB) = af ad 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2073): Encrypted text(LSB ~ MSB) = 31 7c f1 dc 7b fb b1 6a 3e 9c 04 5d 9c 9a 33 b8 
,W/bt-btm  ( 2073): Stopping oneshot timer
,I/ProcessStatsService(  756): Prepared write state in 31ms
,I/ProcessStatsService(  756): Prepared write state in 7ms
,I/ProcessStatsService(  756): Pruning old procstats: /data/system/procstats/state-2015-12-01-17-48-11.bin
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/ActivityManager(  756): Killing 2974:com.google.android.gms:car/u0a8 (adj 13): empty for 1803s
,I/ActivityManager(  756): Killing 1988:com.android.providers.calendar/u0a2 (adj 15): empty for 1804s
,I/ActivityManager(  756): Killing 1966:com.google.android.calendar/u0a31 (adj 15): empty for 1835s
,I/ActivityManager(  756): Killing 2555:com.google.android.gm/u0a70 (adj 15): empty for 1835s
,W/libprocessgroup(  756): failed to open /acct/uid_10008/pid_2974/cgroup.procs: No such file or directory
,W/libprocessgroup(  756): failed to open /acct/uid_10002/pid_1988/cgroup.procs: No such file or directory
,W/libprocessgroup(  756): failed to open /acct/uid_10031/pid_1966/cgroup.procs: No such file or directory
,W/libprocessgroup(  756): failed to open /acct/uid_10070/pid_2555/cgroup.procs: No such file or directory
,I/EventLogService( 1617): Aggregate from 1449062796188 (log), 1449062796188 (data)
,V/GLSActivity( 1379): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1379): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/ActivityManager(  756): Killing 1452:com.google.android.partnersetup/u0a13 (adj 13): empty for 1802s
,I/ActivityManager(  756): Killing 1344:android.process.acore/u0a4 (adj 15): empty for 1802s
,W/libprocessgroup(  756): failed to open /acct/uid_10004/pid_1344/cgroup.procs: No such file or directory
,W/libprocessgroup(  756): failed to open /acct/uid_10013/pid_1452/cgroup.procs: No such file or directory
,I/ActivityManager(  756): Killing 3075:com.android.musicfx/u0a15 (adj 15): empty for 1802s
,W/libprocessgroup(  756): failed to open /acct/uid_10015/pid_3075/cgroup.procs: No such file or directory
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3218): 
,TIME-OUT KILL (timeout was 1800000ms)
```
