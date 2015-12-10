#### Test 5065027881383b1_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3191): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3191):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3191):   adb logcat -s GAv4
W/GAv4    ( 3191): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3191): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3191): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3191): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,D/Finsky  ( 2617): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3191): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3191): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  758): Killing 2003:com.google.android.deskclock/u0a38 (adj 15): empty #17
D/AndroidRuntime( 3241): 
D/AndroidRuntime( 3241): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3241): CheckJNI is OFF
W/libprocessgroup(  758): failed to open /acct/uid_10038/pid_2003/cgroup.procs: No such file or directory
V/JNIHelp ( 3191): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3191): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3191): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1561): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3241): Calling main entry com.android.commands.am.Am
I/ActivityManager(  758): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/Icing   ( 1621): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/ActivityManager(  758): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3266 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3241): Shutting down VM
V/ActivityManager(  758): Display changed displayId=0
I/Icing   ( 1621): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1621): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/WebViewFactory( 3266): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/Icing   ( 1621): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/LibraryLoader( 3266): Time to load native libraries: 1 ms (timestamps 7364-7365)
I/LibraryLoader( 3266): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3266): Binding Chromium to main looper Looper (main, tid 1) {3eebad06}
I/LibraryLoader( 3266): Expected native library version number "",actual native library version number ""
I/chromium( 3266): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3266): Initializing chromium process, singleProcess=true
W/art     ( 3266): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3266): ApplicationContext is null in ApplicationStatus
W/chromium( 3266): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3266): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3266): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3266): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ee8e47d:true
W/art     ( 3266): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3266): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3266): CordovaWebView is running on device made by: LGE
W/art     ( 3266): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3266): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3266): Render dirty regions requested: true
D/Atlas   ( 3266): Validating map...
W/chromium( 3266): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3266): Initialized EGL, version 1.4
D/OpenGLRenderer( 3266): Enabling debug mode 0
W/IInputConnectionWrapper( 3266): showStatusIcon on inactive InputConnection
I/ActivityManager(  758): Displayed com.test.thalitest/.MainActivity: +423ms (total +56s62ms)
W/BindingManager( 3266): Cannot call determinedVisibility() - never saw a connection for the pid: 3266
D/JsMessageQueue( 3266): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3266): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257343360
D/JX-Cordova( 3266): jxcore cordova android initializing
I/ActivityManager(  758): Killing 2496:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10045/pid_2496/cgroup.procs: No such file or directory
,W/jxcore-log( 3266): Initializing JXcore engine
W/jxcore-log( 3266): JXcore engine is ready
,W/jxcore-log( 3266): Starting JXcore engine
,W/.test.thalitest( 3266): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6475]" dev="sockfs" ino=6475 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3266): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3266): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6601]" dev="sockfs" ino=6601 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3266): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20246]" dev="sockfs" ino=20246 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3266): Platform android
W/jxcore-log( 3266): 
,W/jxcore-log( 3266): Process ARCH arm
W/jxcore-log( 3266): 
,I/jxcore-log( 3266): JXcore Cordova bridge is ready!
I/jxcore-log( 3266): 
W/jxcore-log( 3266): JXcore engine is started
I/Choreographer( 3266): Skipped 105 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3266): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3266): Toggling radios to true
I/jxcore-log( 3266): 
,D/BluetoothAdapter( 3266): enable(): BT is already enabled..!
,D/WifiService(  758): New client listening to asynchronous messages
D/WifiService(  758): setWifiEnabled: true pid=3266, uid=10270
E/WifiService(  758): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3266): Radios toggled
I/jxcore-log( 3266): 
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3266): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3266): 
,I/jxcore-log( 3266): Perf Test app loaded loaded
I/jxcore-log( 3266): 
,I/wpa_supplicant(  989): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  758): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  758): do suspend true
,I/jxcore-log( 3266): check test folder
I/jxcore-log( 3266): 
,D/CommandListener(  178): Clearing all IP addresses on wlan0
I/jxcore-log( 3266): found test : ./testFindPeers.js
I/jxcore-log( 3266): 
,I/jxcore-log( 3266): found test : ./testSendData.js,
I/jxcore-log( 3266): 
,V/NativeCrypto( 1561): Read error: ssl=0x9b408e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1561): SSL shutdown failed: ssl=0x9b408e00: I/O error during system call, Broken pipe
,E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  758): Start Disconnecting Watchdog 1
D/ConnectivityService(  758): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant(  989): wlan0: CTRL-EVENT-SCAN-STARTED 
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,E/native  (  758): do suspend true
,D/ConnectivityService(  758): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/Nat464Xlat(  758): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  758): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Disconnected - quitting
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1621): CM callback handler got msg 524292
D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  758): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/Choreographer( 3266): Skipped 66 frames!  The application may be doing too much work on its main thread.
,D/TelephonyNetworkFactory( 1240): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/chromium( 3266): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiNetworkAgent(  758): NetworkAgent: NetworkAgent channel lost
,W/ProcessCpuTracker(  758): Skipping unknown process pid 3319
W/ProcessCpuTracker(  758): Skipping unknown process pid 3320
W/ProcessCpuTracker(  758): Skipping unknown process pid 3323
,W/ProcessCpuTracker(  758): Skipping unknown process pid 3324
W/ProcessCpuTracker(  758): Skipping unknown process pid 3325
W/ProcessCpuTracker(  758): Skipping unknown process pid 3327
,W/ProcessCpuTracker(  758): Skipping unknown process pid 3328
W/ProcessCpuTracker(  758): Skipping unknown process pid 3334
,W/ProcessCpuTracker(  758): Skipping unknown process pid 3335
,W/ProcessCpuTracker(  758): Skipping unknown process pid 3336
W/ProcessCpuTracker(  758): Skipping unknown process pid 3337
,W/ProcessCpuTracker(  758): Skipping unknown process pid 3340
W/ProcessCpuTracker(  758): Skipping unknown process pid 3343
,I/wpa_supplicant(  989): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,V/GLSActivity( 1561): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1561): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant(  989): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  989): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  989): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  758): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  178): Setting iface cfg
E/WifiStateMachine(  758): Start Dhcp Watchdog 2
,W/NetworkUtils( 1358): OkHttp exception
,W/EventLoggerService( 1358): Unable to send logs Error code: 262146
,E/native  (  758): do suspend false
,E/WifiStateMachine(  758): scanCount==0 - aborting
,I/dhcpcd  ( 3371): version 5.5.6 starting
,E/dhcpcd  ( 3371): get_duid: Read-only file system
,I/dhcpcd  ( 3371): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3371): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3371): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  758): MasterInitialState.processMessage what=3
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  758): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2741): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/iu.Environment( 1621): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1621): num queued entries: 0
,I/iu.UploadsManager( 1621): num updated entries: 0
,I/iu.SyncManager( 1621): NEXT; no task
,I/ActivityManager(  758): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3415 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 1880): connection state changed from CONNECTED to DISCONNECTED
,E/GpsLocationProvider(  758): No APN found to select.
,E/GpsLocationProvider(  758): No APN found to select.
,E/native  (  758): do suspend true
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  758): Adding iface wlan0 to network 101
,E/WifiStateMachine(  758): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  758): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  758): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  758): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  758): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  758): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  758): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  758): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  758): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  758): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  758): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::5255:27ff:fef0:fd0b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  758): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1621): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 13:08:25 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449752905821], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449752905803]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Validated
D/ConnectivityService(  758): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  758): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1621): CM callback handler got msg 524290
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1240): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/GAv4    ( 3415): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3415):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3415):   adb logcat -s GAv4
,W/GAv4    ( 3415): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3415): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3415): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3415): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3415): Time to load native libraries: 1 ms (timestamps 4267-4268)
I/LibraryLoader( 3415): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3415): Binding Chromium to main looper Looper (main, tid 1) {37aff608}
,I/LibraryLoader( 3415): Expected native library version number "",actual native library version number ""
I/chromium( 3415): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3415): Initializing chromium process, singleProcess=true
,W/art     ( 3415): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3415): ApplicationContext is null in ApplicationStatus
,W/chromium( 3415): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3415): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3415): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3415): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3415): Requires BLUETOOTH permission
,I/NSApplication( 3415): Starting up...
,I/ActivityManager(  758): Killing 2713:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10003/pid_2713/cgroup.procs: No such file or directory
,V/MusicLeanback( 2741): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/iu.Environment( 1621): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1621): num queued entries: 0
,I/iu.UploadsManager( 1621): num updated entries: 0
,I/iu.SyncManager( 1621): NEXT; no task
,I/Babel   ( 1880): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  758): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3266): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 3266): 
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  758): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2741): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2741): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  758): No APN found to select.
,D/Finsky  ( 2617): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2617): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/art     (  758): Explicit concurrent mark sweep GC freed 42881(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.154ms total 122.752ms
,V/GLSActivity( 1561): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1561): Vacuum at: now=1449752918955 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1561): disconnect managed GoogleApiClient

```
