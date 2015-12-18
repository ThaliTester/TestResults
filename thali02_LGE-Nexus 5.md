#### Test 539786637913587_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/Finsky  ( 2598): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3175): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3175): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  733): Killing 2564:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3175): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3175): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3175): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  733): failed to open /acct/uid_10069/pid_2564/cgroup.procs: No such file or directory
V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1627): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1627): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1627): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1627): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3248): 
D/AndroidRuntime( 3248): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3248): CheckJNI is OFF
D/AndroidRuntime( 3248): Calling main entry com.android.commands.am.Am
I/ActivityManager(  733): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  733): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3272 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3248): Shutting down VM
V/ActivityManager(  733): Display changed displayId=0
I/WebViewFactory( 3272): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3272): Time to load native libraries: 1 ms (timestamps 8356-8357)
I/LibraryLoader( 3272): Expected native library version number "",actual native library version number ""
I/ActivityManager(  733): Killing 2520:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
V/WebViewChromiumFactoryProvider( 3272): Binding Chromium to main looper Looper (main, tid 1) {127cec7c}
I/LibraryLoader( 3272): Expected native library version number "",actual native library version number ""
I/chromium( 3272): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3272): Initializing chromium process, singleProcess=true
W/art     ( 3272): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3272): ApplicationContext is null in ApplicationStatus
W/libprocessgroup(  733): failed to open /acct/uid_10045/pid_2520/cgroup.procs: No such file or directory
W/chromium( 3272): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3272): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3272): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3272): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  733): Message: 20
D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bd8d753:true
,W/art     ( 3272): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3272): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3272): CordovaWebView is running on device made by: LGE
,W/art     ( 3272): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3272): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3272): Render dirty regions requested: true
,D/Atlas   ( 3272): Validating map...
,W/chromium( 3272): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3272): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3272): Enabling debug mode 0
,W/IInputConnectionWrapper( 3272): showStatusIcon on inactive InputConnection
,I/ActivityManager(  733): Displayed com.test.thalitest/.MainActivity: +435ms (total +57s515ms)
,W/BindingManager( 3272): Cannot call determinedVisibility() - never saw a connection for the pid: 3272
,D/JsMessageQueue( 3272): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3272): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,D/JX-Cordova( 3272): jxcore cordova android initializing
,W/jxcore-log( 3272): Initializing JXcore engine
,W/jxcore-log( 3272): JXcore engine is ready
,W/jxcore-log( 3272): Starting JXcore engine
,W/.test.thalitest( 3272): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8039]" dev="sockfs" ino=8039 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3272): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 3272): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8082]" dev="sockfs" ino=8082 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3272): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19843]" dev="sockfs" ino=19843 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3272): Platform android
W/jxcore-log( 3272): 
W/jxcore-log( 3272): Process ARCH arm
W/jxcore-log( 3272): 
,I/jxcore-log( 3272): JXcore Cordova bridge is ready!
I/jxcore-log( 3272): 
,W/jxcore-log( 3272): JXcore engine is started
,I/Choreographer( 3272): Skipped 111 frames!  The application may be doing too much work on its main thread.
I/chromium( 3272): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3272): Toggling radios to true
I/jxcore-log( 3272): 
,D/BluetoothAdapter( 3272): enable(): BT is already enabled..!
,D/WifiService(  733): New client listening to asynchronous messages
D/WifiService(  733): setWifiEnabled: true pid=3272, uid=10270
E/WifiService(  733): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3272): Radios toggled
I/jxcore-log( 3272): 
,I/wpa_supplicant( 1019): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  733): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  733): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1572): Read error: ssl=0xaf8afc00: I/O error during system call, Connection timed out
,E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,V/NativeCrypto( 1572): SSL shutdown failed: ssl=0xaf8afc00: I/O error during system call, Broken pipe
,E/WifiStateMachine(  733): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1019): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/ConnectivityService(  733): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,E/native  (  733): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService(  733): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  733): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  733): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler(  888): CM callback handler got msg 524292
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1627): CM callback handler got msg 524292
D/ConnectivityService(  733): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1251): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  733): NetworkAgent: NetworkAgent channel lost
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1466): OkHttp exception
W/EventLoggerService( 1466): Unable to send logs Error code: 262146
,I/wpa_supplicant( 1019): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1019): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1019): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1019): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  733): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  733): Start Dhcp Watchdog 2
,E/native  (  733): do suspend false
,E/WifiStateMachine(  733): scanCount==0 - aborting
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3272): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): my name is : LGE-Nexus 5_PT8301
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): attempting to connect to test coordinator
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): check test folder
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): found test : ./testFindPeers.js
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): found test : ./testReConnect.js
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): found test : ./testSendData.js
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): Test app app.js loaded
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
I/chromium( 3272): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/dhcpcd  ( 3357): version 5.5.6 starting
E/dhcpcd  ( 3357): get_duid: Read-only file system
,I/dhcpcd  ( 3357): wlan0: rebinding lease of 192.168.1.114
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  733): MasterInitialState.processMessage what=3
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  733): MasterInitialState.processMessage what=3
,I/dhcpcd  ( 3357): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,V/MusicLeanback( 2733): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/dhcpcd  ( 3357): wlan0: leased 192.168.1.114 for 86400 seconds
,I/SystemUpdateService( 1627): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1627): onCreate
,D/SystemUpdateService( 1627): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1627): active receiver: enabled
,I/iu.Environment( 1627): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1627): num queued entries: 0
I/iu.UploadsManager( 1627): num updated entries: 0
I/iu.SyncManager( 1627): NEXT; no task
,I/SystemUpdateService( 1627): showing system update notification
,E/GpsLocationProvider(  733): No APN found to select.
,I/Babel   ( 1888): connection state changed from CONNECTED to DISCONNECTED
,I/ValidateNoPeople(  733): skipping global notification
,V/SystemUpdateService( 1627): retry (wakeup: false) in 3599975 ms
,I/ActivityManager(  733): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3398 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1627): onDestroy
,E/GpsLocationProvider(  733): No APN found to select.
,I/GAv4    ( 3398): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3398):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3398):   adb logcat -s GAv4
,E/native  (  733): do suspend true
,W/GAv4    ( 3398): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  733): Adding iface wlan0 to network 101
,E/WifiStateMachine(  733): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  733): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  733): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  733): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  733): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  733): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  733): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  733): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  733):    accepting network in place of null
,D/CSLegacyTypeTracker(  733): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  733): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  733): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  888): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1627): CM callback handler got msg 524290
,W/GAv4    ( 3398): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3398): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 18 Dec 2015 12:46:49 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450442809772], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450442809722]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Validated
D/ConnectivityService(  733): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  733): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  888): CM callback handler got msg 524290
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1627): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1251): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WebViewFactory( 3398): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3398): Time to load native libraries: 1 ms (timestamps 4566-4567)
,I/LibraryLoader( 3398): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3398): Binding Chromium to main looper Looper (main, tid 1) {129e50e}
,I/LibraryLoader( 3398): Expected native library version number "",actual native library version number ""
I/chromium( 3398): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3398): Initializing chromium process, singleProcess=true
,W/art     ( 3398): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3398): ApplicationContext is null in ApplicationStatus
,W/chromium( 3398): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3398): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3398): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3398): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3398): Requires BLUETOOTH permission
,I/NSApplication( 3398): Starting up...
,I/ActivityManager(  733): Killing 2705:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10003/pid_2705/cgroup.procs: No such file or directory
,V/MusicLeanback( 2733): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1627): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1627): onCreate
,D/SystemUpdateService( 1627): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1627): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1627): active receiver: enabled
,I/iu.UploadsManager( 1627): num queued entries: 0
,I/iu.UploadsManager( 1627): num updated entries: 0
,I/SystemUpdateService( 1627): showing system update notification
,I/iu.SyncManager( 1627): NEXT; no task
,I/ValidateNoPeople(  733): skipping global notification
,V/SystemUpdateService( 1627): retry (wakeup: false) in 3599960 ms
,D/SystemUpdateService( 1627): onDestroy
,I/Babel   ( 1888): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,D/ConnectivityService(  733): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  733): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2733): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2733): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1627): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1627): onCreate
,D/SystemUpdateService( 1627): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1627): active receiver: enabled
,I/SystemUpdateService( 1627): showing system update notification
,I/ValidateNoPeople(  733): skipping global notification
,V/SystemUpdateService( 1627): retry (wakeup: false) in 3599980 ms
,D/SystemUpdateService( 1627): onDestroy
,I/art     (  733): Explicit concurrent mark sweep GC freed 45804(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.206ms total 64.855ms
,E/GpsLocationProvider(  733): No APN found to select.
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3272): BLE supported!!
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,D/Finsky  ( 2598): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2598): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/ActivityManager(  733): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3538 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 3538): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3538): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/VacuumService( 1572): Vacuum at: now=1450442822201 tag=VacuumService
,V/JNIHelp ( 3538): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 3538): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3538): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 3538): Bogus value in shared preferences for key MdxServerSelection value , returning default value.,
,I/dex2oat ( 3573): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads454245245.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads454245245.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3573): dex2oat took 52.581ms (threads: 4)
,W/InstanceID/Rpc( 3538): Found 10008
,I/ActivityManager(  733): Killing 2676:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  733): Client connection lost with reason: 4
,W/libprocessgroup(  733): failed to open /acct/uid_1000/pid_2676/cgroup.procs: No such file or directory
,I/PhenotypeConfigurator( 1572): Scheduling Phenotype for one-off execution 6708 seconds from now (1450442823166)
,D/GetConfigurationSnapshotOperation( 1572): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1572): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1572): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/ClearcutLoggerApiImpl( 1572): disconnect managed GoogleApiClient
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector connect called
I/jxcore-log( 3272): 
I/jxcore-log( 3272): Coordinator is now connected to the server!
I/jxcore-log( 3272): 
,I/chromium( 3272): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3272): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector command called
I/jxcore-log( 3272): 
I/jxcore-log( 3272): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":20000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":16,"addressList":[{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0}]}
I/jxcore-log( 3272): 
I/jxcore-log( 3272): Start now : testSendData.js
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 16
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): check server
I/jxcore-log( 3272): 
I/jxcore-log( 3272): serverPort is 55815
I/jxcore-log( 3272): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT8301
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3272): bind: Binding a new listener
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3272): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3272): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8301","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): start: OK
I/io.jxcore.node.ConnectionHelper( 3272): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT8301
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3272): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8301","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3272): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8301","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3272): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8301","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3272): start: OK
I/jxcore-log( 3272): StartBroadcasting started ok
I/jxcore-log( 3272): 
I/jxcore-log( 3272): do fake peer & start
I/jxcore-log( 3272): 
I/jxcore-log( 3272): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:53:32.110Z SendDataConnector.js: Start called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:53:32.110Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:53:32.110Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
W/io.jxcore.node.ConnectionHelper( 3272): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to null in address F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: null F8:CF:C5:D9:E5:61
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to null in address F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: F8:CF:C5:D9:E5:61)
,I/jxcore-log( 3272): 2015-12-18T12:53:32.120Z SendDataTCPServer.js: TCP/IP server is bound to port: 55815
I/jxcore-log( 3272): 
I/chromium( 3272): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3272): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3272): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3272): onDiscoveryManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address F8:CF:C5:D9:E5:61 (thread ID: 308)
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2072): info:x10
,D/        ( 2072): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 2072): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2072): info:x10
,D/        ( 2072): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
E/BluetoothRemoteDevices( 2072): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 2072): bta_dm_check_av:0
,W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=0
W/bt-btif ( 2072): bta_dm_check_av:0
,W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2072): process_service_search_attr_rsp
,W/bt-btif ( 2072): info:x10
,D/        ( 2072): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 2072): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
,E/bt-btif ( 2072): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2072): Entering PendingCommandState State
,I/ActivityManager(  733): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=3712 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BluetoothManagerService(  733): Message: 20
D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a32870:true
,I/ActivityManager(  733): Killing 2538:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10070/pid_2538/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 2072): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,E/bt-btm  ( 2072): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2072): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2072): StableState(): Entering Off State
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 2072): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2072): Entering PendingCommandState State
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 2072): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2072): StableState(): Entering Off State
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 2072): bta_dm_check_av:0
,W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=1
W/bt-btif ( 2072): bta_dm_check_av:0
,W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2072): new conn_srvc id:26, app_id:255
W/bt-btif ( 2072): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2072): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Incoming connection initialized (thread ID: 309)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Entering thread (ID: 309)
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 2072): bta_dm_check_av:0
,W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): onBytesRead: Read 82 bytes successfully (thread ID: 309)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Got valid identity from [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): onBytesWritten: 77 bytes successfully written (thread ID: 309)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): removeThreadFromList: Removing thread with ID 309
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Handshake thread disposed (thread ID: 309)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onIncomingConnectionConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Exiting thread (ID: 309)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
,I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Incoming connection to peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3272): notifyPeerAvailability: Peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] is available
,I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Incoming socket thread, for peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178], created successfully
D/io.jxcore.node.ConnectionHelper( 3272): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3272): Entering thread (ID: 310)
,I/jxcore-log( 3272): 2015-12-18T12:53:36.798Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3272): 
,I/io.jxcore.node.IncomingSocketThread( 3272): Local host address: localhost/127.0.0.1, port: 55815
D/io.jxcore.node.IncomingSocketThread( 3272): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3272): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3272): Exiting thread (ID: 310)
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 312, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 311, name: Sender)
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=0
W/bt-btif ( 2072): bta_dm_check_av:0
,W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2072): new conn_srvc id:26, app_id:1
W/bt-btif ( 2072): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2072): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onSocketConnected: [F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 308)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): onBytesWritten: 77 bytes successfully written (thread ID: 313)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Outgoing connection initialized (*handshake* thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 308)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Entering thread (ID: 313)
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=1
W/bt-btif ( 2072): bta_dm_check_av:0
,W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): onBytesRead: Read 82 bytes successfully (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Handshake succeeded with [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onHandshakeSucceeded: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Exiting thread (ID: 313)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Outgoing connection to peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
,D/io.jxcore.node.ConnectionHelper( 3272): notifyPeerAvailability: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351] is available
,I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Outgoing socket thread, for peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3272): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 3272): Entering thread (ID: 314)
,D/io.jxcore.node.OutgoingSocketThread( 3272): Server socket local port: 47382
,I/io.jxcore.node.OutgoingSocketThread( 3272): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3272): onListeningForIncomingConnections: Outgoing connection is using port 47382 (peer ID: F8:CF:C5:D9:E5:61)
,I/jxcore-log( 3272): 2015-12-18T12:53:37.497Z SendDataConnector.js: CLIENT connected to 47382, error: null
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:53:37.498Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3272): 
,I/io.jxcore.node.OutgoingSocketThread( 3272): Incoming data from address: /127.0.0.1, port: 47382
D/io.jxcore.node.OutgoingSocketThread( 3272): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3272): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3272): Exiting thread (ID: 314)
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 316, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 315, name: Sender)
,I/jxcore-log( 3272): 2015-12-18T12:53:37.542Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:38.057Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:38.111Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3272): 
,D/        ( 2072): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 3272): 2015-12-18T12:53:38.283Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3272): 
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 2072): bta_dm_check_av:0
,W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3272): 2015-12-18T12:53:38.354Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3272): 
,D/        ( 2072): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19756
,I/jxcore-log( 3272): 2015-12-18T12:53:38.499Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:38.571Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:38.709Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:38.812Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:38.856Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:38.870Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3272): 
,D/btif_config_util( 2072): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3272): 2015-12-18T12:53:38.919Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:38.945Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:38.972Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:39.106Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:39.112Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:39.208Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:39.462Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:39.474Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:39.478Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:39.514Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:39.537Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:39.611Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:39.616Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:39.755Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3272): 
,D/        ( 2072): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 3272): 2015-12-18T12:53:39.770Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:39.785Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:39.836Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:39.996Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:53:39.998Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:40.212Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:40.245Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:40.293Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:40.298Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:40.431Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:40.486Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:40.498Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:40.613Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:40.646Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:40.732Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:40.747Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:40.778Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:40.802Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:40.835Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:40.895Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:41.194Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:41.271Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:41.392Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3272): 
,W/bt-btif ( 2072): invalid rfc slot id: 4
,W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 312, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3272): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Incoming connection, peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 310
D/io.jxcore.node.OutgoingSocketThread( 3272): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 312
,D/io.jxcore.node.OutgoingSocketThread( 3272): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 311
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 311, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3272): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Incoming connection, peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3272): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 311, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 312, name: Receiver)
,I/jxcore-log( 3272): 2015-12-18T12:53:41.589Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:41.700Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:41.936Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:42.270Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:53:42.271Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:42.292Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:42.295Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3272): 
D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:CF:C5:D9:E5:61
I/io.jxcore.node.OutgoingSocketThread( 3272): close
D/io.jxcore.node.OutgoingSocketThread( 3272): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 316
D/io.jxcore.node.OutgoingSocketThread( 3272): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 315
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 315, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3272): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Outgoing connection, peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3272): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 316, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3272): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Outgoing connection, peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:CF:C5:D9:E5:61
,E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 315, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:CF:C5:D9:E5:61
,D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 316, name: Receiver)
,I/jxcore-log( 3272): 2015-12-18T12:53:42.340Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): ---- round done--------
I/jxcore-log( 3272): 
I/jxcore-log( 3272): do fake peer & start
I/jxcore-log( 3272): 
I/jxcore-log( 3272): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:42.342Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:53:42.342Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:53:42.342Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
,I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper( 3272): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [58:3F:54:73:64:C0 58:3F:54:73:64:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: null 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to null in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
I/chromium( 3272): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:CF:C5:D9:E5:61 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 317)
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=0
W/bt-btif ( 2072): bta_dm_check_av:0
,W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2072): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,E/bt-btm  ( 2072): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2072): onReceive
,D/BluetoothManagerService(  733): Message: 20
D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5fb0c6e:true
,I/BTConnectionReceiver( 1466): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1466): Bluetooth Device Name: Nexus 6
,W/bt-btif ( 2072): info:x10
,D/        ( 2072): remote version info [e0:db:10:14:e2:c0]: 7, f, 230f
,E/BluetoothRemoteDevices( 2072): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2072): info:x10
,D/        ( 2072): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2072): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 2072): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2072): Entering PendingCommandState State
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=1
W/bt-btif ( 2072): bta_dm_check_av:0
,W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2072): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2072): StableState(): Entering Off State
,W/bt-btif ( 2072): new conn_srvc id:26, app_id:255
W/bt-btif ( 2072): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2072): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Incoming connection initialized (thread ID: 318)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Entering thread (ID: 318)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): onBytesRead: Read 82 bytes successfully (thread ID: 318)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Got valid identity from [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): onBytesWritten: 77 bytes successfully written (thread ID: 318)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): removeThreadFromList: Removing thread with ID 318
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Handshake thread disposed (thread ID: 318)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Exiting thread (ID: 318)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932]
,I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Incoming connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932]
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
,D/io.jxcore.node.ConnectionHelper( 3272): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932] is available
,I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Incoming socket thread, for peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932], created successfully
,D/io.jxcore.node.ConnectionHelper( 3272): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3272): Entering thread (ID: 319)
,I/jxcore-log( 3272): 2015-12-18T12:53:49.686Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3272): 
,I/io.jxcore.node.IncomingSocketThread( 3272): Local host address: localhost/127.0.0.1, port: 55815
,D/io.jxcore.node.IncomingSocketThread( 3272): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3272): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3272): Exiting thread (ID: 319)
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 321, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 320, name: Sender)
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=0
W/bt-btif ( 2072): bta_dm_check_av:0
,W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2072): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 2072): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2072): Entering PendingCommandState State
,I/jxcore-log( 3272): 2015-12-18T12:53:50.442Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:50.444Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:50.452Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:50.508Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3272): 
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0,
,D/BluetoothAdapterProperties( 2072): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/jxcore-log( 3272): 2015-12-18T12:53:50.584Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3272): 
,I/BluetoothBondStateMachine( 2072): StableState(): Entering Off State
,I/jxcore-log( 3272): 2015-12-18T12:53:50.639Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:50.674Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:50.715Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:50.718Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:50.723Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:50.733Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:50.787Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:50.800Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:50.850Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:50.885Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3272): 
,W/bt-btif ( 2072): new conn_srvc id:26, app_id:1
W/bt-btif ( 2072): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2072): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onSocketConnected: [58:3F:54:73:64:C0 58:3F:54:73:64:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): onBytesWritten: 77 bytes successfully written (thread ID: 322)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Outgoing connection initialized (*handshake* thread ID: 322)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 317)
,I/jxcore-log( 3272): 2015-12-18T12:53:50.931Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3272): 
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Entering thread (ID: 322)
,I/jxcore-log( 3272): 2015-12-18T12:53:50.976Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:51.016Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:51.121Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:51.134Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:51.207Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:51.218Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3272): 
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=1
W/bt-btif ( 2072): bta_dm_check_av:0
,W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3272): 2015-12-18T12:53:51.280Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:51.316Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:51.351Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:51.359Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3272): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): onBytesRead: Read 77 bytes successfully (thread ID: 322)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Handshake succeeded with [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onHandshakeSucceeded: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Exiting thread (ID: 322)
,I/jxcore-log( 3272): 2015-12-18T12:53:51.411Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3272): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Outgoing connection to peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3272): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] is available
,I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Outgoing socket thread, for peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3272): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 3272): Entering thread (ID: 323)
,D/io.jxcore.node.OutgoingSocketThread( 3272): Server socket local port: 36576
I/io.jxcore.node.OutgoingSocketThread( 3272): Now accepting connections...
,I/jxcore-log( 3272): 2015-12-18T12:53:51.445Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:51.477Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:51.515Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:51.537Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:51.544Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:51.555Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:51.616Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:51.690Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3272): 
,I/io.jxcore.node.ConnectionHelper( 3272): onListeningForIncomingConnections: Outgoing connection is using port 36576 (peer ID: 58:3F:54:73:64:C0)
I/jxcore-log( 3272): 2015-12-18T12:53:51.739Z SendDataConnector.js: CLIENT connected to 36576, error: null
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:53:51.740Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3272): 
,I/io.jxcore.node.OutgoingSocketThread( 3272): Incoming data from address: /127.0.0.1, port: 36576
D/io.jxcore.node.OutgoingSocketThread( 3272): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3272): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3272): Exiting thread (ID: 323)
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 325, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 324, name: Sender)
,I/jxcore-log( 3272): 2015-12-18T12:53:51.788Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:51.798Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3272): 
,W/bt-btif ( 2072): invalid rfc slot id: 6
W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 321, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3272): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 319
D/io.jxcore.node.OutgoingSocketThread( 3272): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 321
D/io.jxcore.node.OutgoingSocketThread( 3272): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 320
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3272): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 321, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 320, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3272): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 320, name: Sender)
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa405124c rs_disc_pending=0
W/bt-btif ( 2072): bta_dm_check_av:0
W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3272): 2015-12-18T12:53:52.201Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3272): 
,W/bt-rfcomm( 2072): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 2072): RFCOMM_DisconnectInd LCID:0x47
,D/        ( 2072): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3272): 2015-12-18T12:53:52.834Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:53.165Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3272): 
,D/        ( 2072): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12826
,I/jxcore-log( 3272): 2015-12-18T12:53:53.596Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:53.939Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3272): 
,D/        ( 2072): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3272): 2015-12-18T12:53:54.292Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:54.750Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3272): 
,D/btif_config_util( 2072): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3272): 2015-12-18T12:53:55.091Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:55.395Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:55.626Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3272): 
,E/bt-btm  ( 2072): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2072): onReceive
,I/BTConnectionReceiver( 1466): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1466): Bluetooth Device Name: Note4-1
,I/jxcore-log( 3272): 2015-12-18T12:53:56.035Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:53:56.035Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:53:56.038Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:53:56.038Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3272): 
D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 58:3F:54:73:64:C0
I/io.jxcore.node.OutgoingSocketThread( 3272): close
D/io.jxcore.node.OutgoingSocketThread( 3272): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 325
D/io.jxcore.node.OutgoingSocketThread( 3272): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 324
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 324, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3272): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3272): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 325, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3272): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Successfully disconnected (peer ID: 58:3F:54:73:64:C0
,E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 324, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 325, name: Receiver)
,I/jxcore-log( 3272): 2015-12-18T12:53:56.053Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3272): 
I/jxcore-log( 3272): ---- round done--------
I/jxcore-log( 3272): 
I/jxcore-log( 3272): do fake peer & start
I/jxcore-log( 3272): 
I/jxcore-log( 3272): Connect to fake peer: 7C:F9:0E:51:18:22
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:53:56.055Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:53:56.055Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:53:56.056Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 3272): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: null 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
I/chromium( 3272): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:3F:54:73:64:C0 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 326)
,W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2072): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,W/bt-btif ( 2072): info:x10
,D/        ( 2072): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2072): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=1
W/bt-btif ( 2072): bta_dm_check_av:0
,W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2072): process_service_search_attr_rsp
,E/bt-btm  ( 2072): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2072): onReceive
,I/BTConnectionReceiver( 1466): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1466): Bluetooth Device Name: G3-1
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
E/bt-btif ( 2072): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2072): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 2072): Failed to remove device: 7C:F9:0E:51:18:22
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2072): StableState(): Entering Off State
,W/bt-btif ( 2072): new conn_srvc id:26, app_id:1
W/bt-btif ( 2072): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2072): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onSocketConnected: [7C:F9:0E:51:18:22 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 326)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): onBytesWritten: 77 bytes successfully written (thread ID: 327)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Outgoing connection initialized (*handshake* thread ID: 327)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 326)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Entering thread (ID: 327)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): onBytesRead: Read 83 bytes successfully (thread ID: 327)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onHandshakeSucceeded: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523]
I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Outgoing connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523]
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3272): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523] is available
I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Outgoing socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3272): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Exiting thread (ID: 327)
,D/io.jxcore.node.OutgoingSocketThread( 3272): Entering thread (ID: 328)
D/io.jxcore.node.OutgoingSocketThread( 3272): Server socket local port: 60242
I/io.jxcore.node.OutgoingSocketThread( 3272): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3272): onListeningForIncomingConnections: Outgoing connection is using port 60242 (peer ID: 7C:F9:0E:51:18:22)
I/jxcore-log( 3272): 2015-12-18T12:54:01.648Z SendDataConnector.js: CLIENT connected to 60242, error: null
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:01.649Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3272): 
,I/io.jxcore.node.OutgoingSocketThread( 3272): Incoming data from address: /127.0.0.1, port: 60242
D/io.jxcore.node.OutgoingSocketThread( 3272): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3272): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3272): Exiting thread (ID: 328)
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 330, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 329, name: Sender)
,I/jxcore-log( 3272): 2015-12-18T12:54:01.686Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3272): 
,E/bt-btm  ( 2072): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2072): onReceive
,I/BTConnectionReceiver( 1466): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1466): Bluetooth Device Name: Note3-1
,D/        ( 2072): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 3272): 2015-12-18T12:54:02.997Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:54:03.127Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3272): 
,D/        ( 2072): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 3272): 2015-12-18T12:54:03.203Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3272): 
,D/        ( 2072): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 3272): 2015-12-18T12:54:03.266Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:54:03.498Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:54:03.619Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:54:03.681Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:54:03.790Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:54:03.846Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3272): 
,D/btif_config_util( 2072): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3272): 2015-12-18T12:54:04.278Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:04.279Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:54:04.294Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:04.298Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3272): 
D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 3272): close
D/io.jxcore.node.OutgoingSocketThread( 3272): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 330
D/io.jxcore.node.OutgoingSocketThread( 3272): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 329
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 329, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3272): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3272): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 330, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3272): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4523] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:51:18:22
,E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 329, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 330, name: Receiver)
,I/jxcore-log( 3272): 2015-12-18T12:54:04.329Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): ---- round done--------
I/jxcore-log( 3272): 
I/jxcore-log( 3272): do fake peer & start
I/jxcore-log( 3272): 
I/jxcore-log( 3272): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:04.331Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:04.331Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:04.331Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 3272): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [08:EC:A9:50:75:41 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to null in address 08:EC:A9:50:75:41
,I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
I/chromium( 3272): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:51:18:22 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 331)
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2072): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: RESTARTING
,I/wpa_supplicant( 1019): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,E/bt-btm  ( 2072): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2072): onReceive
,I/BTConnectionReceiver( 1466): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1466): Bluetooth Device Name: Thali Test (Galaxy A5)
,W/bt-sdp  ( 2072): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2072): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2072): invalid rfc slot id: 10
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 331)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Maximum number of allowed retries (0) reached, giving up... (thread ID: 331)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 331)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:75:41 08:EC:A9:50:75:41]
I/jxcore-log( 3272): 2015-12-18T12:54:09.490Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:75:41 08:EC:A9:50:75:41] failed
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:09.491Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:75:41 08:EC:A9:50:75:41] failed
I/jxcore-log( 3272): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): shutdown (thread ID: 331)
,I/jxcore-log( 3272): 2015-12-18T12:54:09.493Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3272): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Start timer timeout, starting now...
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/jxcore-log( 3272): 2015-12-18T12:54:14.508Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:14.510Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3272): 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3272): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] is available
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
,I/jxcore-log( 3272): 2015-12-18T12:54:19.532Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:19.537Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:19.538Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:19.538Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
,I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 3272): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [08:EC:A9:50:75:41 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 334)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3272): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2072): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2072): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2072): invalid rfc slot id: 11
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2072): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2072): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2072): invalid rfc slot id: 12
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 334)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Maximum number of allowed retries (0) reached, giving up... (thread ID: 334)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 334)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:75:41 08:EC:A9:50:75:41]
I/jxcore-log( 3272): 2015-12-18T12:54:29.831Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:75:41 08:EC:A9:50:75:41] failed
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:29.832Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:75:41 08:EC:A9:50:75:41] failed
I/jxcore-log( 3272): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): shutdown (thread ID: 334)
,I/jxcore-log( 3272): 2015-12-18T12:54:29.833Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3272): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 6 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT548","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 3272): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548] is available
,I/jxcore-log( 3272): 2015-12-18T12:54:34.844Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:34.845Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3272): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3565","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 3272): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565] is available
,D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
I/jxcore-log( 3272): 2015-12-18T12:54:39.850Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:39.850Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:39.851Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:39.851Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
,I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,W/io.jxcore.node.ConnectionHelper( 3272): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [08:EC:A9:50:75:41 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 336)
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2072): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2072): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2072): invalid rfc slot id: 13
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 336)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Maximum number of allowed retries (0) reached, giving up... (thread ID: 336)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 336)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:75:41 08:EC:A9:50:75:41]
I/jxcore-log( 3272): 2015-12-18T12:54:45.027Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:75:41 08:EC:A9:50:75:41] failed
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:45.027Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:75:41 08:EC:A9:50:75:41] failed
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:45.028Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3272): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): shutdown (thread ID: 336)
,I/jxcore-log( 3272): 2015-12-18T12:54:50.029Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:50.030Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3272): 
,D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
I/jxcore-log( 3272): 2015-12-18T12:54:55.036Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:55.037Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:55.038Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:54:55.038Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 3272): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [08:EC:A9:50:75:41 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 338)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3272): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2072): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2072): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2072): invalid rfc slot id: 14
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: RESTARTING
,I/wpa_supplicant( 1019): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,W/bt-sdp  ( 2072): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2072): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2072): invalid rfc slot id: 15
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 338)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Maximum number of allowed retries (0) reached, giving up... (thread ID: 338)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 338)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:75:41 08:EC:A9:50:75:41]
I/jxcore-log( 3272): 2015-12-18T12:55:05.350Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:75:41 08:EC:A9:50:75:41] failed
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:05.350Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:75:41 08:EC:A9:50:75:41] failed
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:05.351Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3272): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): shutdown (thread ID: 338)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Start timer timeout, starting now...
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3272): 2015-12-18T12:55:10.351Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:10.352Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3272): 
,D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
I/jxcore-log( 3272): 2015-12-18T12:55:15.359Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:15.360Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:15.360Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:15.361Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 3272): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [08:EC:A9:50:75:41 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 340)
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2072): info:x10
,D/        ( 2072): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2072): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa405196c rs_disc_pending=0
W/bt-btif ( 2072): bta_dm_check_av:0
,W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,E/bt-btif ( 2072): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2072): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2072): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2072): StableState(): Entering Off State
,W/bt-btif ( 2072): new conn_srvc id:26, app_id:255
W/bt-btif ( 2072): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2072): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Incoming connection initialized (thread ID: 341)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Entering thread (ID: 341)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): onBytesRead: Read 77 bytes successfully (thread ID: 341)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): onBytesWritten: 77 bytes successfully written (thread ID: 341)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): removeThreadFromList: Removing thread with ID 341
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Handshake thread disposed (thread ID: 341)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Exiting thread (ID: 341)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Incoming connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3272): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] is available
,I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Incoming socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], created successfully
D/io.jxcore.node.ConnectionHelper( 3272): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3272): Entering thread (ID: 342)
,I/jxcore-log( 3272): 2015-12-18T12:55:19.397Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3272): 
,I/io.jxcore.node.IncomingSocketThread( 3272): Local host address: localhost/127.0.0.1, port: 55815
D/io.jxcore.node.IncomingSocketThread( 3272): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3272): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3272): Exiting thread (ID: 342)
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 344, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 343, name: Sender)
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3272): 2015-12-18T12:55:20.232Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:20.305Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:20.449Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data,
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:20.457Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:20.516Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3272): 
,W/bt-sdp  ( 2072): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2072): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2072): invalid rfc slot id: 16
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 340)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Maximum number of allowed retries (0) reached, giving up... (thread ID: 340)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 340)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:75:41 08:EC:A9:50:75:41]
,I/jxcore-log( 3272): 2015-12-18T12:55:20.534Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:75:41 08:EC:A9:50:75:41] failed
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:20.534Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:75:41 08:EC:A9:50:75:41] failed
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:20.536Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3272): 
D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
I/jxcore-log( 3272): 2015-12-18T12:55:20.538Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3272): 
I/jxcore-log( 3272): ---- round done--------
I/jxcore-log( 3272): 
I/jxcore-log( 3272): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 1
I/jxcore-log( 3272): 
I/jxcore-log( 3272): do fake peer & start
I/jxcore-log( 3272): 
I/jxcore-log( 3272): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:20.538Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:20.538Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:20.538Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: null F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to null in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
I/chromium( 3272): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:75:41 done with result: Connection to peer [08:EC:A9:50:75:41 08:EC:A9:50:75:41] failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): shutdown (thread ID: 340)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 346)
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3272): 2015-12-18T12:55:20.606Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3272): 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa405196c rs_disc_pending=1
W/bt-btif ( 2072): bta_dm_check_av:0
,W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
I/jxcore-log( 3272): 2015-12-18T12:55:20.809Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:20.843Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:20.856Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:20.894Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3272): 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3272): 2015-12-18T12:55:20.909Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:20.911Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3272): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,I/jxcore-log( 3272): 2015-12-18T12:55:20.986Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:20.992Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:21.137Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:21.207Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:21.288Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:21.355Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:21.522Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:21.590Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:21.726Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:21.882Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:21.891Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3272): 
,D/btif_config_util( 2072): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3272): 2015-12-18T12:55:21.953Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:22.088Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:22.224Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:22.294Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:22.436Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:22.486Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:22.516Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:22.557Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3272): 
,W/bt-btif ( 2072): info:x10
,D/        ( 2072): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2072): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3272): 2015-12-18T12:55:22.593Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3272): 
,W/bt-sdp  ( 2072): process_service_search_attr_rsp
,I/jxcore-log( 3272): 2015-12-18T12:55:22.735Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:22.855Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:22.871Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:22.917Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3272): 
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2072): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2072): Entering PendingCommandState State
,I/jxcore-log( 3272): 2015-12-18T12:55:23.021Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3272): 
,D/WifiP2pManager( 3272): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/jxcore-log( 3272): 2015-12-18T12:55:23.141Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3272): 
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2072): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/jxcore-log( 3272): 2015-12-18T12:55:23.289Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3272): 
,I/BluetoothBondStateMachine( 2072): StableState(): Entering Off State
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2072): new conn_srvc id:26, app_id:1
W/bt-btif ( 2072): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2072): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onSocketConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 346)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): onBytesWritten: 77 bytes successfully written (thread ID: 347)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Outgoing connection initialized (*handshake* thread ID: 347)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 346)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Entering thread (ID: 347)
,I/jxcore-log( 3272): 2015-12-18T12:55:23.453Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3272): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): onBytesRead: Read 77 bytes successfully (thread ID: 347)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Handshake succeeded with [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onHandshakeSucceeded: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Outgoing connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3272): onConnected: The total number of connections is now 2
,I/jxcore-log( 3272): 2015-12-18T12:55:23.489Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3272): 
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Exiting thread (ID: 347)
,D/io.jxcore.node.OutgoingSocketThread( 3272): Entering thread (ID: 348)
D/io.jxcore.node.OutgoingSocketThread( 3272): Server socket local port: 42809
,I/io.jxcore.node.OutgoingSocketThread( 3272): Now accepting connections...
,I/jxcore-log( 3272): 2015-12-18T12:55:23.536Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3272): 
,W/bt-btif ( 2072): invalid rfc slot id: 8
,W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 344, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3272): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 342
D/io.jxcore.node.OutgoingSocketThread( 3272): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 344
D/io.jxcore.node.OutgoingSocketThread( 3272): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 343
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 343, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3272): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3272): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 344, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 343, name: Sender)
,I/jxcore-log( 3272): 2015-12-18T12:55:23.594Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3272): 
,I/io.jxcore.node.ConnectionHelper( 3272): onListeningForIncomingConnections: Outgoing connection is using port 42809 (peer ID: F8:95:C7:87:3C:51)
I/jxcore-log( 3272): 2015-12-18T12:55:23.811Z SendDataConnector.js: CLIENT connected to 42809, error: null
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:23.811Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3272): 
,I/io.jxcore.node.OutgoingSocketThread( 3272): Incoming data from address: /127.0.0.1, port: 42809
D/io.jxcore.node.OutgoingSocketThread( 3272): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3272): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3272): Exiting thread (ID: 348)
,I/jxcore-log( 3272): 2015-12-18T12:55:23.829Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3272): 
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 350, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 349, name: Sender)
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-rfcomm( 2072): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 2072): RFCOMM_DisconnectInd LCID:0x42
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/jxcore-log( 3272): 2015-12-18T12:55:24.555Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:24.751Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:25.062Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3272): 
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa405196c rs_disc_pending=0
W/bt-btif ( 2072): bta_dm_check_av:0
,W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3272): 2015-12-18T12:55:25.179Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:25.781Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:26.198Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:26.869Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:27.135Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3272): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3565","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565] already in the list, will not add again
,I/jxcore-log( 3272): 2015-12-18T12:55:27.707Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:27.885Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:27.886Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:27.902Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:27.903Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3272): 
,E/bt-btm  ( 2072): btm_sec_disconnected - Clearing Pending flag
,D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread( 3272): close
D/io.jxcore.node.OutgoingSocketThread( 3272): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 350
D/io.jxcore.node.OutgoingSocketThread( 3272): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 349
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 349, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3272): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3272): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 350, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3272): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:3C:51
,E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 349, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
,D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 350, name: Receiver)
,I/jxcore-log( 3272): 2015-12-18T12:55:27.951Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3272): 
I/jxcore-log( 3272): ---- round done--------
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): do fake peer & start
I/jxcore-log( 3272): 
I/jxcore-log( 3272): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:27.953Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:27.953Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:27.953Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
,I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 3272): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,D/BluetoothMapService( 2072): onReceive
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/chromium( 3272): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:95:C7:87:3C:51 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 351)
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1466): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1466): Bluetooth Device Name: G3s-1
,W/bt-btif ( 2072): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,W/bt-btif ( 2072): info:x10
,D/        ( 2072): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2072): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2072): process_service_search_attr_rsp
,E/bt-btif ( 2072): DISCOVERY_COMP_EVT slot id:19, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2072): invalid rfc slot id: 19
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 351)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Maximum number of allowed retries (0) reached, giving up... (thread ID: 351)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 351)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
I/jxcore-log( 3272): 2015-12-18T12:55:28.439Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:28.439Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:28.440Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3272): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): shutdown (thread ID: 351)
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 2072): bta_dm_check_av:0
,W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2072): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2072): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2072): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2072): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2072): onReceive
,I/BTConnectionReceiver( 1466): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1466): Bluetooth Device Name: G4-1
,I/jxcore-log( 3272): 2015-12-18T12:55:33.442Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:33.444Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3272): 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2072): info:x10
,D/        ( 2072): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
E/BluetoothRemoteDevices( 2072): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 3272): 2015-12-18T12:55:38.449Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:38.449Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:38.450Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:38.450Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 3272): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 353)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3272): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 2072): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2072): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2072): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2072): StableState(): Entering Off State
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa4051ec4 rs_disc_pending=1
W/bt-btif ( 2072): bta_dm_check_av:0
,W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2072): new conn_srvc id:26, app_id:255
W/bt-btif ( 2072): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2072): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Incoming connection initialized (thread ID: 354)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Entering thread (ID: 354)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): onBytesRead: Read 82 bytes successfully (thread ID: 354)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Got valid identity from [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): onBytesWritten: 77 bytes successfully written (thread ID: 354)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): removeThreadFromList: Removing thread with ID 354
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Handshake thread disposed (thread ID: 354)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onIncomingConnectionConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Exiting thread (ID: 354)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Incoming connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3272): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] is available
,I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Incoming socket thread, for peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], created successfully
D/io.jxcore.node.ConnectionHelper( 3272): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3272): Entering thread (ID: 355)
,I/jxcore-log( 3272): 2015-12-18T12:55:41.292Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3272): 
,I/io.jxcore.node.IncomingSocketThread( 3272): Local host address: localhost/127.0.0.1, port: 55815
D/io.jxcore.node.IncomingSocketThread( 3272): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3272): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3272): Exiting thread (ID: 355)
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 357, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 356, name: Sender)
,W/bt-btif ( 2072): info:x10
,D/        ( 2072): remote version info [00:f4:6f:30:e0:6c]: 7, f, 6109
,E/BluetoothRemoteDevices( 2072): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2072): process_service_search_attr_rsp
,E/bt-btif ( 2072): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2072): invalid rfc slot id: 20
,W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3272): 2015-12-18T12:55:42.245Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:42.278Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:42.282Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:42.421Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3272): 
,W/bt-sdp  ( 2072): process_service_search_attr_rsp
,E/bt-btif ( 2072): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 353)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Maximum number of allowed retries (0) reached, giving up... (thread ID: 353)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 353)
,W/bt-btif ( 2072): invalid rfc slot id: 22
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/jxcore-log( 3272): 2015-12-18T12:55:42.485Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:42.487Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:42.488Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3272): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): shutdown (thread ID: 353)
,I/jxcore-log( 3272): 2015-12-18T12:55:42.499Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:42.535Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:42.540Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:42.546Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:42.587Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:42.595Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:42.624Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:42.735Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:42.765Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:42.782Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:42.895Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:42.981Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:43.010Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:43.021Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:43.036Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:43.044Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:43.073Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:43.092Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:43.100Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:43.134Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3272): 
,W/bt-btif ( 2072): invalid rfc slot id: 17
,W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 357, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3272): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 355
D/io.jxcore.node.IncomingSocketThread( 3272): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 357
D/io.jxcore.node.IncomingSocketThread( 3272): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 356
D/io.jxcore.node.IncomingSocketThread( 3272): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 356, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3272): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3272): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 3272): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 357, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 356, name: Sender)
,I/jxcore-log( 3272): 2015-12-18T12:55:43.378Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3272): 
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa4051ec4 rs_disc_pending=0
W/bt-btif ( 2072): bta_dm_check_av:0
,W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2072): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 2072): RFCOMM_DisconnectInd LCID:0x49
,D/btif_config_util( 2072): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2072): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2072): aclStateChangeCallback: Device is NULL
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): checkListForExpiredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
,I/io.jxcore.node.ConnectionHelper( 3272): onPeerLost: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
,D/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548] removed
,D/io.jxcore.node.ConnectionHelper( 3272): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548] not available
,E/bt-btm  ( 2072): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2072): onReceive
,I/BTConnectionReceiver( 1466): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1466): Bluetooth Device Name: S5-1
,I/jxcore-log( 3272): 2015-12-18T12:55:47.490Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:47.490Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3272): 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT548","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 3272): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548] is available
,D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 3272): 2015-12-18T12:55:52.491Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:52.492Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:52.492Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:52.492Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 3272): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 359)
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2072): info:x10
,D/        ( 2072): remote version info [00:f4:6f:30:e0:6c]: 7, f, 610c
,E/BluetoothRemoteDevices( 2072): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2072): process_service_search_attr_rsp
,E/bt-btif ( 2072): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2072): invalid rfc slot id: 23
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 359)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Maximum number of allowed retries (0) reached, giving up... (thread ID: 359)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 359)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/jxcore-log( 3272): 2015-12-18T12:55:53.329Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:53.330Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:55:53.330Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3272): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): shutdown (thread ID: 359)
,D/btif_config_util( 2072): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2072): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2072): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3272): 2015-12-18T12:55:58.331Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:55:58.332Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3272): 
,I/ActivityManager(  733): Killing 1982:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10031/pid_1982/cgroup.procs: No such file or directory
,D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 3272): 2015-12-18T12:56:03.339Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:03.340Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:03.340Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:03.341Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 3272): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 361)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3272): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2072): info:x10
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2072): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2072): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2072): process_service_search_attr_rsp
,E/bt-btif ( 2072): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2072): invalid rfc slot id: 24
,W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2072): process_service_search_attr_rsp
,E/bt-btif ( 2072): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2072): invalid rfc slot id: 25
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 361)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Maximum number of allowed retries (0) reached, giving up... (thread ID: 361)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 361)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
I/jxcore-log( 3272): 2015-12-18T12:56:04.421Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:04.422Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:56:04.422Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3272): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): shutdown (thread ID: 361)
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2072): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2072): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2072): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3272): 2015-12-18T12:56:09.426Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:09.427Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3272): 
,D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 3272): 2015-12-18T12:56:14.430Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:14.431Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:14.432Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:14.432Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
,I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 3272): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 363)
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2072): info:x10
,D/        ( 2072): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2072): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2072): process_service_search_attr_rsp
,E/bt-btif ( 2072): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2072): invalid rfc slot id: 26
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 363)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Maximum number of allowed retries (0) reached, giving up... (thread ID: 363)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 363)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/jxcore-log( 3272): 2015-12-18T12:56:15.209Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:15.210Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3272): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): shutdown (thread ID: 363)
,I/jxcore-log( 3272): 2015-12-18T12:56:15.235Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3272): 
D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 3272): 2015-12-18T12:56:15.238Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3272): 
I/jxcore-log( 3272): ---- round done--------
I/jxcore-log( 3272): 
I/jxcore-log( 3272): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 1
I/jxcore-log( 3272): 
I/jxcore-log( 3272): do fake peer & start
I/jxcore-log( 3272): 
I/jxcore-log( 3272): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:15.241Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:15.241Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:15.242Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
,I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to S5-1 in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: S5-1 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to S5-1 in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
I/chromium( 3272): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 00:F4:6F:30:E0:6C done with result: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 365)
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2072): info:x10
,D/        ( 2072): remote version info [7c:f9:0e:34:8a:a0]: 6, f, 410d
,I/BTConnectionReceiver( 1466): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1466): Bluetooth Device Name: S5-1
,W/bt-sdp  ( 2072): process_service_search_attr_rsp
,E/bt-btm  ( 2072): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2072): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa4051ec4 rs_disc_pending=1
W/bt-btif ( 2072): bta_dm_check_av:0
,W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2072): new conn_srvc id:26, app_id:1
W/bt-btif ( 2072): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2072): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onSocketConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 365)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): onBytesWritten: 77 bytes successfully written (thread ID: 366)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Outgoing connection initialized (*handshake* thread ID: 366)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 365)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Entering thread (ID: 366)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): onBytesRead: Read 82 bytes successfully (thread ID: 366)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Handshake succeeded with [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onHandshakeSucceeded: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Exiting thread (ID: 366)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Outgoing connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Outgoing socket thread, for peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3272): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3272): Entering thread (ID: 367)
D/io.jxcore.node.OutgoingSocketThread( 3272): Server socket local port: 49323
I/io.jxcore.node.OutgoingSocketThread( 3272): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3272): onListeningForIncomingConnections: Outgoing connection is using port 49323 (peer ID: 7C:F9:0E:34:8A:A0)
I/jxcore-log( 3272): 2015-12-18T12:56:20.101Z SendDataConnector.js: CLIENT connected to 49323, error: null
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:20.101Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:56:20.112Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3272): 
,I/io.jxcore.node.OutgoingSocketThread( 3272): Incoming data from address: /127.0.0.1, port: 49323
D/io.jxcore.node.OutgoingSocketThread( 3272): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3272): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3272): Exiting thread (ID: 367)
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 368, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 369, name: Receiver)
,D/        ( 2072): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1392
,I/jxcore-log( 3272): 2015-12-18T12:56:20.673Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:56:21.047Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3272): 
,D/btif_config_util( 2072): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3272): 2015-12-18T12:56:21.219Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:56:21.310Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:56:21.325Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:56:21.369Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:56:21.371Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:56:21.447Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:56:21.495Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:56:21.506Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:21.506Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:56:21.508Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:21.508Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3272): 
D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:34:8A:A0
I/io.jxcore.node.OutgoingSocketThread( 3272): close
D/io.jxcore.node.OutgoingSocketThread( 3272): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 369
D/io.jxcore.node.OutgoingSocketThread( 3272): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 368
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 368, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3272): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3272): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 369, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3272): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 368, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 369, name: Receiver)
I/jxcore-log( 3272): 2015-12-18T12:56:21.516Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): ---- round done--------
I/jxcore-log( 3272): 
I/jxcore-log( 3272): do fake peer & start
I/jxcore-log( 3272): 
I/jxcore-log( 3272): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:21.517Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:56:21.518Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:21.518Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to Note3-1 in address E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: Note3-1 E0:DB:10:1F:C9:5E
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to Note3-1 in address E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: E0:DB:10:1F:C9:5E)
,I/chromium( 3272): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:34:8A:A0 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address E0:DB:10:1F:C9:5E (thread ID: 370)
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2072): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,E/bt-btm  ( 2072): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2072): onReceive
,I/BTConnectionReceiver( 1466): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1466): Bluetooth Device Name: S5-1
,W/bt-sdp  ( 2072): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2072): DISCOVERY_COMP_EVT slot id:28, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2072): invalid rfc slot id: 28
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 370)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Maximum number of allowed retries (0) reached, giving up... (thread ID: 370)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 370)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
I/jxcore-log( 3272): 2015-12-18T12:56:26.668Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] failed
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:26.669Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] failed
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:26.671Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3272): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): shutdown (thread ID: 370)
,I/jxcore-log( 3272): 2015-12-18T12:56:31.672Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:56:31.677Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3272): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: RESTARTING
,I/wpa_supplicant( 1019): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:1F:C9:5E
E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Failed to disconnect (peer ID: E0:DB:10:1F:C9:5E), either no such connection or failed to close the connection
I/jxcore-log( 3272): 2015-12-18T12:56:36.681Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:36.682Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:56:36.687Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:36.688Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to Note3-1 in address E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: Note3-1 E0:DB:10:1F:C9:5E
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to Note3-1 in address E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: E0:DB:10:1F:C9:5E),
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address E0:DB:10:1F:C9:5E (thread ID: 372)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3272): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Start timer timeout, starting now...
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionTimeout: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
,I/jxcore-log( 3272): 2015-12-18T12:56:51.710Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] timed out
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:51.711Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] timed out
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:51.712Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:56:56.721Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:56:56.722Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3272): 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT548]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:1F:C9:5E
E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Failed to disconnect (peer ID: E0:DB:10:1F:C9:5E), either no such connection or failed to close the connection
I/jxcore-log( 3272): 2015-12-18T12:57:01.731Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:57:01.732Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:57:01.741Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:57:01.741Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
,I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to Note3-1 in address E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: Note3-1 E0:DB:10:1F:C9:5E
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to Note3-1 in address E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: E0:DB:10:1F:C9:5E)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address E0:DB:10:1F:C9:5E (thread ID: 374)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3272): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,W/bt-sdp  ( 2072): SDP - Rcvd conn cnf with error: 0x22  CID 0x41
E/bt-btif ( 2072): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2072): invalid rfc slot id: 29
,W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2072): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2072): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2072): invalid rfc slot id: 30
,W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionTimeout: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
I/jxcore-log( 3272): 2015-12-18T12:57:16.757Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] timed out
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:57:16.758Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] timed out
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:57:16.759Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3272): 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] removed
D/io.jxcore.node.ConnectionHelper( 3272): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] not available
I/io.jxcore.node.ConnectionHelper( 3272): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565]
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565] removed
D/io.jxcore.node.ConnectionHelper( 3272): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3565] not available
,W/bt-sdp  ( 2072): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2072): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2072): invalid rfc slot id: 31
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 372)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): shutdown (thread ID: 372)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Maximum number of allowed retries (0) reached, giving up... (thread ID: 372)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 372)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,I/jxcore-log( 3272): 2015-12-18T12:57:21.761Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:57:21.763Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3272): 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:1F:C9:5E
E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Failed to disconnect (peer ID: E0:DB:10:1F:C9:5E), either no such connection or failed to close the connection
I/jxcore-log( 3272): 2015-12-18T12:57:26.771Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:57:26.771Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:57:26.772Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:57:26.773Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
,I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to Note3-1 in address E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: Note3-1 E0:DB:10:1F:C9:5E
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to Note3-1 in address E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: E0:DB:10:1F:C9:5E)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address E0:DB:10:1F:C9:5E (thread ID: 376)
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3272): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionTimeout: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
I/jxcore-log( 3272): 2015-12-18T12:57:41.795Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] timed out
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:57:41.796Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] timed out
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:57:41.796Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:57:46.797Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:57:46.798Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3272): 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pManager( 3272): Ignored { when=-24ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:1F:C9:5E
E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Failed to disconnect (peer ID: E0:DB:10:1F:C9:5E), either no such connection or failed to close the connection
I/jxcore-log( 3272): 2015-12-18T12:57:51.802Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:57:51.803Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:57:51.807Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:57:51.810Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
,I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to Note3-1 in address E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: Note3-1 E0:DB:10:1F:C9:5E
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to Note3-1 in address E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: E0:DB:10:1F:C9:5E)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address E0:DB:10:1F:C9:5E (thread ID: 378)
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2072): SDP - Rcvd conn cnf with error: 0x22  CID 0x45
E/bt-btif ( 2072): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2072): invalid rfc slot id: 32
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 374)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Maximum number of allowed retries (0) reached, giving up... (thread ID: 374)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 374)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): shutdown (thread ID: 374)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
I/jxcore-log( 3272): 2015-12-18T12:57:55.494Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] failed
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:57:55.495Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] failed
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:57:55.526Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3272): 
D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:1F:C9:5E
E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Failed to disconnect (peer ID: E0:DB:10:1F:C9:5E), either no such connection or failed to close the connection
I/jxcore-log( 3272): 2015-12-18T12:57:55.529Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3272): 
I/jxcore-log( 3272): ---- round done--------
I/jxcore-log( 3272): 
I/jxcore-log( 3272): ---- gotta redo : E0:DB:10:1F:C9:5E, try count now: 1
I/jxcore-log( 3272): 
I/jxcore-log( 3272): do fake peer & start
I/jxcore-log( 3272): 
I/jxcore-log( 3272): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:57:55.532Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:57:55.533Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:57:55.541Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to G3s-1 in address F8:95:C7:87:85:54
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: G3s-1 F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to G3s-1 in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
I/chromium( 3272): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:1F:C9:5E done with result: Connection to peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178] failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 380)
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionTimeout: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/jxcore-log( 3272): 2015-12-18T12:58:10.561Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] timed out
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:58:10.561Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] timed out
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:58:10.562Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3272): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/jxcore-log( 3272): 2015-12-18T12:58:15.562Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:58:15.563Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3272): 
,I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:85:54), either no such connection or failed to close the connection
I/jxcore-log( 3272): 2015-12-18T12:58:20.568Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:58:20.569Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:58:20.569Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:58:20.570Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to G3s-1 in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: G3s-1 F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to G3s-1 in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 382)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3272): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,W/bt-sdp  ( 2072): SDP - Rcvd conn cnf with error: 0x22  CID 0x47
E/bt-btif ( 2072): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2072): invalid rfc slot id: 33
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): shutdown (thread ID: 376)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 376)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionTimeout: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/jxcore-log( 3272): 2015-12-18T12:58:35.586Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] timed out
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:58:35.587Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] timed out
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:58:35.587Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:58:40.589Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:58:40.590Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3272): 
,D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:85:54), either no such connection or failed to close the connection
,I/jxcore-log( 3272): 2015-12-18T12:58:45.597Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:58:45.598Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:58:45.598Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:58:45.599Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to G3s-1 in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: G3s-1 F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to G3s-1 in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 384)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3272): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,W/bt-sdp  ( 2072): SDP - Rcvd conn cnf with error: 0x22  CID 0x48
E/bt-btif ( 2072): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2072): invalid rfc slot id: 34
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): shutdown (thread ID: 378)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 378)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Maximum number of allowed retries (0) reached, giving up... (thread ID: 378)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 378)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT9178]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,W/bt-btif ( 2072): info:x10
,D/        ( 2072): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1466): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1466): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 2072): process_service_search_attr_rsp
,W/bt-sdp  ( 2072): process_service_search_attr_rsp
,E/bt-rfcomm( 2072): RFCOMM_CreateConnection - already opened state:1, RFC state:0, MCB state:1
E/bt-btif ( 2072): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/bt-btif ( 2072): invalid rfc slot id: 36
,W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2072): process_service_search_attr_rsp
,E/bt-rfcomm( 2072): RFCOMM_CreateConnection - already opened state:1, RFC state:0, MCB state:1
E/bt-btif ( 2072): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/bt-btif ( 2072): invalid rfc slot id: 37
,W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2072): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2072): Entering PendingCommandState State
,W/bt-sdp  ( 2072): process_service_search_attr_rsp
,E/bt-rfcomm( 2072): RFCOMM_CreateConnection - already opened state:1, RFC state:0, MCB state:1
E/bt-btif ( 2072): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 382)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Maximum number of allowed retries (0) reached, giving up... (thread ID: 382)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 382)
,W/bt-btif ( 2072): invalid rfc slot id: 38
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): shutdown (thread ID: 382)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/jxcore-log( 3272): 2015-12-18T12:59:01.130Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] failed
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:59:01.131Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] failed
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:59:01.131Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3272): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2072): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2072): StableState(): Entering Off State
,W/bt-sdp  ( 2072): process_service_search_attr_rsp
,E/bt-rfcomm( 2072): RFCOMM_CreateConnection - already opened state:1, RFC state:0, MCB state:3
E/bt-btif ( 2072): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 384)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Maximum number of allowed retries (0) reached, giving up... (thread ID: 384)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 384)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): shutdown (thread ID: 384)
,W/bt-btif ( 2072): invalid rfc slot id: 39
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,W/bt-btif ( 2072): new conn_srvc id:26, app_id:1
W/bt-btif ( 2072): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2072): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onSocketConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 380)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): shutdown (thread ID: 380)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): onBytesWritten: 77 bytes successfully written (thread ID: 386)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Unexpected error: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): java.lang.NullPointerException: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:186)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onConnectionFailed: Unexpected error: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 380)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionFailed: Unexpected error: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Entering thread (ID: 386)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Exiting thread (ID: 386)
,W/bt-btif ( 2072): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,D/btif_config_util( 2072): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2072): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2072): onReceive
,I/BTConnectionReceiver( 1466): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1466): Bluetooth Device Name: G3s-1
,I/jxcore-log( 3272): 2015-12-18T12:59:06.131Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:59:06.131Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3272): 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:85:54), either no such connection or failed to close the connection
,I/jxcore-log( 3272): 2015-12-18T12:59:11.135Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:59:11.136Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:59:11.136Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:59:11.137Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to G3s-1 in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: G3s-1 F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to G3s-1 in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 387)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3272): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2072): info:x10
,D/        ( 2072): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1466): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1466): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 2072): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2072): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2072): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2072): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2072): StableState(): Entering Off State
,W/bt-btif ( 2072): new conn_srvc id:26, app_id:1
W/bt-btif ( 2072): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2072): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onSocketConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 387)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): onBytesWritten: 77 bytes successfully written (thread ID: 388)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Outgoing connection initialized (*handshake* thread ID: 388)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 387)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Entering thread (ID: 388)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): onBytesRead: Read 77 bytes successfully (thread ID: 388)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Handshake succeeded with [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onHandshakeSucceeded: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Exiting thread (ID: 388)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Outgoing connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3272): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3272): Entering thread (ID: 389)
D/io.jxcore.node.OutgoingSocketThread( 3272): Server socket local port: 54136
I/io.jxcore.node.OutgoingSocketThread( 3272): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3272): onListeningForIncomingConnections: Outgoing connection is using port 54136 (peer ID: F8:95:C7:87:85:54)
I/jxcore-log( 3272): 2015-12-18T12:59:15.366Z SendDataConnector.js: CLIENT connected to 54136, error: null
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:59:15.367Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3272): 
,I/io.jxcore.node.OutgoingSocketThread( 3272): Incoming data from address: /127.0.0.1, port: 54136
D/io.jxcore.node.OutgoingSocketThread( 3272): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3272): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3272): Exiting thread (ID: 389)
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 391, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 390, name: Sender)
,I/jxcore-log( 3272): 2015-12-18T12:59:15.405Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:59:16.045Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:59:16.126Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:59:16.220Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3272): 
,W/ProcessCpuTracker(  733): Skipping unknown process pid 3897
,W/ProcessCpuTracker(  733): Skipping unknown process pid 3900
,I/jxcore-log( 3272): 2015-12-18T12:59:16.321Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:59:16.399Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:59:16.553Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:59:16.674Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:59:16.756Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:59:16.803Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:59:16.895Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:59:16.896Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T12:59:16.911Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:59:16.912Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3272): 
,D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:85:54
I/io.jxcore.node.OutgoingSocketThread( 3272): close
D/io.jxcore.node.OutgoingSocketThread( 3272): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 391
D/io.jxcore.node.OutgoingSocketThread( 3272): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 390
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 390, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3272): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3272): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3272): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 391, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3272): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:85:54
,E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 390, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 391, name: Receiver)
,I/jxcore-log( 3272): 2015-12-18T12:59:16.952Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3272): 
I/jxcore-log( 3272): ---- round done--------
I/jxcore-log( 3272): 
I/jxcore-log( 3272): do fake peer & start
I/jxcore-log( 3272): 
I/jxcore-log( 3272): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:59:16.953Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:59:16.953Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T12:59:16.953Z SendDataConnector.js: do connect now
I/jxcore-log( 3272): 
I/io.jxcore.node.ConnectionHelper( 3272): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): connect: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnecting: Note4-1 E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3272): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,I/chromium( 3272): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:95:C7:87:85:54 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 392)
W/BluetoothAdapter( 3272): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2072): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2072): tBTM_SEC_DEV:0xa405196c rs_disc_pending=1
W/bt-btif ( 2072): bta_dm_check_av:0
,W/bt-btif ( 2072): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2072): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,W/bt-btif ( 2072): info:x10
,D/        ( 2072): remote version info [e0:db:10:14:e2:c0]: 7, f, 610c
,I/BTConnectionReceiver( 1466): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1466): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 2072): process_service_search_attr_rsp
,W/bt-btif ( 2072): new conn_srvc id:26, app_id:1
W/bt-btif ( 2072): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2072): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onSocketConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3932]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 392)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): onBytesWritten: 77 bytes successfully written (thread ID: 393)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Outgoing connection initialized (*handshake* thread ID: 393)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): Exiting thread (thread ID: 392)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Entering thread (ID: 393)
,E/bt-btm  ( 2072): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2072): onReceive
,I/BTConnectionReceiver( 1466): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1466): Bluetooth Device Name: G3s-1
,D/btif_config_util( 2072): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2072): dm_pm_timer expires
W/bt-btif ( 2072): dm_pm_timer expires 0
W/bt-btif ( 2072): proc dm_pm_timer expires
,W/bt-btif ( 2072): invalid rfc slot id: 41
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Disconnected: bt socket closed, read return: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): onDisconnected: [null null null] (thread ID: 393)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onConnectionFailed: Socket disconnected
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): shutdown (thread ID: 392)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Exiting thread (ID: 393)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnectionFailed: Socket disconnected [null null null]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3272): shutdown (thread ID: 392)
,E/bt-btm  ( 2072): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2072): onReceive
,I/BTConnectionReceiver( 1466): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1466): Bluetooth Device Name: Note4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: RESTARTING
,I/wpa_supplicant( 1019): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Start timer timeout, starting now...
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/WifiP2pManager( 3272): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  733): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3910 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3910): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3910):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3910):   adb logcat -s GAv4
,W/GAv4    ( 3910): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3910): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3910): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  733): Killing 2998:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10008/pid_2998/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: RESTARTING
,I/wpa_supplicant( 1019): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Start timer timeout, starting now...
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT9351","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], Bluetooth address: F8:CF:C5:D9:E5:61, device name: Android_50a5, device address: fa:cf:c5:d9:e5:62
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-8ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully,
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] removed
D/io.jxcore.node.ConnectionHelper( 3272): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: RESTARTING
,I/wpa_supplicant( 1019): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Start timer timeout, starting now...
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3272): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: RESTARTING
,I/wpa_supplicant( 1019): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Start timer timeout, starting now...
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: RESTARTING
,I/wpa_supplicant( 1019): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Start timer timeout, starting now...
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT9351","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: fa:cf:c5:d9:e5:62
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT9351","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], Bluetooth address: F8:CF:C5:D9:E5:61, device name: Android_50a5, device address: fa:cf:c5:d9:e5:62
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3272): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] is available
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: RESTARTING
,I/wpa_supplicant( 1019): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Start timer timeout, starting now...
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT9351","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], Bluetooth address: F8:CF:C5:D9:E5:61, device name: Android_50a5, device address: fa:cf:c5:d9:e5:62
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,W/bt-btif ( 2072): info:x10
,D/        ( 2072): remote version info [f8:95:c7:87:3c:51]: 6, f, 410d
,I/BTConnectionReceiver( 1466): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1466): Bluetooth Device Name: G4-1
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2072): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2072): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2072): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2072): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2072): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2072): StableState(): Entering Off State
,W/bt-btif ( 2072): new conn_srvc id:26, app_id:255
W/bt-btif ( 2072): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2072): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Incoming connection initialized (thread ID: 395)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Entering thread (ID: 395)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): onBytesRead: Read 77 bytes successfully (thread ID: 395)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): onBytesWritten: 77 bytes successfully written (thread ID: 395)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): removeThreadFromList: Removing thread with ID 395
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Handshake thread disposed (thread ID: 395)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3272): Exiting thread (ID: 395)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Incoming connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3272): onConnected: Incoming socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], created successfully
D/io.jxcore.node.ConnectionHelper( 3272): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3272): Entering thread (ID: 396)
,I/jxcore-log( 3272): 2015-12-18T13:05:05.591Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3272): 
,I/io.jxcore.node.IncomingSocketThread( 3272): Local host address: localhost/127.0.0.1, port: 55815
D/io.jxcore.node.IncomingSocketThread( 3272): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3272): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3272): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3272): Exiting thread (ID: 396)
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 398, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3272): Entering thread (ID: 397, name: Sender)
,I/jxcore-log( 3272): 2015-12-18T13:05:06.310Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.313Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.317Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.321Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.375Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.379Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.394Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.415Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.455Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.460Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.509Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.545Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.565Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.606Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.630Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.666Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.690Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.745Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.763Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.813Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.826Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.856Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.889Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.938Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:06.956Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:07.006Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:07.035Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:07.061Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:07.115Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:07.169Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:07.184Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:07.235Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:05:07.282Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3272): 
,W/bt-btif ( 2072): invalid rfc slot id: 21
,W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 398, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3272): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 396
D/io.jxcore.node.IncomingSocketThread( 3272): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 398
D/io.jxcore.node.IncomingSocketThread( 3272): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3272): doStop: Thread ID: 397
,D/io.jxcore.node.IncomingSocketThread( 3272): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3272): Either failed to read from the output stream or write to the input stream (thread ID: 397, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3272): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3272): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3272): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3272): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 3272): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 397, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3272): Exiting thread (ID: 398, name: Receiver)
,I/jxcore-log( 3272): 2015-12-18T13:05:07.459Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3272): 
,W/bt-rfcomm( 2072): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 2072): RFCOMM_DisconnectInd LCID:0x46
,D/btif_config_util( 2072): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2072): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2072): onReceive
,I/BTConnectionReceiver( 1466): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1466): Bluetooth Device Name: G4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: RESTARTING
,I/wpa_supplicant( 1019): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/WifiP2pManager( 3272): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/UsageStatsService(  733): User[0] Flushing usage stats to disk
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): checkListForExpiredPeers: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Removed [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerLost: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/io.jxcore.node.ConnectionHelper( 3272): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351] removed
D/io.jxcore.node.ConnectionHelper( 3272): notifyPeerAvailability: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351] not available
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT9351","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: fa:cf:c5:d9:e5:62
D/io.jxcore.node.ConnectionHelper( 3272): notifyPeerAvailability: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT9351","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
,I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: fa:cf:c5:d9:e5:62
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT9351","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], Bluetooth address: F8:CF:C5:D9:E5:61, device name: Android_50a5, device address: fa:cf:c5:d9:e5:62
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT9351]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: RESTARTING
,I/wpa_supplicant( 1019): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Start timer timeout, starting now...
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-8ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: RESTARTING
,I/wpa_supplicant( 1019): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED ,
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3272): timeout now
I/jxcore-log( 3272): 
I/jxcore-log( 3272): dun
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): weAreDoneNow , resultArray.length: 6
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): done, now sending data to server
I/jxcore-log( 3272): 
I/jxcore-log( 3272): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): -- RESULT DATA {"name:":"LGE-Nexus 5_PT8301","time":1000074,"result":"TIMEOUT","sendList":[{"name":"F8:CF:C5:D9:E5:61","time":10167,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":13693,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":8224,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":7348,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":6265,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":81364,"result":"OK","connections":4,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections
I/jxcore-log( 3272): sendList : 100% : 81364 ms, 99% : 81364 ms, 95 : 81364 ms, 90% : 13693 ms.
I/jxcore-log( 3272): 
I/jxcore-log( 3272): Result count 6, range 6265 ms to  81364 ms.
I/jxcore-log( 3272): 
I/jxcore-log( 3272): sendList failed peers count : 4 [40 %]
I/jxcore-log( 3272): 
I/jxcore-log( 3272): - Peer ID : E0:DB:10:14:E2:C0, Tried : 1
I/jxcore-log( 3272): 
I/jxcore-log( 3272): - Peer ID : 08:EC:A9:50:75:41, Tried : 1
I/jxcore-log( 3272): 
I/jxcore-log( 3272): - Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
I/jxcore-log( 3272): 
I/jxcore-log( 3272): - Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
I/jxcore-log( 3272): 
I/jxcore-log( 3272): sendList never tried peers count : 6 [37.5 %]
I/jxcore-log( 3272): 
I/jxcore-log( 3272): - Peer ID : 7C:F9:0E:37:96:AB
I/jxcore-log( 3272): 
I/jxcore-log( 3272): - Peer ID : B0:C5:59:3F:75:69
I/jxcore-log( 3272): 
I/jxcore-log( 3272): - Peer ID : 90:E7:C4:F6:69:77
I/jxcore-log( 3272): 
I/jxcore-log( 3272): - Peer ID : 08:EC:A9:50:76:27
I/jxcore-log( 3272): 
I/jxcore-log( 3272): - Peer ID : 44:80:EB:7B:5A:05
I/jxcore-log( 3272): 
I/jxcore-log( 3272): - Peer ID : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3272): 
I/jxcore-log( 3272): 2015-12-18T13:10:12.187Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3272): 
D/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
E/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3272): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3272): disconnectOutgoingConnection: Failed to disconnect (peer ID: E0:DB:10:14:E2:C0), either no such connection or failed to close the connection
I/jxcore-log( 3272): 2015-12-18T13:10:12.187Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3272): 
,I/chromium( 3272): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3272): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: RESTARTING
,I/wpa_supplicant( 1019): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,D/WifiP2pManager( 3272): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Start timer timeout, starting now...
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: RESTARTING
,I/wpa_supplicant( 1019): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Start timer timeout, starting now...
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/WifiP2pManager( 3272): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: RESTARTING
,I/wpa_supplicant( 1019): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): P2P device discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
,I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5199","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3638","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9700","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4778","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
I/io.jxcore.node.ConnectionHelper( 3272): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3272): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778] already in the list, will not add again
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5199], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5199]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4778]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3638], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3638]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9700]
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/HeadsetStateMachine( 2072): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 2072): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 2072): Disconnected process message: 11, size: 0
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: RESTARTING
,I/wpa_supplicant( 1019): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1019): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): P2P device discovery started successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1019): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): restart: Restarting...
,D/WifiP2pManager( 3272): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service request added successfully
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1019): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3272): Service discovery started successfully
,I/jxcore-log( 3272): DBG, CoordinatorConnector command called
I/jxcore-log( 3272): 
I/jxcore-log( 3272): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): stop tests now !
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): stop current!
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): testSendData stopped
I/jxcore-log( 3272): 
I/io.jxcore.node.ConnectionHelper( 3272): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3272): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3272): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3272): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3272): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3272): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3272): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3272): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3272): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3272): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): setState: NOT_STARTED
I/jxcore-log( 3272): StopBroadcasting went ok
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): 2015-12-18T13:14:32.188Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3272): 
I/chromium( 3272): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3272): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3272): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3272): DBG, CoordinatorConnector command called
I/jxcore-log( 3272): 
I/jxcore-log( 3272): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"7C:F9:0E:34:8A:A0\",\"time\":6265,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"F8:95:C7:87:3C:51\",\"time\":7348,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"7C:F9:0E:51:18:22\",\"time\":8224,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"F8:CF:C5:D9:E5:61\",\"time\":10167,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"58:3F:54:73:64:C0\",\"time\":13693,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"F8:95:C7:87:85:54\",\"time\":81364,\"result\":\"OK\",\"connections\":4,\"tryCount\":1,\"doneRounds\":1,\"dat
I/jxcore-log( 3272): ****TEST TOOK:  ms ****
I/jxcore-log( 3272): 
I/jxcore-log( 3272): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3272): 
I/jxcore-log( 3272): stop tests now !
I/jxcore-log( 3272): 
I/jxcore-log( 3272): end, event received
I/jxcore-log( 3272): 
I/jxcore-log( 3272): CoordinatorConnector close called
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3272): 
I/jxcore-log( 3272): The Coordinator has disconnected!
I/jxcore-log( 3272): 
I/jxcore-log( 3272): The Coordinator has closed!
I/jxcore-log( 3272): 
I/jxcore-log( 3272): stop tests now !
I/jxcore-log( 3272): 
I/jxcore-log( 3272): turning Radios off
I/jxcore-log( 3272): 
I/jxcore-log( 3272): Toggling radios to false
I/jxcore-log( 3272): 
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  733): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@14c1ff0f mBinding = false
,D/BluetoothManagerService(  733): Message: 2
D/BluetoothManagerService(  733): Sending off request.
D/BluetoothAdapterState( 2072): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2072): Setting state to 13
I/BluetoothAdapterState( 2072): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 2072): onBluetoothDisable()
I/BluetoothAdapterState( 2072): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterProperties( 2072): Scan Mode:20
D/BluetoothAdapterState( 2072): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 2072): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2072): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2072): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2072): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2072): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2072): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2072): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2072): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,D/btif_config_util( 2072): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
E/BtOppRfcommListener( 2072): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 2072): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,W/bt-l2cap( 2072): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2072): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  733): Message: 60
D/BluetoothManagerService(  733): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService(  733): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 2072): onReceive
D/BluetoothMapService( 2072): STATE_TURNING_OFF
V/BluetoothMapService( 2072): Handler(): got msg=4
D/BluetoothMapService( 2072): MAP Service closeService in
D/BluetoothMapMasInstance( 2072): MAP Service shutdown
V/BluetoothMapService( 2072): MAP Service closeService out
,I/BtOppRfcommListener( 2072): stopping Accept Thread
,I/BtOppRfcommListener( 2072): BluetoothSocket listen thread finished
,D/WifiService(  733): setWifiEnabled: false pid=3272, uid=10270
E/WifiService(  733): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 3712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,E/WifiStateMachine(  733): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
I/jxcore-log( 3272): Radios toggled
I/jxcore-log( 3272): 
I/chromium( 3272): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BluetoothManagerService(  733): Message: 30
,D/BluetoothManagerService(  733): Message: 30
D/LocalBluetoothProfileManager( 3712): Adding local MAP profile
D/BluetoothMap( 3712): Create BluetoothMap proxy object
D/BluetoothManagerService(  733): Message: 30
D/BluetoothManagerService(  733): Message: 30
D/LocalBluetoothProfileManager( 3712): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3712): finishStartingService: stopping service
,W/bt-btif ( 2072): ag scb idx 1 not allocated
E/bt-btif ( 2072): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2072): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2072): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2072): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2072): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2072): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2072): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 2072): RX termination
W/bt_userial( 2072): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 2072): Leaving userial_read_thread()
D/bt_userial( 2072): userial_close_reader Joined userial reader thread: 0
,D/bt_hwcfg( 2072): hw_epilog_process
,I/bt_userial_vendor( 2072): device fd = 53 close
,I/GKI_LINUX( 2072): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2072): GKI_exit_task 0 done
I/GKI_LINUX( 2072): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 2072): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 2072): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2072): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1326a905
D/HeadsetStateMachine( 2072): Exit Disconnected: -1
D/BluetoothHeadset(  733): Proxy object disconnected
D/BluetoothHeadset( 1251): Proxy object disconnected
,D/BluetoothAdapterState( 2072): Stopping profile services that were post enabled
,D/A2dpService( 2072): Received stop request...Stopping profile...
D/A2dpStateMachine( 2072): Exit Disconnected: -1
D/BluetoothAdapterService( 2072): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1326a905
,D/BluetoothA2dp(  733): Proxy object disconnected
D/HidService( 2072): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2072): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1326a905
,D/HealthService( 2072): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2072): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1326a905
,D/PanService( 2072): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2072): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1326a905
,D/BtGatt.DebugUtils( 2072): handleDebugAction() action=null
,D/BtGatt.GattService( 2072): Received stop request...Stopping profile...
D/BtGatt.GattService( 2072): stop()
D/BtGatt.AdvertiseManager( 2072): advertise clients cleared
D/BluetoothHeadset( 1218): Proxy object disconnected
D/BluetoothAdapterService( 2072): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1326a905
D/BluetoothHeadset( 1218): Proxy object disconnected
,D/HeadsetStateMachine( 2072): Unbinding service...
W/BluetoothHeadsetServiceJni( 2072): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2072): Cleaning up Bluetooth Handsfree callback object
D/BluetoothMapService( 2072): Received stop request...Stopping profile...
D/BluetoothMapService( 2072): stop()
D/BluetoothMapEmailAppObserver( 2072): deinitObservers()
D/BluetoothMapEmailAppObserver( 2072): removeReceiver()
D/BluetoothAdapterService( 2072): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1326a905
I/GKI_LINUX( 2072): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2072): GKI_exit_task 2 done
I/GKI_LINUX( 2072): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 2072): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2072): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2072): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 2072): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2072): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 2072): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2072): Cleaning up Bluetooth PAN callback object
V/BluetoothMapService( 2072): Handler(): got msg=4
D/BluetoothMapService( 2072): MAP Service closeService in
V/BluetoothMapService( 2072): MAP Service closeService out
D/BluetoothMapService( 2072): cleanup()
D/BluetoothMapService( 2072): MAP Service closeService in
V/BluetoothMapService( 2072): MAP Service closeService out
D/BluetoothAdapterState( 2072): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2072): Setting state to 10
I/BluetoothAdapterState( 2072): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  733): Message: 60
D/BluetoothManagerService(  733): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  733): Broadcasting onBluetoothStateChange(false) to 9 receivers.
I/BluetoothAdapterState( 2072): Entering OffState
D/BluetoothMap( 3712): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1218): onBluetoothStateChange: up=false
D/BluetoothHeadset(  733): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1251): onBluetoothStateChange: up=false
D/BluetoothPbap( 3712): onBluetoothStateChange: up=false
D/BluetoothA2dp(  733): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1218): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 3712): onBluetoothStateChange: up=false
D/BluetoothManagerService(  733): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  733): Broadcasting onBluetoothServiceDown() to 10 receivers.
,D/BluetoothManagerService(  733): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@14c1ff0f mBinding = false
,D/BluetoothManagerService(  733): Sending unbind request.
,D/BluetoothManagerService(  733): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  888): 179017886: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  888): 179017886: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  888): 179017886: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 2072): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2072): GKI_exit_task 1 done
I/GKI_LINUX( 2072): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2072): cleanupNative: return from cleanup
,D/BluetoothAdapter( 1572): 269547801: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1572): 269547801: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1572): 269547801: getState() :  mService = null. Returning STATE_OFF
E/BluetoothDevice( 1572): BT not enabled. Cannot get Bluetooth Class
E/BluetoothDevice( 1572): BT not enabled. Cannot get Remote Device name
E/BluetoothDevice( 1572): BT not enabled. Cannot get Remote Device Alias
E/BluetoothDevice( 1572): BT not enabled. Cannot get Bluetooth Class
E/BluetoothDevice( 1572): BT not enabled. Cannot get Bluetooth Class
E/BluetoothDevice( 1572): BT not enabled. Cannot get Remote Device name
E/BluetoothDevice( 1572): BT not enabled. Cannot get Remote Device Alias
,I/art     ( 2072): System.exit called, status: 0
I/AndroidRuntime( 2072): VM exiting with result code 0, cleanup skipped.
,D/AndroidRuntime( 3983): 
D/AndroidRuntime( 3983): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3983): CheckJNI is OFF
,I/art     (  733): Explicit concurrent mark sweep GC freed 115575(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 29MB/43MB, paused 1.186ms total 101.391ms
,I/ActivityManager(  733): Process com.android.bluetooth (pid 2072) has died
,D/WifiService(  733): New client listening to asynchronous messages
,D/AndroidRuntime( 3983): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  733): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  733): Killing 3272:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,W/PackageSettings(  733): Skipping PackageSetting{215d6750 com.example.hello/10278} due to missing metadata
,I/WindowState(  733): WIN DEATH: Window{3163b43 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  733): Client connection lost with reason: 4
,E/libprocessgroup(  733): failed to kill 1 processes for processgroup 3272
,I/ActivityManager(  733):   Force finishing activity ActivityRecord{b37ebf u0 com.test.thalitest/.MainActivity t214}
,I/ActivityManager(  733): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=4027 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/ActivityManager(  733): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  733):   Force finishing activity ActivityRecord{b37ebf u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  733): Duplicate finish request for ActivityRecord{b37ebf u0 com.test.thalitest/.MainActivity t214 f}
,W/ActivityManager(  733): Spurious death for ProcessRecord{38265615 3272:com.test.thalitest/u0a270}, curProc for 3272: null
,I/InputReader(  733): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1572): Ignoring removeGeofence because network location is disabled.
,I/art     ( 1271): Explicit concurrent mark sweep GC freed 3944(293KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 957us total 29.898ms
I/Keyboard.Facilitator( 1083): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1083): run()
,I/Decoder ( 1083): createOrResetDecoder
,I/Adreno-EGL(  941): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  941): Initialized EGL, version 1.4
I/art     ( 1466): Explicit concurrent mark sweep GC freed 46521(2MB) AllocSpace objects, 9(144KB) LOS objects, 25% free, 19MB/25MB, paused 353us total 76.980ms
,I/ConfigService( 1572): onCreate
,W/ResourcesManager( 4027): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/OpenGLRenderer(  941): Enabling debug mode 0
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1083): run()
,I/art     ( 1627): Explicit concurrent mark sweep GC freed 21057(1233KB) AllocSpace objects, 5(80KB) LOS objects, 25% free, 22MB/30MB, paused 1.624ms total 122.811ms
,D/BackupManagerService(  733): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  733): Receieved: android.intent.action.PACKAGE_REMOVED
,D/AdapterServiceConfig( 4027): Adding HeadsetService
D/AdapterServiceConfig( 4027): Adding A2dpService
D/AdapterServiceConfig( 4027): Adding HidService
,D/AdapterServiceConfig( 4027): Adding HealthService
,D/AdapterServiceConfig( 4027): Adding PanService
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1083): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
D/AdapterServiceConfig( 4027): Adding GattService
D/AdapterServiceConfig( 4027): Adding BluetoothMapService
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Loading LM = contacts
I/ActivityManager(  733): Killing 2796:com.android.providers.calendar/u0a2 (adj 15): empty #17
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1083): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1083): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1083): run()
I/StatsUtilsManager( 1083): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1083): shouldRecordStats() = Too Soon
,W/InputMethodManagerService(  733): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@3decee63 (uid=10034 pid=941)
,W/libprocessgroup(  733): failed to open /acct/uid_10002/pid_2796/cgroup.procs: No such file or directory
,D/AuthorizationBluetoothService( 1572): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/TaskPersister(  733): removeObsoleteFile: deleting file=214_task.xml
W/ContextImpl( 3712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 3712): finishStartingService: stopping service
,I/art     (  733): Explicit concurrent mark sweep GC freed 39649(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 28MB/42MB, paused 1.275ms total 226.841ms
,D/BluetoothAdapter( 3712): 102403506: getState() :  mService = null. Returning STATE_OFF
,D/AuthorizationBluetoothService( 1572): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/VoicemailCleanupService( 2861): Cleaning up data for package: com.test.thalitest
,I/UpdateIcingCorporaServi( 1466): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1271): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1326a905 new=com.google.android.velvet.VelvetApplication@1326a905
,I/ActivityManager(  733): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4057 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/Launcher( 1271): Deferring update until onResume
,D/AndroidRuntime( 3983): Shutting down VM
,W/ResourcesManager( 1271): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ContextImpl( 4057): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,W/ResourcesManager( 1271): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1271): Deferring update until onResume
,E/DataBuffer( 1572): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@109bcf65)
,E/DataBuffer( 1572): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@18a6443a)
I/art     ( 1572): Explicit concurrent mark sweep GC freed 89034(4MB) AllocSpace objects, 25(400KB) LOS objects, 39% free, 22MB/38MB, paused 673us total 43.206ms
,E/DataBuffer( 1572): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2670e8eb)
E/DataBuffer( 1572): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@15ccf648)
,E/DataBuffer( 1572): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3efefce1)
,E/DataBuffer( 1572): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@16f328c7)
,D/PackageBroadcastService( 1627): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1627): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1627): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1627): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1627): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1627): Module APK com.google.android.play.games already loaded
I/UpdateIcingCorporaServi( 1466): UpdateCorporaTask done [took 149 ms] updated apps [took 149 ms] 
,E/NetworkScheduler.SchedulerReceiver( 1572): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1572): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1627): Removing dialog suppression flag for package com.test.thalitest
,D/gH_CompatibleDatabase( 1627): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1627): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1627): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1627): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1627): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1627): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1627): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1627): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1627): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1627): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1627): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1627): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1627): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  733): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4086 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,W/BaseAppContext( 1627): Using Auth Proxy for data requests.
W/BaseAppContext( 1627): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1627): App measurement is starting up, version: 8489
I/GMPM-SVC( 1627): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/ActivityManager(  733): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4109 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  733): Killing 1503:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10013/pid_1503/cgroup.procs: No such file or directory
,I/ActivityManager(  733): Killing 3072:com.android.defcontainer/u0a5 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10005/pid_3072/cgroup.procs: No such file or directory
,E/SQLiteLog( 1627): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/GMPM-SVC( 1627): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
,D/ExternalStorage( 4109): After updating volumes, found 1 active roots
,E/SharedPreferencesImpl( 1627): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,I/Icing   ( 1627): doRemovePackageData com.test.thalitest
,W/ResourcesManager( 3175): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3175): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 4086): Update found 7 roots in 196ms
,D/Documents( 4086): Update found 7 roots in 66ms

```
