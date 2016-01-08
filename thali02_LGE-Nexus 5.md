#### Test 55431344148e3f8_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1577): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1577): Module APK com.google.android.play.games already loaded
,I/GAv4    ( 3139): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3139):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3139):   adb logcat -s GAv4
W/GAv4    ( 3139): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3139): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3139): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3139): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2629): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/AndroidRuntime( 3184): 
D/AndroidRuntime( 3184): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3184): CheckJNI is OFF
--------- beginning of system
W/ResourcesManager( 3139): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3139): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  760): Killing 2594:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3139): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3139): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3139): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 3184): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_2594/cgroup.procs: No such file or directory
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3219 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3184): Shutting down VM
V/ActivityManager(  760): Display changed displayId=0
I/WebViewFactory( 3219): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3219): Time to load native libraries: 1 ms (timestamps 8421-8422)
I/LibraryLoader( 3219): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3219): Binding Chromium to main looper Looper (main, tid 1) {1855a663}
I/LibraryLoader( 3219): Expected native library version number "",actual native library version number ""
I/chromium( 3219): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3219): Initializing chromium process, singleProcess=true
I/Icing   ( 1577): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
W/art     ( 3219): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3219): ApplicationContext is null in ApplicationStatus
W/chromium( 3219): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3219): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3219): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3219): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/Icing   ( 1577): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
D/BluetoothManagerService(  760): Message: 20
I/Icing   ( 1577): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7bf972b:true
W/art     ( 3219): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3219): onDetachedFromWindow called when already detached. Ignoring
I/Icing   ( 1577): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
D/SystemWebViewEngine( 3219): CordovaWebView is running on device made by: LGE
W/art     ( 3219): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3219): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3219): Render dirty regions requested: true
D/Atlas   ( 3219): Validating map...
W/chromium( 3219): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3219): Initialized EGL, version 1.4
D/OpenGLRenderer( 3219): Enabling debug mode 0
W/BindingManager( 3219): Cannot call determinedVisibility() - never saw a connection for the pid: 3219
I/Keyboard.Facilitator( 1064): onFinishInput()
W/IInputConnectionWrapper( 3219): showStatusIcon on inactive InputConnection
I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +459ms (total +55s813ms)
D/JsMessageQueue( 3219): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3219): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257343360
D/JX-Cordova( 3219): jxcore cordova android initializing
,I/ActivityManager(  760): Killing 2550:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_2550/cgroup.procs: No such file or directory
,W/jxcore-log( 3219): Initializing JXcore engine
W/jxcore-log( 3219): JXcore engine is ready
W/jxcore-log( 3219): Starting JXcore engine
,W/.test.thalitest( 3219): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9389]" dev="sockfs" ino=9389 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3219): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3219): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8094]" dev="sockfs" ino=8094 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3219): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18318]" dev="sockfs" ino=18318 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3219): Platform android
W/jxcore-log( 3219): 
W/jxcore-log( 3219): Process ARCH arm
W/jxcore-log( 3219): 
,I/jxcore-log( 3219): JXcore Cordova bridge is ready!
I/jxcore-log( 3219): 
W/jxcore-log( 3219): JXcore engine is started
I/Choreographer( 3219): Skipped 108 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3219): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3219): Toggling radios to true
I/jxcore-log( 3219): 
,D/BluetoothAdapter( 3219): enable(): BT is already enabled..!
,D/WifiService(  760): New client listening to asynchronous messages
,D/WifiService(  760): setWifiEnabled: true pid=3219, uid=10270
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3219): Radios toggled
I/jxcore-log( 3219): 
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3219): Received device characteristics:
I/jxcore-log( 3219): Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3219): Bluetooth name: Nexus 5
I/jxcore-log( 3219): Device name: LGE-Nexus 5
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): Perf Test app loaded loaded
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): check test folder
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): found test : ./testFindPeers.js
I/jxcore-log( 3219): 
,I/wpa_supplicant( 1058): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
E/WifiStateMachine(  760): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  760): do suspend true
,I/jxcore-log( 3219): found test : ./testSendData.js
I/jxcore-log( 3219): 
D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1567): Read error: ssl=0xafa95e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1567): SSL shutdown failed: ssl=0xafa95e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  760): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  760): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1058): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  760): do suspend true
,D/ConnectivityService(  760): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  760): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityManager.CallbackHandler( 1577): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Disconnected - quitting
,D/ConnectivityService(  760): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  760): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory( 1196): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  760): NetworkAgent: NetworkAgent channel lost
,I/Choreographer( 3219): Skipped 74 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3219): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ProcessCpuTracker(  760): Skipping unknown process pid 3285
,W/ProcessCpuTracker(  760): Skipping unknown process pid 3288
W/ProcessCpuTracker(  760): Skipping unknown process pid 3290
,W/ProcessCpuTracker(  760): Skipping unknown process pid 3291
,W/ProcessCpuTracker(  760): Skipping unknown process pid 3295
,W/ProcessCpuTracker(  760): Skipping unknown process pid 3296
,W/ProcessCpuTracker(  760): Skipping unknown process pid 3302
,W/ProcessCpuTracker(  760): Skipping unknown process pid 3303
,I/wpa_supplicant( 1058): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant( 1058): wlan0: Associated with c0:ff:d4:d3:aa:4a
,W/NetworkUtils( 1343): OkHttp exception
,W/EventLoggerService( 1343): Unable to send logs Error code: 262146
,I/wpa_supplicant( 1058): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1058): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  760): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
E/WifiStateMachine(  760): Start Dhcp Watchdog 2
,E/native  (  760): do suspend false
,E/WifiStateMachine(  760): scanCount==0 - aborting
,I/dhcpcd  ( 3332): version 5.5.6 starting
,E/dhcpcd  ( 3332): get_duid: Read-only file system
,I/dhcpcd  ( 3332): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3332): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3332): wlan0: leased 192.168.1.114 for 86400 seconds
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
,D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  760): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  760): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  760): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1577): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1577): CM callback handler got msg 524295
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 09:47:55 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452246475858], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452246475845]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Validated
D/ConnectivityService(  760): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1577): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1196): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2732): type=WIFI subType= reason=null isConnected=true
,D/Tethering(  760): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2732): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2732): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1577): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1577): onCreate
,E/GpsLocationProvider(  760): No APN found to select.
,D/SystemUpdateService( 1577): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1577): active receiver: enabled
,I/SystemUpdateService( 1577): showing system update notification
,E/GpsLocationProvider(  760): No APN found to select.
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1577): retry (wakeup: false) in 3599970 ms
,I/ActivityManager(  760): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3390 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1577): onDestroy
,I/GAv4    ( 3390): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3390):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3390):   adb logcat -s GAv4
,W/GAv4    ( 3390): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3390): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3390): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3390): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3390): Time to load native libraries: 2 ms (timestamps 5478-5480)
I/LibraryLoader( 3390): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3390): Binding Chromium to main looper Looper (main, tid 1) {1dbad3dd}
,I/LibraryLoader( 3390): Expected native library version number "",actual native library version number ""
I/chromium( 3390): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3390): Initializing chromium process, singleProcess=true
,W/art     ( 3390): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3390): ApplicationContext is null in ApplicationStatus
,W/chromium( 3390): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3390): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3390): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3390): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3390): Requires BLUETOOTH permission
,I/NSApplication( 3390): Starting up...
,I/ActivityManager(  760): Killing 2709:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10003/pid_2709/cgroup.procs: No such file or directory
,V/MusicLeanback( 2732): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1577): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1577): onCreate
,D/SystemUpdateService( 1577): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1577): active receiver: enabled
,I/SystemUpdateService( 1577): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1577): retry (wakeup: false) in 3599968 ms
,I/art     (  760): Explicit concurrent mark sweep GC freed 44160(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 967us total 65.518ms
,D/SystemUpdateService( 1577): onDestroy
,D/ConnectivityService(  760): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3219): BLE is supported
I/jxcore-log( 3219): 
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2732): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2732): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1577): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1577): onCreate
,D/SystemUpdateService( 1577): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1577): active receiver: enabled
,I/SystemUpdateService( 1577): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
E/GpsLocationProvider(  760): No APN found to select.
,V/SystemUpdateService( 1577): retry (wakeup: false) in 3599980 ms
,D/SystemUpdateService( 1577): onDestroy
,W/ProcessCpuTracker(  760): Skipping unknown process pid 3480
,W/ProcessCpuTracker(  760): Skipping unknown process pid 3483
,W/ProcessCpuTracker(  760): Skipping unknown process pid 3484
W/ProcessCpuTracker(  760): Skipping unknown process pid 3487
,D/Finsky  ( 2629): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2629): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1567): Vacuum at: now=1452246489014 tag=VacuumService
,I/PhenotypeConfigurator( 1567): Scheduling Phenotype for one-off execution 7357 seconds from now (1452246489450)
,D/GetConfigurationSnapshotOperation( 1567): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1567): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1567): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1064): run()
I/Keyboard.Facilitator( 1064): flushDynamicLanguageModels()
,I/ConfigService( 1567): onCreate
,I/ConfigService( 1567): onDestroy
,I/ClearcutLoggerApiImpl( 1567): disconnect managed GoogleApiClient
,I/jxcore-log( 3219): Connected to the server!
I/jxcore-log( 3219): 
,I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3219): --- start :testFindPeers.js---
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): testFindPeers created [object Object]
I/jxcore-log( 3219): 
I/jxcore-log( 3219): serverPort is 8876
I/jxcore-log( 3219): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3219): bind: Binding a new listener
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3219): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3219): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): start: OK
I/io.jxcore.node.ConnectionHelper( 3219): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3219): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3219): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): start: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3219): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3219): start: OK
I/jxcore-log( 3219): StartBroadcasting started ok
I/jxcore-log( 3219): 
I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3219): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3219): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3219): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1058): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1058): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/WifiP2pManager( 3219): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): Service request added successfully
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): setState: RESTARTING
,I/wpa_supplicant( 1058): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): P2P device discovery started successfully
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): restart: Restarting...
,D/WifiP2pManager( 3219): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): Service request added successfully
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): Service discovery started successfully
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 3219): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,D/io.jxcore.node.ConnectionHelper( 3219): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
,I/jxcore-log( 3219): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"Thali Test (Galaxy A3)","peerAvailable":true}]
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 3219): 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 3219): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 3219): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] is available
I/jxcore-log( 3219): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"G3s-1","peerAvailable":true}]
I/jxcore-log( 3219): 
I/jxcore-log( 3219): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 3219): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 3219): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3219): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
I/jxcore-log( 3219): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"A3-1","peerAvailable":true}]
I/jxcore-log( 3219): 
I/jxcore-log( 3219): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 3219): 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/io.jxcore.node.ConnectionHelper( 3219): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3219): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
,I/jxcore-log( 3219): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"Thali Test (Galaxy S5)","peerAvailable":true}]
I/jxcore-log( 3219): 
I/jxcore-log( 3219): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 3219): 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): restart: Restarting...
,D/WifiP2pManager( 3219): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): Service request added successfully
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): Service discovery started successfully
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 3219): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3219): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
I/jxcore-log( 3219): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"G4-1","peerAvailable":true}]
I/jxcore-log( 3219): 
I/jxcore-log( 3219): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 3219): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 3219): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 3219): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
I/jxcore-log( 3219): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"Thali Test (Galaxy A5)","peerAvailable":true}]
I/jxcore-log( 3219): 
I/jxcore-log( 3219): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 3219): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 3219): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
,W/io.jxcore.node.ConnectionHelper( 3219): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
,I/io.jxcore.node.ConnectionHelper( 3219): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3219): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
I/jxcore-log( 3219): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"S5-1","peerAvailable":true}]
I/jxcore-log( 3219): 
I/jxcore-log( 3219): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 3219): 
D/WifiP2pManager( 3219): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): Service request added successfully
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): Service discovery started successfully
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 3219): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3219): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
,I/jxcore-log( 3219): timeout now
I/jxcore-log( 3219): 
I/jxcore-log( 3219): weAreDoneNow
I/jxcore-log( 3219): 
I/jxcore-log( 3219): done, now sending data to server
I/jxcore-log( 3219): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): setState: RESTARTING
,I/wpa_supplicant( 1058): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): Start timer timeout, starting now...
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): restart: Restarting...
,D/WifiP2pManager( 3219): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): Service request added successfully
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): Service discovery started successfully
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1058): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1058): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 3219): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3219): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3219): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 3219): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 G3-1] is available
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3219): teardown
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): testFindPeers stopped
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3219): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 1058): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3219): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3219): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3219): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): setState: NOT_STARTED
I/jxcore-log( 3219): StopBroadcasting went ok
I/jxcore-log( 3219): 
,I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3219): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3219): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3219): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3219): --- start :testSendData.js---
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":15}bt-address length : 14
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): daya100000
I/jxcore-log( 3219): 
I/jxcore-log( 3219): check server
I/jxcore-log( 3219): 
I/jxcore-log( 3219): serverPort is 32965
I/jxcore-log( 3219): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3219): bind: Binding a new listener
D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3219): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3219): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): start: OK
I/io.jxcore.node.ConnectionHelper( 3219): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3219): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3219): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): start: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3219): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): start: Starting P2P device discovery...
,I/wpa_supplicant( 1058): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3219): start: OK
I/jxcore-log( 3219): StartBroadcasting started ok
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): [ { address: 'F8:95:C7:87:85:54', tryCount: 0 },
I/jxcore-log( 3219):   { address: 'F4:F1:E1:5C:3B:E2', tryCount: 0 },
I/jxcore-log( 3219):   { address: '58:3F:54:73:64:C0', tryCount: 0 },
I/jxcore-log( 3219):   { address: '90:E7:C4:F6:69:77', tryCount: 0 },
I/jxcore-log( 3219):   { address: '00:F4:6F:30:E0:6C', tryCount: 0 },
I/jxcore-log( 3219):   { address: '7C:F9:0E:37:96:AB', tryCount: 0 },
I/jxcore-log( 3219):   { address: '7C:F9:0E:51:18:22', tryCount: 0 },
I/jxcore-log( 3219):   { address: '44:80:EB:7B:5A:05', tryCount: 0 },
I/jxcore-log( 3219):   { address: '7C:F9:0E:34:8A:A0', tryCount: 0 },
I/jxcore-log( 3219):   { address: '08:EC:A9:50:76:27', tryCount: 0 },
I/jxcore-log( 3219):   { address: 'E0:DB:10:14:E2:C0', tryCount: 0 },
I/jxcore-log( 3219):   { address: 'B0:C5:59:3F:75:69', tryCount: 0 },
I/jxcore-log( 3219):   { address: 'F8:95:C7:87:3C:51', tryCount: 0 },
I/jxcore-log( 3219):   { address: '08:EC:A9:50:75:41', tryCount: 0 } ]
I/jxcore-log( 3219): 
I/jxcore-log( 3219): startWithNextDevice
I/jxcore-log( 3219): 
I/jxcore-log( 3219): do fake peer & start
I/jxcore-log( 3219): 
I/jxcore-log( 3219): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:55:31.736Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:55:31.737Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:55:31.737Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: [F8:95:C7:87:85:54 G3s-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3219): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/jxcore-log( 3219): 2016-01-08T09:55:31.743Z SendDataTCPServer.js: TCP/IP server is bound to port: 32965
I/jxcore-log( 3219): 
,I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3219): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3219): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): setState: RESTARTING
,I/wpa_supplicant( 1058): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3219): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 303)
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2081): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1058): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3219): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): Service request added successfully
,W/bt-btif ( 2081): info:x10
,D/        ( 2081): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 2081): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2081): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=0
W/bt-btif ( 2081): bta_dm_check_av:0
,W/bt-btif ( 2081): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2081): process_service_search_attr_rsp
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): Service discovery started successfully
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2081): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2081): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2081): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2081): Entering PendingCommandState State
,W/BluetoothEventManager( 2689): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2689): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 2081): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2081): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2081): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,W/BluetoothEventManager( 2689): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2689): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 2081): StableState(): Entering Off State
,W/bt-btif ( 2081): new conn_srvc id:26, app_id:1
W/bt-btif ( 2081): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2081): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onSocketConnected: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 303)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 66 bytes successfully written (thread ID: 304)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (*handshake* thread ID: 304)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread (thread ID: 303)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3219): Entering thread (ID: 304)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 64 bytes successfully (thread ID: 304)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [F8:95:C7:87:85:54 G3s-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onHandshakeSucceeded: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3219): Exiting thread (ID: 304)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [F8:95:C7:87:85:54 G3s-1]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection to peer [F8:95:C7:87:85:54 G3s-1]
,D/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
,W/io.jxcore.node.ConnectionHelper( 3219): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 G3s-1] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:85:54 G3s-1], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3219): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3219): Entering thread (ID: 305)
,D/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 35271
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3219): onListeningForIncomingConnections: Outgoing connection is using port 35271 (peer ID: F8:95:C7:87:85:54)
I/jxcore-log( 3219): 2016-01-08T09:55:35.021Z SendDataConnector.js: CLIENT connected to 35271, error: null
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:55:35.022Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3219): 
,I/io.jxcore.node.OutgoingSocketThread( 3219): Incoming data from address: /127.0.0.1, port: 35271
D/io.jxcore.node.OutgoingSocketThread( 3219): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3219): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3219): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3219): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread (ID: 305)
,D/io.jxcore.node.StreamCopyingThread( 3219): Entering thread (ID: 306, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3219): Entering thread (ID: 307, name: Receiver)
,I/jxcore-log( 3219): 2016-01-08T09:55:35.081Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3219): 
,D/        ( 2081): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:41220
,I/jxcore-log( 3219): 2016-01-08T09:55:36.338Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:36.530Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3219): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): Start timer timeout, starting now...
,D/        ( 2081): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:20430
,I/jxcore-log( 3219): 2016-01-08T09:55:36.777Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:37.256Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:37.583Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3219): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/btif_config_util( 2081): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3219): 2016-01-08T09:55:38.042Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:38.151Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:38.256Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:38.373Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:38.534Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:55:38.535Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3219): 
I/jxcore-log( 3219): oneRoundDownNow
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:38.544Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:55:38.545Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3219): 
,D/io.jxcore.node.ConnectionHelper( 3219): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:85:54
I/io.jxcore.node.OutgoingSocketThread( 3219): close
D/io.jxcore.node.OutgoingSocketThread( 3219): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3219): doStop: Thread ID: 307
D/io.jxcore.node.OutgoingSocketThread( 3219): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3219): doStop: Thread ID: 306
D/io.jxcore.node.OutgoingSocketThread( 3219): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3219): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3219): Either failed to read from the output stream or write to the input stream (thread ID: 306, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 G3s-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3219): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3219): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3219): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3219): Either failed to read from the output stream or write to the input stream (thread ID: 307, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3219): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 G3s-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3219): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:85:54
,E/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3219): Exiting thread (ID: 307, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3219): Exiting thread (ID: 306, name: Sender)
,I/jxcore-log( 3219): 2016-01-08T09:55:38.596Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3219): 
I/jxcore-log( 3219): ---- round done--------
I/jxcore-log( 3219): 
I/jxcore-log( 3219): startWithNextDevice
I/jxcore-log( 3219): 
I/jxcore-log( 3219): do fake peer & start
I/jxcore-log( 3219): 
I/jxcore-log( 3219): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:55:38.597Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:55:38.597Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:55:38.597Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3219): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 309)
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2081): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2081): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,W/bt-btif ( 2081): info:x10
,D/        ( 2081): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2081): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2081): info:x10
,D/        ( 2081): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2081): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2081): process_service_search_attr_rsp
,E/bt-btif ( 2081): DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2081): invalid rfc slot id: 7
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 309)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Maximum number of allowed retries (0) reached, giving up... (thread ID: 309)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread (thread ID: 309)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown (thread ID: 309)
,I/jxcore-log( 3219): 2016-01-08T09:55:43.069Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:55:43.070Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:43.075Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: P2P: Reject scan trigger since one is already pending
,I/BluetoothBondStateMachine( 2081): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
E/bt-btif ( 2081): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2081): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2081): Entering PendingCommandState State
,W/BluetoothEventManager( 2689): CachedBluetoothDevice for device 90:E7:C4:F6:69:77 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2689): Got bonding state changed for 90:E7:C4:F6:69:77, but we have no record of that device.
,I/BluetoothBondStateMachine( 2081): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
,D/BluetoothAdapterProperties( 2081): Failed to remove device: 90:E7:C4:F6:69:77
,I/BluetoothBondStateMachine( 2081): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2081): StableState(): Entering Off State
,W/BluetoothEventManager( 2689): CachedBluetoothDevice for device 90:E7:C4:F6:69:77 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2689): Got bonding state changed for 90:E7:C4:F6:69:77, but we have no record of that device.
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection initialized (thread ID: 311)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
W/bt-btif ( 2081): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2081): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2081): bta_dm_pm_ssr:2, lat:1200
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3219): Entering thread (ID: 311)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesRead: Read 70 bytes successfully (thread ID: 311)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Got valid identity from [90:E7:C4:F6:69:77 HTC One M8s]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesWritten: 66 bytes successfully written (thread ID: 311)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): removeThreadFromList: Removing thread with ID 311
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Handshake thread disposed (thread ID: 311)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionConnected: [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3219): Exiting thread (ID: 311)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [90:E7:C4:F6:69:77 HTC One M8s]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming connection to peer [90:E7:C4:F6:69:77 HTC One M8s]
D/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3219): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC One M8s] is available
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming socket thread, for peer [90:E7:C4:F6:69:77 HTC One M8s], created successfully
D/io.jxcore.node.ConnectionHelper( 3219): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3219): Entering thread (ID: 312)
,I/jxcore-log( 3219): 2016-01-08T09:55:45.125Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3219): 
,I/io.jxcore.node.IncomingSocketThread( 3219): Local host address: localhost/127.0.0.1, port: 32965
D/io.jxcore.node.IncomingSocketThread( 3219): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3219): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3219): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3219): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3219): Exiting thread (ID: 312)
,D/io.jxcore.node.StreamCopyingThread( 3219): Entering thread (ID: 313, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3219): Entering thread (ID: 314, name: Receiver)
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): restart: Restarting...
,D/WifiP2pManager( 3219): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): Service request added successfully
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 2081): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=1
W/bt-btif ( 2081): bta_dm_check_av:0
,W/bt-btif ( 2081): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): Service discovery started successfully
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3219): 2016-01-08T09:55:46.359Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:46.795Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:46.804Z SendDataTCPServer.js: TCP/IP server has received 2970 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:46.815Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:46.823Z SendDataTCPServer.js: TCP/IP server has received 4950 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:46.833Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:46.909Z SendDataTCPServer.js: TCP/IP server has received 6930 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:46.919Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:46.928Z SendDataTCPServer.js: TCP/IP server has received 8910 bytes of data
I/jxcore-log( 3219): 
,E/bt-btm  ( 2081): tBTM_SEC_DEV:0xa405124c rs_disc_pending=0
E/bt-btm  ( 2081): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2081): bta_dm_check_av:0
,W/bt-btif ( 2081): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 2081): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3219): 2016-01-08T09:55:47.205Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.222Z SendDataTCPServer.js: TCP/IP server has received 10890 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.299Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.397Z SendDataTCPServer.js: TCP/IP server has received 12870 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.406Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.420Z SendDataTCPServer.js: TCP/IP server has received 14850 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.430Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.503Z SendDataTCPServer.js: TCP/IP server has received 16830 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.512Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.516Z SendDataTCPServer.js: TCP/IP server has received 18810 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.526Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.587Z SendDataTCPServer.js: TCP/IP server has received 20790 bytes of data
I/jxcore-log( 3219): 
,D/btif_config_util( 2081): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3219): 2016-01-08T09:55:47.682Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.723Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.728Z SendDataTCPServer.js: TCP/IP server has received 24750 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.790Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.800Z SendDataTCPServer.js: TCP/IP server has received 26730 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.816Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.823Z SendDataTCPServer.js: TCP/IP server has received 28710 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.884Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.894Z SendDataTCPServer.js: TCP/IP server has received 30690 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.910Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.941Z SendDataTCPServer.js: TCP/IP server has received 32670 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:47.991Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.022Z SendDataTCPServer.js: TCP/IP server has received 34650 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.049Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.091Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:55:48.093Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.254Z SendDataTCPServer.js: TCP/IP server has received 36630 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.399Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.406Z SendDataTCPServer.js: TCP/IP server has received 38610 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.415Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.431Z SendDataTCPServer.js: TCP/IP server has received 40590 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.441Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.493Z SendDataTCPServer.js: TCP/IP server has received 42570 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.499Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.505Z SendDataTCPServer.js: TCP/IP server has received 44550 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.557Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.572Z SendDataTCPServer.js: TCP/IP server has received 46530 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.583Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.590Z SendDataTCPServer.js: TCP/IP server has received 48510 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.596Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.720Z SendDataTCPServer.js: TCP/IP server has received 50490 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.733Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.761Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.773Z SendDataTCPServer.js: TCP/IP server has received 54450 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:48.925Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:49.239Z SendDataTCPServer.js: TCP/IP server has received 56430 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:49.246Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:49.327Z SendDataTCPServer.js: TCP/IP server has received 58410 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:49.506Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:49.932Z SendDataTCPServer.js: TCP/IP server has received 60390 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:50.005Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:50.089Z SendDataTCPServer.js: TCP/IP server has received 62370 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:50.116Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3219): 
,E/bt-btm  ( 2081): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2081): onReceive
,I/jxcore-log( 3219): 2016-01-08T09:55:50.187Z SendDataTCPServer.js: TCP/IP server has received 64350 bytes of data
I/jxcore-log( 3219): 
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@300e42d9:true
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: G3s-1
,I/jxcore-log( 3219): 2016-01-08T09:55:50.235Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:50.241Z SendDataTCPServer.js: TCP/IP server has received 66330 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:50.247Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:50.253Z SendDataTCPServer.js: TCP/IP server has received 68310 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:50.260Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:50.266Z SendDataTCPServer.js: TCP/IP server has received 70290 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:50.394Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:50.486Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:50.724Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:50.731Z SendDataTCPServer.js: TCP/IP server has received 74250 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:50.740Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:50.747Z SendDataTCPServer.js: TCP/IP server has received 76230 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:50.756Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:50.763Z SendDataTCPServer.js: TCP/IP server has received 78210 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:50.824Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:50.836Z SendDataTCPServer.js: TCP/IP server has received 80190 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:50.849Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:50.976Z SendDataTCPServer.js: TCP/IP server has received 82170 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:50.988Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:51.003Z SendDataTCPServer.js: TCP/IP server has received 84150 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:51.073Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:51.248Z SendDataTCPServer.js: TCP/IP server has received 86130 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:51.255Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:51.301Z SendDataTCPServer.js: TCP/IP server has received 88110 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:51.313Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:51.324Z SendDataTCPServer.js: TCP/IP server has received 90090 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:51.389Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:51.494Z SendDataTCPServer.js: TCP/IP server has received 92070 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:51.501Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:51.553Z SendDataTCPServer.js: TCP/IP server has received 94050 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:51.586Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:51.800Z SendDataTCPServer.js: TCP/IP server has received 96030 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:51.812Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:51.819Z SendDataTCPServer.js: TCP/IP server has received 98010 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:51.825Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:55:51.832Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3219): 
,D/io.jxcore.node.ConnectionHelper( 3219): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3219): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
,I/jxcore-log( 3219): 2016-01-08T09:55:53.104Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:55:53.105Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:55:53.105Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:55:53.106Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3219): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 315)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3219): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2081): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2081): info:x10
,D/        ( 2081): remote version info [f4:f1:e1:5c:3b:e2]: 6, f, 410d
,E/BluetoothRemoteDevices( 2081): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2081): process_service_search_attr_rsp
,E/bt-btif ( 2081): DISCOVERY_COMP_EVT slot id:9, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2081): invalid rfc slot id: 9
,W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2081): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2081): process_service_search_attr_rsp
,E/bt-btif ( 2081): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2081): invalid rfc slot id: 10
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 315)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Maximum number of allowed retries (0) reached, giving up... (thread ID: 315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread (thread ID: 315)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/jxcore-log( 3219): 2016-01-08T09:55:54.813Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:55:54.814Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:55:54.815Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown (thread ID: 315)
,D/btif_config_util( 2081): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2081): dm_pm_timer expires
W/bt-btif ( 2081): dm_pm_timer expires 0
W/bt-btif ( 2081): proc dm_pm_timer expires
,E/bt-btm  ( 2081): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2081): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3219): 2016-01-08T09:55:59.816Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:55:59.817Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
,D/io.jxcore.node.ConnectionHelper( 3219): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3219): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 3219): 2016-01-08T09:56:04.823Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:56:04.823Z SendDataConnector.js: Connect (retry count 2) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:56:04.824Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:56:04.824Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3219): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 317)
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2081): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2081): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 2081): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2081): invalid rfc slot id: 11
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 317)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Maximum number of allowed retries (0) reached, giving up... (thread ID: 317)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread (thread ID: 317)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/jxcore-log( 3219): 2016-01-08T09:56:09.994Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:56:09.994Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:56:09.994Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown (thread ID: 317)
,I/jxcore-log( 3219): 2016-01-08T09:56:14.995Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:56:14.996Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): setState: RESTARTING
,I/wpa_supplicant( 1058): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 0 device(s) discovered
,D/io.jxcore.node.ConnectionHelper( 3219): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3219): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
,I/jxcore-log( 3219): 2016-01-08T09:56:20.004Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:56:20.006Z SendDataConnector.js: Connect (retry count 3) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:56:20.006Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:56:20.007Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3219): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 319)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3219): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2081): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): Start timer timeout, starting now...
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,W/bt-btif ( 2081): info:x10
,D/        ( 2081): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2081): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2081): process_service_search_attr_rsp
,E/bt-btif ( 2081): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2081): invalid rfc slot id: 12
,W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2081): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2081): process_service_search_attr_rsp
,E/bt-btif ( 2081): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2081): invalid rfc slot id: 13
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 319)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Maximum number of allowed retries (0) reached, giving up... (thread ID: 319)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread (thread ID: 319)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
I/jxcore-log( 3219): 2016-01-08T09:56:21.531Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:56:21.532Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:56:21.532Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown (thread ID: 319)
,E/bt-btm  ( 2081): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
E/bt-btm  ( 2081): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2081): bta_dm_check_av:0
,W/bt-btif ( 2081): invalid rfc slot id: 5
,W/bt-btif ( 2081): btif_dm_cback : unhandled event (14)
,W/io.jxcore.node.StreamCopyingThread( 3219): Either failed to read from the output stream or write to the input stream (thread ID: 314, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3219): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC One M8s] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 312
D/io.jxcore.node.IncomingSocketThread( 3219): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3219): doStop: Thread ID: 314
D/io.jxcore.node.IncomingSocketThread( 3219): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3219): doStop: Thread ID: 313
D/io.jxcore.node.IncomingSocketThread( 3219): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3219): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3219): Either failed to read from the output stream or write to the input stream (thread ID: 313, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3219): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC One M8s] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3219): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3219): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3219): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3219): Exiting thread (ID: 313, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3219): Exiting thread (ID: 314, name: Receiver)
,I/jxcore-log( 3219): 2016-01-08T09:56:22.441Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3219): 
,D/BluetoothMapService( 2081): onReceive
,I/BTConnectionReceiver( 1343): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1343): Bluetooth Device Name: HTC One M8s
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2081): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2081): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2081): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): restart: Restarting...
,D/WifiP2pManager( 3219): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): Service request added successfully
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): Service discovery started successfully
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3219): 2016-01-08T09:56:26.534Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:56:26.535Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
,D/io.jxcore.node.ConnectionHelper( 3219): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3219): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
,I/jxcore-log( 3219): 2016-01-08T09:56:31.543Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:56:31.544Z SendDataConnector.js: Connect (retry count 4) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:56:31.544Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:56:31.545Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3219): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 321)
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2081): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionTimeout: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
I/jxcore-log( 3219): 2016-01-08T09:56:46.568Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] timed out
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:56:46.569Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] timed out
I/jxcore-log( 3219): 
I/jxcore-log( 3219): oneRoundDownNow
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:56:46.574Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3219): 
D/io.jxcore.node.ConnectionHelper( 3219): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3219): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 3219): 2016-01-08T09:56:46.577Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): ---- round done--------
I/jxcore-log( 3219): 
I/jxcore-log( 3219): ---- gotta redo : F4:F1:E1:5C:3B:E2, try count now: 1
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): startWithNextDevice
I/jxcore-log( 3219): 
I/jxcore-log( 3219): do fake peer & start
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:56:46.595Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:56:46.596Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:56:46.596Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3219): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 323)
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2081): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): restart: Restarting...
,D/WifiP2pManager( 3219): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): Service request added successfully
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): Service discovery started successfully
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionTimeout: [58:3F:54:73:64:C0 G3-1]
,I/jxcore-log( 3219): 2016-01-08T09:57:01.614Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [58:3F:54:73:64:C0 G3-1] timed out
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:57:01.615Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [58:3F:54:73:64:C0 G3-1] timed out
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:57:01.620Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-sdp  ( 2081): SDP - Rcvd conn cnf with error: 0x8  CID 0x4a
E/bt-btif ( 2081): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2081): invalid rfc slot id: 14
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown (thread ID: 321)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 321)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Maximum number of allowed retries (0) reached, giving up... (thread ID: 321)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread (thread ID: 321)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,I/jxcore-log( 3219): 2016-01-08T09:57:06.621Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:57:06.621Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
,I/ActivityManager(  760): Killing 2568:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2568/cgroup.procs: No such file or directory
,D/io.jxcore.node.ConnectionHelper( 3219): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
E/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3219): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:3F:54:73:64:C0), either no such connection or failed to close the connection
I/jxcore-log( 3219): 2016-01-08T09:57:11.626Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:57:11.626Z SendDataConnector.js: Connect (retry count 1) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:57:11.627Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:57:11.627Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3219): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 325)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3219): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2081): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3219): timeout now
I/jxcore-log( 3219): 
I/jxcore-log( 3219): weAreDoneNow, resultArray.length: 1
I/jxcore-log( 3219): 
I/jxcore-log( 3219): sendReportNow
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): done, now sending data to server
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:57:11.805Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3219): 
D/io.jxcore.node.ConnectionHelper( 3219): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
E/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3219): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:3F:54:73:64:C0), either no such connection or failed to close the connection
I/jxcore-log( 3219): 2016-01-08T09:57:11.806Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
,W/bt-sdp  ( 2081): SDP - Rcvd conn cnf with error: 0x1f  CID 0x4b
E/bt-btif ( 2081): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2081): invalid rfc slot id: 15
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 323)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Maximum number of allowed retries (0) reached, giving up... (thread ID: 323)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread (thread ID: 323)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown (thread ID: 323)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [58:3F:54:73:64:C0 G3-1]
I/jxcore-log( 3219): 2016-01-08T09:57:17.167Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [58:3F:54:73:64:C0 G3-1] failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:57:17.168Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [58:3F:54:73:64:C0 G3-1] failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:57:17.169Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): setState: RESTARTING
,I/wpa_supplicant( 1058): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1058): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 0 device(s) discovered
,I/jxcore-log( 3219): 2016-01-08T09:57:22.178Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:57:22.184Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
,W/bt-sdp  ( 2081): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2081): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2081): invalid rfc slot id: 16
,W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2081): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): Start timer timeout, starting now...
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3219): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
E/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3219): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:3F:54:73:64:C0), either no such connection or failed to close the connection
,I/jxcore-log( 3219): 2016-01-08T09:57:27.193Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:57:27.194Z SendDataConnector.js: Connect (retry count 2) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:57:27.195Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:57:27.195Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3219): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 327)
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2081): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2081): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2081): DISCOVERY_COMP_EVT slot id:17, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2081): invalid rfc slot id: 17
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown (thread ID: 325)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 325)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Maximum number of allowed retries (0) reached, giving up... (thread ID: 325)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread (thread ID: 325)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [58:3F:54:73:64:C0 G3-1]
,I/jxcore-log( 3219): 2016-01-08T09:57:27.443Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [58:3F:54:73:64:C0 G3-1] failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:57:27.444Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [58:3F:54:73:64:C0 G3-1] failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:57:27.445Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): restart: Restarting...
,D/WifiP2pManager( 3219): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): Service request added successfully
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1058): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant( 1058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1058): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3219): Service discovery started successfully
,I/jxcore-log( 3219): teardown
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): testSendData stopped
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3219): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3219): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3219): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3219): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3219): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3219): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3219): setState: NOT_STARTED
,I/jxcore-log( 3219): StopBroadcasting went ok
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:57:31.717Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3219): 
I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3219): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3219): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3219): ****TEST TOOK:  ms ****
I/jxcore-log( 3219): 
I/jxcore-log( 3219): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2016-01-08T09:57:32.450Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2016-01-08T09:57:32.451Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
,W/bt-sdp  ( 2081): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2081): DISCOVERY_COMP_EVT slot id:18, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2081): invalid rfc slot id: 18
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 327)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Maximum number of allowed retries (0) reached, giving up... (thread ID: 327)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread (thread ID: 327)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown (thread ID: 327)
D/AndroidRuntime( 3219): Shutting down VM
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): Uncaught exception: Attempt to invoke virtual method 'int org.thaliproject.p2p.btconnectorlib.ConnectionManager.getInsecureRfcommSocketPort()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): java.lang.NullPointerException: Attempt to invoke virtual method 'int org.thaliproject.p2p.btconnectorlib.ConnectionManager.getInsecureRfcommSocketPort()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): 	at io.jxcore.node.ConnectionHelper.onConnectionFailed(ConnectionHelper.java:449)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): 	at org.thaliproject.p2p.btconnectorlib.ConnectionManager$3.run(ConnectionManager.java:396)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): 	at android.os.Handler.handleCallback(Handler.java:739)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): 	at android.os.Looper.loop(Looper.java:135)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): 	at java.lang.reflect.Method.invoke(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,D/AndroidRuntime( 3611): 
D/AndroidRuntime( 3611): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3611): CheckJNI is OFF
,D/AndroidRuntime( 3611): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  760): Killing 3219:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  760): WIN DEATH: Window{1bf8a11b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  760): Client connection lost with reason: 4
,W/PackageSettings(  760): Skipping PackageSetting{3e1130c7 com.example.hello/10278} due to missing metadata
,E/libprocessgroup(  760): failed to kill 1 processes for processgroup 3219
I/ActivityManager(  760):   Force finishing activity ActivityRecord{28c6c204 u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  760): Spurious death for ProcessRecord{1b46c49e 3219:com.test.thalitest/u0a270}, curProc for 3219: null
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  760):   Force finishing activity ActivityRecord{28c6c204 u0 com.test.thalitest/.MainActivity t214 f}
,W/ActivityManager(  760): Duplicate finish request for ActivityRecord{28c6c204 u0 com.test.thalitest/.MainActivity t214 f}
,I/art     ( 1343): Explicit concurrent mark sweep GC freed 15914(866KB) AllocSpace objects, 2(32KB) LOS objects, 25% free, 19MB/25MB, paused 878us total 46.211ms
,I/Keyboard.Facilitator( 1064): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1567): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1064): run()
,I/art     ( 1218): Explicit concurrent mark sweep GC freed 3984(295KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 639us total 25.072ms
I/Decoder ( 1064): createOrResetDecoder
,I/Adreno-EGL(  947): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  947): Initialized EGL, version 1.4
,D/OpenGLRenderer(  947): Enabling debug mode 0
,I/ConfigService( 1567): onCreate
,I/art     (  760): Explicit concurrent mark sweep GC freed 44385(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 6.288ms total 86.764ms
,I/art     (  760): WaitForGcToComplete blocked for 75.096ms for cause Explicit
,D/VoicemailCleanupService( 2871): Cleaning up data for package: com.test.thalitest
,I/art     ( 1577): Explicit concurrent mark sweep GC freed 21190(1195KB) AllocSpace objects, 5(80KB) LOS objects, 25% free, 22MB/30MB, paused 453us total 154.209ms
,I/UpdateIcingCorporaServi( 1343): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1218): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@8bc3260 new=com.google.android.velvet.VelvetApplication@8bc3260
,W/InputMethodManagerService(  760): Got RemoteException sending setActive(false) notification to pid 3219 uid 10270
,I/Keyboard.Facilitator( 1064): onFinishInput()
,I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3652 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  760): removeObsoleteFile: deleting file=214_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1064): run()
,W/ResourcesManager( 1218): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Launcher( 1218): Deferring update until onResume
,I/art     (  760): Explicit concurrent mark sweep GC freed 8699(457KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.136ms total 145.737ms
,W/ResourcesManager( 1218): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1064): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1064): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1064): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1064): run()
I/StatsUtilsManager( 1064): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1064): shouldRecordStats() = Too Soon
I/UpdateIcingCorporaServi( 1343): UpdateCorporaTask done [took 154 ms] updated apps [took 153 ms] 
,W/ContextImpl( 3652): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1577): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1577): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1577): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1577): Module APK com.google.android.play.games already loaded
,I/Launcher( 1218): Deferring update until onResume
,I/Keyboard.Facilitator( 1064): onFinishInput()
,D/ChimeraCfgMgr( 1577): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1577): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1567): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1567): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1577): Removing dialog suppression flag for package com.test.thalitest
,W/IInputConnectionWrapper( 1218): showStatusIcon on inactive InputConnection
,D/gH_CompatibleDatabase( 1577): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1577): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1577): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1577): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1577): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1577): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1577): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1577): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1577): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1577): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1577): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1577): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1577): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  760): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3684 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,D/AndroidRuntime( 3611): Shutting down VM
,I/GMPM-SVC( 1577): App measurement is starting up, version: 8489
,I/GMPM-SVC( 1577): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1577): Using Auth Proxy for data requests.
,W/BaseAppContext( 1577): Using Auth Proxy for data requests.
,I/Icing   ( 1577): doRemovePackageData com.test.thalitest
,I/ActivityManager(  760): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3709 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  760): Killing 1968:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10031/pid_1968/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 2008:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10002/pid_2008/cgroup.procs: No such file or directory
,D/ExternalStorage( 3709): After updating volumes, found 1 active roots
,W/ResourcesManager( 3139): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3139): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3684): Update found 7 roots in 265ms
,D/Documents( 3684): Update found 7 roots in 138ms

```
