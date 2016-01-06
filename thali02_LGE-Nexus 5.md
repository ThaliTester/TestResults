#### Test 552541413820a6d_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1583): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1583): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3186): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3186):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3186):   adb logcat -s GAv4
W/GAv4    ( 3186): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3186): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3186): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3186): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2617): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3186): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3186): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  753): Killing 2587:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3186): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3186): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3186): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  753): failed to open /acct/uid_10069/pid_2587/cgroup.procs: No such file or directory
V/GLSActivity( 1606): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1583): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1583): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1583): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1583): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3266): 
D/AndroidRuntime( 3266): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3266): CheckJNI is OFF
D/AndroidRuntime( 3266): Calling main entry com.android.commands.am.Am
I/ActivityManager(  753): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  753): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3287 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3266): Shutting down VM
V/ActivityManager(  753): Display changed displayId=0
I/ActivityManager(  753): Killing 2543:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
W/libprocessgroup(  753): failed to open /acct/uid_10045/pid_2543/cgroup.procs: No such file or directory
I/WebViewFactory( 3287): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3287): Time to load native libraries: 1 ms (timestamps 9576-9577)
I/LibraryLoader( 3287): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3287): Binding Chromium to main looper Looper (main, tid 1) {20e1eb85}
I/LibraryLoader( 3287): Expected native library version number "",actual native library version number ""
I/chromium( 3287): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3287): Initializing chromium process, singleProcess=true
W/art     ( 3287): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3287): ApplicationContext is null in ApplicationStatus
,W/chromium( 3287): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3287): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3287): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3287): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  753): Message: 20
,D/BluetoothManagerService(  753): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a8ffa12:true
,W/art     ( 3287): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3287): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3287): CordovaWebView is running on device made by: LGE
,W/art     ( 3287): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3287): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3287): Render dirty regions requested: true
,D/Atlas   ( 3287): Validating map...
,W/chromium( 3287): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3287): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3287): Enabling debug mode 0
,W/IInputConnectionWrapper( 3287): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1071): onFinishInput()
,I/ActivityManager(  753): Displayed com.test.thalitest/.MainActivity: +562ms (total +57s32ms)
,W/BindingManager( 3287): Cannot call determinedVisibility() - never saw a connection for the pid: 3287
,D/JsMessageQueue( 3287): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3287): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1356460288
D/JX-Cordova( 3287): jxcore cordova android initializing
,W/jxcore-log( 3287): Initializing JXcore engine
W/jxcore-log( 3287): JXcore engine is ready
,W/jxcore-log( 3287): Starting JXcore engine
,W/.test.thalitest( 3287): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8373]" dev="sockfs" ino=8373 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3287): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3287): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6664]" dev="sockfs" ino=6664 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3287): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19309]" dev="sockfs" ino=19309 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3287): Platform android
W/jxcore-log( 3287): 
W/jxcore-log( 3287): Process ARCH arm
W/jxcore-log( 3287): 
,I/jxcore-log( 3287): JXcore Cordova bridge is ready!
I/jxcore-log( 3287): 
W/jxcore-log( 3287): JXcore engine is started
I/Choreographer( 3287): Skipped 113 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3287): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3287): Toggling radios to true
I/jxcore-log( 3287): 
,D/BluetoothAdapter( 3287): enable(): BT is already enabled..!
,D/WifiService(  753): New client listening to asynchronous messages
D/WifiService(  753): setWifiEnabled: true pid=3287, uid=10270
E/WifiService(  753): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3287): Radios toggled
I/jxcore-log( 3287): 
,D/BluetoothManagerService(  753): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3287): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3287): 
I/jxcore-log( 3287): Perf Test app loaded loaded
I/jxcore-log( 3287): 
I/Choreographer( 3287): Skipped 55 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 3287): check test folder
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): found test : ./testFindPeers.js
I/jxcore-log( 3287): 
I/wpa_supplicant( 1081): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  753): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  753): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  753): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,I/jxcore-log( 3287): found test : ./testSendData.js
I/jxcore-log( 3287): 
,V/NativeCrypto( 1606): Read error: ssl=0x9bbf6e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1606): SSL shutdown failed: ssl=0x9bbf6e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  753): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  753): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  753): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  753): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  753): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  753): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  753): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  753): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  753): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  753): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine(  753): Start Disconnecting Watchdog 1
,E/native  (  753): do suspend true
,I/wpa_supplicant( 1081): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  753): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
D/Nat464Xlat(  753): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  753): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  753): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  753): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  753): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1583): CM callback handler got msg 524292
D/ConnectivityService(  753): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  753): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  753): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/chromium( 3287): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/TelephonyNetworkFactory( 1193): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  753): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiNetworkAgent(  753): NetworkAgent: NetworkAgent channel lost
,W/NetworkUtils( 1324): OkHttp exception
,W/EventLoggerService( 1324): Unable to send logs Error code: 262146
,V/GLSActivity( 1606): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1606): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant( 1081): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1081): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1081): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1081): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  753): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  753): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  753): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  753): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  753): Start Dhcp Watchdog 2
,E/native  (  753): do suspend false
,E/WifiStateMachine(  753): scanCount==0 - aborting
,I/dhcpcd  ( 3397): version 5.5.6 starting
,E/dhcpcd  ( 3397): get_duid: Read-only file system
,I/dhcpcd  ( 3397): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3397): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3397): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  753): do suspend true
,D/ConnectivityService(  753): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  753): Adding iface wlan0 to network 101
,E/WifiStateMachine(  753): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  753): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  753): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  753): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  753): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  753): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  753): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  753): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  753): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  753): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  753): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  753): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  753): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  753): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  753):    accepting network in place of null
,D/CSLegacyTypeTracker(  753): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  753): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  753): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  753): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/ConnectivityService(  753): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  753): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityManager.CallbackHandler( 1583): CM callback handler got msg 524290
,D/Tethering(  753): MasterInitialState.processMessage what=3
,D/Tethering(  753): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2730): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 2730): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2730): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  753): No APN found to select.
,I/SystemUpdateService( 1583): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1583): onCreate
,D/SystemUpdateService( 1583): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1583): active receiver: enabled
,E/GpsLocationProvider(  753): No APN found to select.
,I/SystemUpdateService( 1583): showing system update notification
,I/ValidateNoPeople(  753): skipping global notification
,V/SystemUpdateService( 1583): retry (wakeup: false) in 3599987 ms
,I/ActivityManager(  753): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3458 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1583): onDestroy
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  753): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 06 Jan 2016 19:51:51 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452109911513], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452109911494]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  753): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  753): Validated
D/ConnectivityService(  753): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  753): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  753): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  753): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
D/ConnectivityService(  753): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1583): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1193): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/GAv4    ( 3458): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3458):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3458):   adb logcat -s GAv4
,W/GAv4    ( 3458): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3458): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3458): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/Nat464Xlat(  753): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  753): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1583): CM callback handler got msg 524295
,I/WebViewFactory( 3458): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3458): Time to load native libraries: 2 ms (timestamps 6652-6654)
I/LibraryLoader( 3458): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3458): Binding Chromium to main looper Looper (main, tid 1) {b2759af}
,I/LibraryLoader( 3458): Expected native library version number "",actual native library version number ""
,I/chromium( 3458): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3458): Initializing chromium process, singleProcess=true
W/art     ( 3458): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3458): ApplicationContext is null in ApplicationStatus
,W/chromium( 3458): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3458): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3458): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3458): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3458): Requires BLUETOOTH permission
,I/NSApplication( 3458): Starting up...
,I/ActivityManager(  753): Killing 2705:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  753): failed to open /acct/uid_10003/pid_2705/cgroup.procs: No such file or directory
,V/MusicLeanback( 2730): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1583): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1583): onCreate
D/SystemUpdateService( 1583): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1583): active receiver: enabled
,I/SystemUpdateService( 1583): showing system update notification
,I/ValidateNoPeople(  753): skipping global notification
,V/SystemUpdateService( 1583): retry (wakeup: false) in 3599981 ms
,D/SystemUpdateService( 1583): onDestroy
,D/ConnectivityService(  753): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3287): BLE supported!!
I/jxcore-log( 3287): 
,D/ConnectivityService(  753): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  753): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2730): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2730): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1583): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1583): onCreate
,D/SystemUpdateService( 1583): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1583): active receiver: enabled
,I/SystemUpdateService( 1583): showing system update notification
,I/ValidateNoPeople(  753): skipping global notification
,V/SystemUpdateService( 1583): retry (wakeup: false) in 3599923 ms
,D/SystemUpdateService( 1583): onDestroy
,I/art     (  753): Explicit concurrent mark sweep GC freed 46062(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.144ms total 88.867ms
,E/GpsLocationProvider(  753): No APN found to select.
,D/Finsky  ( 2617): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2617): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1606): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1606): Vacuum at: now=1452109923114 tag=VacuumService
,I/PhenotypeConfigurator( 1606): Scheduling Phenotype for one-off execution 8504 seconds from now (1452109923369)
,D/GetConfigurationSnapshotOperation( 1606): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1606): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1606): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1606): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1606): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1071): run()
I/Keyboard.Facilitator( 1071): flushDynamicLanguageModels()
,I/ConfigService( 1606): onCreate
,I/ConfigService( 1606): onDestroy
,I/ClearcutLoggerApiImpl( 1606): disconnect managed GoogleApiClient
,I/jxcore-log( 3287): Connected to the server!
I/jxcore-log( 3287): 
,I/chromium( 3287): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3287): --- start :testFindPeers.js---
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): testFindPeers created [object Object]
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): serverPort is 8876
I/jxcore-log( 3287): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  753): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT4461
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3287): bind: Binding a new listener
D/BluetoothManagerService(  753): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3287): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  753): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3287): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4461","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  753): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3287): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): start: OK
I/io.jxcore.node.ConnectionHelper( 3287): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  753): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT4461
,D/BluetoothManagerService(  753): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3287): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4461","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3287): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4461","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3287): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4461","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3287): start: OK
I/jxcore-log( 3287): StartBroadcasting started ok
I/jxcore-log( 3287): 
I/chromium( 3287): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3287): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3287): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3287): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1081): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pManager( 3287): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): Service request added successfully
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): Service discovery started successfully
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): setState: RESTARTING
,I/wpa_supplicant( 1081): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1081): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1081): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1081): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): P2P device discovery started successfully
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1081): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3287): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): Service request added successfully
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): Service discovery started successfully
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1593","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1593]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1593]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1593]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1593], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1593]
,I/io.jxcore.node.ConnectionHelper( 3287): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1593], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 3287): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1593] is available
I/jxcore-log( 3287): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT1593","peerAvailable":true}]
I/jxcore-log( 3287): 
I/jxcore-log( 3287): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 3287): 
I/jxcore-log( 3287): weAreDoneNow
I/jxcore-log( 3287): 
I/jxcore-log( 3287): done, now sending data to server
I/jxcore-log( 3287): 
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1081): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1593], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1593]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1593], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1593]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3287): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): Service request added successfully
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1593], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1593]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1081): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1593], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1593]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1593], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1593]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): Service discovery started successfully
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1081): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1593], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1593]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1593], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1593]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): setState: RESTARTING
,I/wpa_supplicant( 1081): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1081): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1081): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1081): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1081): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1081): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1081): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): Start timer timeout, starting now...
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1081): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): restart: Restarting...
,D/WifiP2pManager( 3287): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): Service request added successfully
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): Service discovery started successfully
,I/wpa_supplicant( 1081): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1081): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1155","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1155]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1155]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1155]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT1155], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT1155]
I/io.jxcore.node.ConnectionHelper( 3287): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT1155], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 3287): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1155] is available
,I/jxcore-log( 3287): teardown
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): testFindPeers stopped
I/jxcore-log( 3287): 
I/io.jxcore.node.ConnectionHelper( 3287): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3287): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 1081): P2P-FIND-STOPPED 
I/wpa_supplicant( 1081): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1081): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3287): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3287): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3287): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): setState: NOT_STARTED
I/jxcore-log( 3287): StopBroadcasting went ok
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): --- start :testSendData.js---
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":15}bt-address length : 0
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): daya100000
I/jxcore-log( 3287): 
I/jxcore-log( 3287): check server
I/jxcore-log( 3287): 
I/jxcore-log( 3287): serverPort is 60862
I/jxcore-log( 3287): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  753): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT4461
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3287): bind: Binding a new listener
,D/BluetoothManagerService(  753): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3287): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  753): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3287): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4461","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  753): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3287): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): start: OK
I/io.jxcore.node.ConnectionHelper( 3287): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  753): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT4461
,D/BluetoothManagerService(  753): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3287): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4461","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3287): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4461","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3287): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4461","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3287): start: OK
I/jxcore-log( 3287): StartBroadcasting started ok
I/jxcore-log( 3287): 
I/jxcore-log( 3287): null
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:00:58.335Z SendDataTCPServer.js: TCP/IP server is bound to port: 60862
I/jxcore-log( 3287): 
I/chromium( 3287): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3287): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3287): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3287): onDiscoveryManagerStateChanged: NOT_STARTED
I/chromium( 3287): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3287): onConnectionManagerStateChanged: RUNNING
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3287): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): setState: RESTARTING
,I/wpa_supplicant( 1081): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3287): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): Start timer timeout, starting now...
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/ActivityManager(  753): Killing 2687:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  753): Client connection lost with reason: 4
,W/libprocessgroup(  753): failed to open /acct/uid_1000/pid_2687/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiP2pManager( 3287): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): Service request added successfully
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2082): info:x10
,D/        ( 2082): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2082): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2082): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
E/bt-btif ( 2082): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2082): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2082): Entering PendingCommandState State
,I/ActivityManager(  753): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=3628 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): Service discovery started successfully
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/BluetoothManagerService(  753): Message: 20
D/BluetoothManagerService(  753): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16167b6:true
,I/ActivityManager(  753): Killing 2561:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  753): failed to open /acct/uid_10070/pid_2561/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 2082): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
,D/BluetoothAdapterProperties( 2082): Failed to remove device: 90:E7:C4:F6:69:77
,I/BluetoothBondStateMachine( 2082): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2082): StableState(): Entering Off State
,W/bt-btif ( 2082): new conn_srvc id:26, app_id:255
W/bt-btif ( 2082): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2082): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): Incoming connection initialized (thread ID: 315)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3287): Entering thread (ID: 315)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): onBytesRead: Read 81 bytes successfully (thread ID: 315)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): Got valid identity from [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): onBytesWritten: 77 bytes successfully written (thread ID: 315)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): removeThreadFromList: Removing thread with ID 315
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): Handshake thread disposed (thread ID: 315)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): onIncomingConnectionConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723]
I/io.jxcore.node.ConnectionHelper( 3287): onConnected: Incoming connection to peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723]
D/io.jxcore.node.ConnectionHelper( 3287): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3287): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723] is available
,I/jxcore-log( 3287): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC-HTC One M8s_PT9723","peerAvailable":true}]
I/jxcore-log( 3287): 
I/jxcore-log( 3287): Found peer : HTC-HTC One M8s_PT9723, Available: true
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): startWithNextDevice
I/jxcore-log( 3287): 
I/jxcore-log( 3287): device[1]: 90:E7:C4:F6:69:77
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:01:07.607Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:01:07.607Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:01:07.607Z SendDataConnector.js: do connect now
I/jxcore-log( 3287): 
I/io.jxcore.node.ConnectionHelper( 3287): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3287): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): connect: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): connect: Trying to start connecting to HTC One M8s in address 90:E7:C4:F6:69:77
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): onConnecting: HTC One M8s 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): connect: Started connecting to HTC One M8s in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 3287): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
,I/io.jxcore.node.ConnectionHelper( 3287): onConnected: Incoming socket thread, for peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723], created successfully
D/io.jxcore.node.ConnectionHelper( 3287): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3287): Exiting thread (ID: 315)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 316)
W/BluetoothAdapter( 3287): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2082): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/io.jxcore.node.IncomingSocketThread( 3287): Entering thread (ID: 317)
,I/io.jxcore.node.IncomingSocketThread( 3287): Local host address: localhost/127.0.0.1, port: 60862
D/io.jxcore.node.IncomingSocketThread( 3287): Setting local streams and starting stream copying threads...
,I/jxcore-log( 3287): 2016-01-06T20:01:07.621Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3287): 
,I/io.jxcore.node.StreamCopyingThread( 3287): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3287): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3287): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3287): Exiting thread (ID: 317)
,D/io.jxcore.node.StreamCopyingThread( 3287): Entering thread (ID: 319, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3287): Entering thread (ID: 318, name: Sender)
,W/bt-sdp  ( 2082): process_service_search_attr_rsp
,W/bt-btif ( 2082): new conn_srvc id:26, app_id:1
W/bt-btif ( 2082): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2082): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2082): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): onSocketConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 316)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): onBytesWritten: 77 bytes successfully written (thread ID: 320)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): Outgoing connection initialized (*handshake* thread ID: 320)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): Exiting thread (thread ID: 316)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3287): Entering thread (ID: 320)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): onBytesRead: Read 81 bytes successfully (thread ID: 320)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): Handshake succeeded with [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): onHandshakeSucceeded: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3287): Exiting thread (ID: 320)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723]
,I/io.jxcore.node.ConnectionHelper( 3287): onConnected: Outgoing connection to peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723]
D/io.jxcore.node.ConnectionHelper( 3287): hasConnection: We have an incoming connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 3287): onConnected: Already connected with peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3287): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3287): onConnected: Outgoing socket thread, for peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3287): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 3287): Entering thread (ID: 321)
,D/io.jxcore.node.OutgoingSocketThread( 3287): Server socket local port: 58297
,I/io.jxcore.node.OutgoingSocketThread( 3287): Now accepting connections...
,W/bt-btif ( 2082): info:x10
,D/        ( 2082): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 2082): aclStateChangeCallback: Device is NULL
,I/io.jxcore.node.ConnectionHelper( 3287): onListeningForIncomingConnections: Outgoing connection is using port 58297 (peer ID: 90:E7:C4:F6:69:77)
,I/jxcore-log( 3287): 2016-01-06T20:01:08.234Z SendDataConnector.js: CLIENT connected to 58297, error: null
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:01:08.235Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3287): 
,I/io.jxcore.node.OutgoingSocketThread( 3287): Incoming data from address: /127.0.0.1, port: 58297
D/io.jxcore.node.OutgoingSocketThread( 3287): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3287): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3287): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3287): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3287): Exiting thread (ID: 321)
,I/jxcore-log( 3287): 2016-01-06T20:01:08.268Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3287): 
,D/io.jxcore.node.StreamCopyingThread( 3287): Entering thread (ID: 322, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3287): Entering thread (ID: 323, name: Receiver)
,E/bt-btm  ( 2082): tBTM_SEC_DEV:0xa41e2ebc rs_disc_pending=1
,W/bt-btif ( 2082): bta_dm_check_av:0
W/bt-btif ( 2082): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2082): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 2082): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2082): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2082): Entering PendingCommandState State
,I/jxcore-log( 3287): 2016-01-06T20:01:08.778Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:08.814Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:08.851Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:08.855Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:08.864Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:08.869Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:08.876Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:08.910Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:08.912Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3287): 
,D/        ( 2082): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3287): 2016-01-06T20:01:08.968Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:08.979Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:08.985Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:09.050Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:09.081Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:09.132Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3287): 
,D/        ( 2082): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 3287): 2016-01-06T20:01:09.181Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3287): 
,I/BluetoothBondStateMachine( 2082): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2082): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 2082): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2082): StableState(): Entering Off State
,I/jxcore-log( 3287): 2016-01-06T20:01:09.234Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:09.236Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3287): 
,W/bt-btif ( 2082): new conn_srvc id:26, app_id:255
W/bt-btif ( 2082): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2082): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): Incoming connection initialized (thread ID: 324)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3287): Entering thread (ID: 324)
,I/jxcore-log( 3287): 2016-01-06T20:01:09.308Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3287): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): onBytesRead: Read 82 bytes successfully (thread ID: 324)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): Got valid identity from [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): onBytesWritten: 77 bytes successfully written (thread ID: 324)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): removeThreadFromList: Removing thread with ID 324
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): Handshake thread disposed (thread ID: 324)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3287): Exiting thread (ID: 324)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301]
I/io.jxcore.node.ConnectionHelper( 3287): onConnected: Incoming connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301]
D/io.jxcore.node.ConnectionHelper( 3287): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3287): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301] is available
I/jxcore-log( 3287): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT3301","peerAvailable":true}]
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): Found peer : samsung-SM-N910C_PT3301, Available: true
I/jxcore-log( 3287): 
I/io.jxcore.node.ConnectionHelper( 3287): onConnected: Incoming socket thread, for peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301], created successfully
D/io.jxcore.node.ConnectionHelper( 3287): onConnected: The total number of connections is now 3
,D/io.jxcore.node.IncomingSocketThread( 3287): Entering thread (ID: 325)
,I/jxcore-log( 3287): 2016-01-06T20:01:09.333Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3287): 
,I/io.jxcore.node.IncomingSocketThread( 3287): Local host address: localhost/127.0.0.1, port: 60862
D/io.jxcore.node.IncomingSocketThread( 3287): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3287): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3287): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3287): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3287): Exiting thread (ID: 325)
,D/io.jxcore.node.StreamCopyingThread( 3287): Entering thread (ID: 327, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3287): Entering thread (ID: 326, name: Sender)
,I/jxcore-log( 3287): 2016-01-06T20:01:09.340Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:09.343Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:09.524Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:09.711Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:09.847Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3287): 
,D/        ( 2082): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3287): 2016-01-06T20:01:09.862Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:09.869Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:09.938Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3287): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3301","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301]
,I/jxcore-log( 3287): 2016-01-06T20:01:09.952Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3287): 
I/io.jxcore.node.ConnectionHelper( 3287): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 3287): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301] already in the list, will not add again
,I/jxcore-log( 3287): 2016-01-06T20:01:10.095Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:10.295Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:10.452Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:10.540Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:10.563Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3287): 
,W/bt-btif ( 2082): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 3287): Either failed to read from the output stream or write to the input stream (thread ID: 319, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3287): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3287): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 317
D/io.jxcore.node.IncomingSocketThread( 3287): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3287): doStop: Thread ID: 319
D/io.jxcore.node.IncomingSocketThread( 3287): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3287): doStop: Thread ID: 318
D/io.jxcore.node.IncomingSocketThread( 3287): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3287): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3287): Either failed to read from the output stream or write to the input stream (thread ID: 318, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3287): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3287): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3287): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3287): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3287): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3287): Exiting thread (ID: 318, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3287): Exiting thread (ID: 319, name: Receiver)
,I/jxcore-log( 3287): 2016-01-06T20:01:10.814Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:10.835Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:10.837Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:10.903Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:10.906Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:10.940Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:11.066Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:11.073Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:11.081Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:11.127Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:11.163Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:11.276Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:11.282Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:11.344Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:11.374Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:11.381Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:11.483Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:11.497Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:11.551Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:11.666Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:11.928Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:11.961Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:11.979Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:11.999Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:12.006Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:12.024Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:12.061Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:12.083Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:12.112Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:12.161Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:12.341Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:12.554Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:12.564Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3287): 
,D/btif_config_util( 2082): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3287): 2016-01-06T20:01:12.590Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:12.611Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:12.644Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3287): 
,W/bt-btif ( 2082): invalid rfc slot id: 6
,W/io.jxcore.node.StreamCopyingThread( 3287): Either failed to read from the output stream or write to the input stream (thread ID: 327, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3287): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3287): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 325
D/io.jxcore.node.IncomingSocketThread( 3287): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3287): doStop: Thread ID: 327
D/io.jxcore.node.IncomingSocketThread( 3287): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3287): doStop: Thread ID: 326
D/io.jxcore.node.IncomingSocketThread( 3287): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3287): closeLocalSocketAndStreams: Closing the local input stream...
,D/io.jxcore.node.IncomingSocketThread( 3287): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3287): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3287): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3287): Exiting thread (ID: 327, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3287): Either failed to read from the output stream or write to the input stream (thread ID: 326, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3287): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3287): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3287): Exiting thread (ID: 326, name: Sender)
,I/jxcore-log( 3287): 2016-01-06T20:01:12.802Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3287): 
,W/bt-rfcomm( 2082): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 2082): RFCOMM_DisconnectInd LCID:0x44
,I/jxcore-log( 3287): 2016-01-06T20:01:14.422Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:01:14.423Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3287): 
I/jxcore-log( 3287): oneRoundDownNow
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:01:14.427Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:01:14.427Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3287): 
,D/io.jxcore.node.ConnectionHelper( 3287): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 90:E7:C4:F6:69:77
I/io.jxcore.node.IncomingSocketThread( 3287): close
D/io.jxcore.node.IncomingSocketThread( 3287): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 3287): doStop: Thread ID: 323
D/io.jxcore.node.IncomingSocketThread( 3287): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3287): doStop: Thread ID: 322
D/io.jxcore.node.IncomingSocketThread( 3287): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3287): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3287): Either failed to read from the output stream or write to the input stream (thread ID: 322, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3287): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 3287): onDisconnected: Outgoing connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3287): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3287): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3287): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3287): Either failed to read from the output stream or write to the input stream (thread ID: 323, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3287): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3287): onDisconnected: Outgoing connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3287): disconnectOutgoingConnection: Successfully disconnected (peer ID: 90:E7:C4:F6:69:77
,E/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
,D/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3287): Exiting thread (ID: 322, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3287): Exiting thread (ID: 323, name: Receiver)
,I/jxcore-log( 3287): 2016-01-06T20:01:14.483Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3287): 
I/jxcore-log( 3287): ---- round done--------
I/jxcore-log( 3287): 
I/jxcore-log( 3287): startWithNextDevice
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): device[2]: E0:DB:10:14:E2:C0
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:01:14.489Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:14.496Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:01:14.497Z SendDataConnector.js: do connect now
I/jxcore-log( 3287): 
,I/io.jxcore.node.ConnectionHelper( 3287): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3287): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): connect: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): onConnecting: Note4-1 E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3287): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 328)
W/BluetoothAdapter( 3287): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2082): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2082): process_service_search_attr_rsp
,E/bt-btm  ( 2082): tBTM_SEC_DEV:0xa41e3084 rs_disc_pending=0
W/bt-btif ( 2082): bta_dm_check_av:0
,W/bt-btif ( 2082): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2082): new conn_srvc id:26, app_id:1
W/bt-btif ( 2082): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2082): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): onSocketConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 328)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): onBytesWritten: 77 bytes successfully written (thread ID: 329)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): Outgoing connection initialized (*handshake* thread ID: 329)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): Exiting thread (thread ID: 328)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3287): Entering thread (ID: 329)
,E/bt-btm  ( 2082): tBTM_SEC_DEV:0xa41e3084 rs_disc_pending=1
W/bt-btif ( 2082): bta_dm_check_av:0
,W/bt-btif ( 2082): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2082): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): onBytesRead: Read 82 bytes successfully (thread ID: 329)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): onHandshakeSucceeded: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3287): Exiting thread (ID: 329)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301]
I/io.jxcore.node.ConnectionHelper( 3287): onConnected: Outgoing connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301]
D/io.jxcore.node.ConnectionHelper( 3287): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 3287): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3287): onConnected: Outgoing socket thread, for peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3287): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3287): Entering thread (ID: 330)
,D/io.jxcore.node.OutgoingSocketThread( 3287): Server socket local port: 38323
I/io.jxcore.node.OutgoingSocketThread( 3287): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3287): onListeningForIncomingConnections: Outgoing connection is using port 38323 (peer ID: E0:DB:10:14:E2:C0)
I/jxcore-log( 3287): 2016-01-06T20:01:17.742Z SendDataConnector.js: CLIENT connected to 38323, error: null
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:01:17.743Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3287): 
,I/io.jxcore.node.OutgoingSocketThread( 3287): Incoming data from address: /127.0.0.1, port: 38323
D/io.jxcore.node.OutgoingSocketThread( 3287): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3287): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3287): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3287): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3287): Exiting thread (ID: 330)
,I/jxcore-log( 3287): 2016-01-06T20:01:17.772Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3287): 
,D/io.jxcore.node.StreamCopyingThread( 3287): Entering thread (ID: 331, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3287): Entering thread (ID: 332, name: Receiver)
,I/jxcore-log( 3287): 2016-01-06T20:01:18.908Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:19.263Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3287): 
,E/bt-btm  ( 2082): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2082): onReceive
,D/BluetoothManagerService(  753): Message: 20
D/BluetoothManagerService(  753): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a5f1c24:true
,I/BTConnectionReceiver( 1324): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1324): Bluetooth Device Name: HTC One M8s
,I/jxcore-log( 3287): 2016-01-06T20:01:19.535Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:19.656Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:19.791Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:19.795Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:20.047Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:20.325Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:20.583Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:20.693Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:01:20.694Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3287): 
I/jxcore-log( 3287): oneRoundDownNow
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:01:20.696Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:01:20.696Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3287): 
,D/io.jxcore.node.ConnectionHelper( 3287): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
,I/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 3287): close
,D/io.jxcore.node.OutgoingSocketThread( 3287): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3287): doStop: Thread ID: 332
D/io.jxcore.node.OutgoingSocketThread( 3287): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3287): doStop: Thread ID: 331
D/io.jxcore.node.OutgoingSocketThread( 3287): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3287): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3287): Either failed to read from the output stream or write to the input stream (thread ID: 331, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3287): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3287): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3287): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3287): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3287): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3287): Either failed to read from the output stream or write to the input stream (thread ID: 332, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3287): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3287): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3287): disconnectOutgoingConnection: Successfully disconnected (peer ID: E0:DB:10:14:E2:C0
,E/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3287): Exiting thread (ID: 331, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3287): Exiting thread (ID: 332, name: Receiver)
,I/jxcore-log( 3287): 2016-01-06T20:01:20.745Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3287): 
I/jxcore-log( 3287): ---- round done--------
I/jxcore-log( 3287): 
I/jxcore-log( 3287): startWithNextDevice
I/jxcore-log( 3287): 
,E/bt-btm  ( 2082): tBTM_SEC_DEV:0xa41e3084 rs_disc_pending=0
W/bt-btif ( 2082): bta_dm_check_av:0
,W/bt-btif ( 2082): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2082): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,W/bt-btif ( 2082): dm_pm_timer expires
W/bt-btif ( 2082): dm_pm_timer expires 0
W/bt-btif ( 2082): proc dm_pm_timer expires
,E/bt-btm  ( 2082): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2082): onReceive
,I/BTConnectionReceiver( 1324): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1324): Bluetooth Device Name: Note4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): setState: RESTARTING
,I/wpa_supplicant( 1081): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1081): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): Start timer timeout, starting now...
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): restart: Restarting...
,D/WifiP2pManager( 3287): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): Service request added successfully
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT9723","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723]
,I/io.jxcore.node.ConnectionHelper( 3287): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723], Bluetooth address: 90:E7:C4:F6:69:77, device name: , device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 3287): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT9723] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4782","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782]
I/io.jxcore.node.ConnectionHelper( 3287): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
,D/io.jxcore.node.ConnectionHelper( 3287): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782] is available
,I/jxcore-log( 3287): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT4782","peerAvailable":true}]
I/jxcore-log( 3287): 
I/jxcore-log( 3287): Found peer : samsung-SM-G900F_PT4782, Available: true
I/jxcore-log( 3287): 
I/jxcore-log( 3287): startWithNextDevice
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): device[3]: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:44.761Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:44.766Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:44.766Z SendDataConnector.js: do connect now
I/jxcore-log( 3287): 
,I/io.jxcore.node.ConnectionHelper( 3287): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3287): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): connect: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3287): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 333)
W/BluetoothAdapter( 3287): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2082): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2082): info:x10
,D/        ( 2082): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2082): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2082): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2082): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 2082): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2082): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2082): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2082): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2082): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2082): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2082): StableState(): Entering Off State
,W/bt-btif ( 2082): new conn_srvc id:26, app_id:1
W/bt-btif ( 2082): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2082): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): onSocketConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 333)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): onBytesWritten: 77 bytes successfully written (thread ID: 334)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): Outgoing connection initialized (*handshake* thread ID: 334)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): Exiting thread (thread ID: 333)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3287): Entering thread (ID: 334)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): onBytesRead: Read 82 bytes successfully (thread ID: 334)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): Handshake succeeded with [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): onHandshakeSucceeded: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782]
I/io.jxcore.node.ConnectionHelper( 3287): onConnected: Outgoing connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782]
D/io.jxcore.node.ConnectionHelper( 3287): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 3287): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3287): onConnected: Outgoing socket thread, for peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3287): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3287): Exiting thread (ID: 334)
,D/io.jxcore.node.OutgoingSocketThread( 3287): Entering thread (ID: 335)
D/io.jxcore.node.OutgoingSocketThread( 3287): Server socket local port: 52791
I/io.jxcore.node.OutgoingSocketThread( 3287): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3287): onListeningForIncomingConnections: Outgoing connection is using port 52791 (peer ID: 7C:F9:0E:34:8A:A0)
I/jxcore-log( 3287): 2016-01-06T20:01:47.906Z SendDataConnector.js: CLIENT connected to 52791, error: null
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:01:47.907Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3287): 
,I/io.jxcore.node.OutgoingSocketThread( 3287): Incoming data from address: /127.0.0.1, port: 52791
D/io.jxcore.node.OutgoingSocketThread( 3287): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3287): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3287): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3287): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3287): Exiting thread (ID: 335)
,D/io.jxcore.node.StreamCopyingThread( 3287): Entering thread (ID: 337, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3287): Entering thread (ID: 336, name: Sender)
,I/jxcore-log( 3287): 2016-01-06T20:01:47.944Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:48.500Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:48.521Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:48.567Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:48.593Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:48.641Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:48.720Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:48.727Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:48.771Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:01:48.774Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:01:48.812Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:01:48.812Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3287): 
I/jxcore-log( 3287): oneRoundDownNow
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:01:48.814Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:01:48.815Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3287): 
D/io.jxcore.node.ConnectionHelper( 3287): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:34:8A:A0
I/io.jxcore.node.OutgoingSocketThread( 3287): close
D/io.jxcore.node.OutgoingSocketThread( 3287): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3287): doStop: Thread ID: 337
D/io.jxcore.node.OutgoingSocketThread( 3287): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3287): doStop: Thread ID: 336
D/io.jxcore.node.OutgoingSocketThread( 3287): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3287): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3287): Either failed to read from the output stream or write to the input stream (thread ID: 336, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3287): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3287): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3287): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3287): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3287): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3287): Either failed to read from the output stream or write to the input stream (thread ID: 337, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3287): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3287): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3287): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3287): Exiting thread (ID: 336, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3287): Exiting thread (ID: 337, name: Receiver)
,I/jxcore-log( 3287): 2016-01-06T20:01:48.856Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3287): 
I/jxcore-log( 3287): ---- round done--------
I/jxcore-log( 3287): 
I/jxcore-log( 3287): startWithNextDevice
I/jxcore-log( 3287): 
,W/bt-btif ( 2082): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,D/btif_config_util( 2082): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2082): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2082): onReceive
,I/BTConnectionReceiver( 1324): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1324): Bluetooth Device Name: S5-1
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): checkListForExpiredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Removed [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301]
,I/io.jxcore.node.ConnectionHelper( 3287): onPeerLost: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301]
D/io.jxcore.node.ConnectionHelper( 3287): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3287): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301] removed
D/io.jxcore.node.ConnectionHelper( 3287): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3301] not available
I/jxcore-log( 3287): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT3301","peerAvailable":false}]
I/jxcore-log( 3287): 
I/jxcore-log( 3287): startWithNextDevice
I/jxcore-log( 3287): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): setState: RESTARTING
,I/wpa_supplicant( 1081): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1081): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): P2P device discovery started successfully
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1081): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): restart: Restarting...
,D/WifiP2pManager( 3287): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): Service request added successfully
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): Service discovery started successfully
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7648","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648]
I/io.jxcore.node.ConnectionHelper( 3287): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3287): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648] is available
I/jxcore-log( 3287): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT7648","peerAvailable":true}]
I/jxcore-log( 3287): 
I/jxcore-log( 3287): Found peer : samsung-SM-A300FU_PT7648, Available: true
I/jxcore-log( 3287): 
I/jxcore-log( 3287): startWithNextDevice
I/jxcore-log( 3287): 
I/jxcore-log( 3287): device[4]: 08:EC:A9:50:75:41
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:02:24.036Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:02:24.037Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:02:24.037Z SendDataConnector.js: do connect now
I/jxcore-log( 3287): 
I/io.jxcore.node.ConnectionHelper( 3287): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3287): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): connect: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3287): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 338)
W/BluetoothAdapter( 3287): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2082): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2082): info:x10
,D/        ( 2082): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2082): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2082): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2082): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 2082): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2082): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2082): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2082): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2082): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2082): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2082): StableState(): Entering Off State
,W/bt-btif ( 2082): new conn_srvc id:26, app_id:1
W/bt-btif ( 2082): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2082): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): onSocketConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 338)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): onBytesWritten: 77 bytes successfully written (thread ID: 339)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): Outgoing connection initialized (*handshake* thread ID: 339)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): Exiting thread (thread ID: 338)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3287): Entering thread (ID: 339)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): onBytesRead: Read 83 bytes successfully (thread ID: 339)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3287): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): onHandshakeSucceeded: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3287): Exiting thread (ID: 339)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648]
I/io.jxcore.node.ConnectionHelper( 3287): onConnected: Outgoing connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648]
D/io.jxcore.node.ConnectionHelper( 3287): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,W/io.jxcore.node.ConnectionHelper( 3287): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3287): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3287): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3287): Entering thread (ID: 340)
D/io.jxcore.node.OutgoingSocketThread( 3287): Server socket local port: 51454
I/io.jxcore.node.OutgoingSocketThread( 3287): Now accepting connections...
,W/bt-btif ( 2082): new conn_srvc id:26, app_id:255
W/bt-btif ( 2082): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2082): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2082): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): Incoming connection initialized (thread ID: 341)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3287): Entering thread (ID: 341)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): onBytesRead: Read 83 bytes successfully (thread ID: 341)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): onBytesWritten: 77 bytes successfully written (thread ID: 341)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): removeThreadFromList: Removing thread with ID 341
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): Handshake thread disposed (thread ID: 341)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3287): Exiting thread (ID: 341)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648]
,I/io.jxcore.node.ConnectionHelper( 3287): onConnected: Incoming connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648]
D/io.jxcore.node.ConnectionHelper( 3287): hasConnection: We have an outgoing connection with peer with ID 08:EC:A9:50:75:41
,W/io.jxcore.node.ConnectionHelper( 3287): onConnected: Already connected with peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3287): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3287): onConnected: Incoming socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648], created successfully
D/io.jxcore.node.ConnectionHelper( 3287): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 3287): Entering thread (ID: 342)
,I/jxcore-log( 3287): 2016-01-06T20:02:25.474Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3287): 
,I/io.jxcore.node.IncomingSocketThread( 3287): Local host address: localhost/127.0.0.1, port: 60862
D/io.jxcore.node.IncomingSocketThread( 3287): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3287): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3287): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3287): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3287): Exiting thread (ID: 342)
,D/io.jxcore.node.StreamCopyingThread( 3287): Entering thread (ID: 343, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3287): Entering thread (ID: 344, name: Receiver)
,I/io.jxcore.node.ConnectionHelper( 3287): onListeningForIncomingConnections: Outgoing connection is using port 51454 (peer ID: 08:EC:A9:50:75:41)
I/jxcore-log( 3287): 2016-01-06T20:02:25.495Z SendDataConnector.js: CLIENT connected to 51454, error: null
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:02:25.495Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3287): 
,I/io.jxcore.node.IncomingSocketThread( 3287): Incoming data from address: /127.0.0.1, port: 51454
D/io.jxcore.node.IncomingSocketThread( 3287): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3287): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3287): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3287): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3287): Exiting thread (ID: 340)
,I/jxcore-log( 3287): 2016-01-06T20:02:25.501Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3287): 
,D/io.jxcore.node.StreamCopyingThread( 3287): Entering thread (ID: 346, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3287): Entering thread (ID: 345, name: Sender)
,D/        ( 2082): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,D/        ( 2082): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11836
,I/jxcore-log( 3287): 2016-01-06T20:02:26.276Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:26.317Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:26.358Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:26.459Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:26.465Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:26.479Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:26.508Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:26.515Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:26.521Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:26.633Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:26.657Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:26.719Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:26.859Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:26.865Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:26.887Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:26.899Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:26.946Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:26.948Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:26.949Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:26.951Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3287): 
I/jxcore-log( 3287): oneRoundDownNow
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:02:26.952Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3287): 
I/jxcore-log( 3287): 2016-01-06T20:02:26.952Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3287): 
D/io.jxcore.node.ConnectionHelper( 3287): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
I/io.jxcore.node.IncomingSocketThread( 3287): close
D/io.jxcore.node.IncomingSocketThread( 3287): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3287): doStop: Thread ID: 346
D/io.jxcore.node.IncomingSocketThread( 3287): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3287): doStop: Thread ID: 345
D/io.jxcore.node.IncomingSocketThread( 3287): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3287): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3287): Either failed to read from the output stream or write to the input stream (thread ID: 345, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3287): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3287): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 3287): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3287): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3287): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3287): Either failed to read from the output stream or write to the input stream (thread ID: 346, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3287): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3287): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3287): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3287): Exiting thread (ID: 345, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3287): Exiting thread (ID: 346, name: Receiver)
,I/jxcore-log( 3287): 2016-01-06T20:02:26.958Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3287): 
I/jxcore-log( 3287): ---- round done--------
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): startWithNextDevice
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:26.961Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:26.965Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:27.000Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:27.006Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3287): 
,W/bt-btif ( 2082): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/jxcore-log( 3287): 2016-01-06T20:02:27.010Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:27.050Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:27.052Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:27.056Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:27.090Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:27.108Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:27.112Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:27.150Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:27.163Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3287): 
,W/bt-btif ( 2082): invalid rfc slot id: 8
,W/io.jxcore.node.StreamCopyingThread( 3287): Either failed to read from the output stream or write to the input stream (thread ID: 344, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3287): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3287): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 342
D/io.jxcore.node.IncomingSocketThread( 3287): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3287): doStop: Thread ID: 344
D/io.jxcore.node.IncomingSocketThread( 3287): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3287): doStop: Thread ID: 343
D/io.jxcore.node.IncomingSocketThread( 3287): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3287): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3287): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3287): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3287): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3287): Exiting thread (ID: 344, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3287): Either failed to read from the output stream or write to the input stream (thread ID: 343, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3287): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3287): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3287): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3287): Exiting thread (ID: 343, name: Sender)
,I/jxcore-log( 3287): 2016-01-06T20:02:27.228Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3287): 
,D/btif_config_util( 2082): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2082): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2082): onReceive
,I/BTConnectionReceiver( 1324): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1324): Bluetooth Device Name: A3-1
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1081): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648]
,D/WifiP2pManager( 3287): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): Service request added successfully
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): Service discovery started successfully
,I/wpa_supplicant( 1081): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1081): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1081): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4782]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7648]
,I/jxcore-log( 3287): timeout now
I/jxcore-log( 3287): 
I/jxcore-log( 3287): weAreDoneNow, resultArray.length: 4
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): sendReportNow
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): done, now sending data to server
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:38.398Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): teardown
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): testSendData stopped
I/jxcore-log( 3287): 
I/io.jxcore.node.ConnectionHelper( 3287): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3287): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3287): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3287): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3287): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3287): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 1081): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1081): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1081): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1081): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1081): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3287): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3287): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3287): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3287): setState: NOT_STARTED
,I/jxcore-log( 3287): StopBroadcasting went ok
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): ****TEST TOOK:  ms ****
I/jxcore-log( 3287): 
I/jxcore-log( 3287): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3287): 
,I/jxcore-log( 3287): 2016-01-06T20:02:58.524Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3287): 
I/chromium( 3287): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3287): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3287): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3287): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3287): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3287): onDiscoveryManagerStateChanged: NOT_STARTED
,D/AndroidRuntime( 3737): 
D/AndroidRuntime( 3737): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3737): CheckJNI is OFF
,D/AndroidRuntime( 3737): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  753): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
,I/ActivityManager(  753): Killing 3287:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  753): WIN DEATH: Window{2ec70bc2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  753): Client connection lost with reason: 4
,I/ActivityManager(  753):   Force finishing activity ActivityRecord{2c16b4ae u0 com.test.thalitest/.MainActivity t214}
,W/PackageSettings(  753): Skipping PackageSetting{13fba7c9 com.example.hello/10278} due to missing metadata
,W/ActivityManager(  753): Spurious death for ProcessRecord{cea238d 3287:com.test.thalitest/u0a270}, curProc for 3287: null
I/ActivityManager(  753): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  753):   Force finishing activity ActivityRecord{2c16b4ae u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  753): Duplicate finish request for ActivityRecord{2c16b4ae u0 com.test.thalitest/.MainActivity t214 f}
,I/art     ( 1324): Explicit concurrent mark sweep GC freed 25367(1241KB) AllocSpace objects, 4(64KB) LOS objects, 25% free, 19MB/25MB, paused 305us total 23.385ms
,I/art     ( 1583): Explicit concurrent mark sweep GC freed 41372(2MB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 22MB/30MB, paused 463us total 39.051ms
,W/GeofencerStateMachine( 1606): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  753): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1242): Explicit concurrent mark sweep GC freed 3960(294KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 458us total 62.700ms
,I/Keyboard.Facilitator( 1071): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1071): run()
,D/VoicemailCleanupService( 2872): Cleaning up data for package: com.test.thalitest
,I/Decoder ( 1071): createOrResetDecoder
,I/UpdateIcingCorporaServi( 1324): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1242): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3d1fdda new=com.google.android.velvet.VelvetApplication@3d1fdda
,I/Adreno-EGL(  947): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  947): Initialized EGL, version 1.4
,D/OpenGLRenderer(  947): Enabling debug mode 0
,I/art     (  753): Explicit concurrent mark sweep GC freed 37540(1928KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.679ms total 91.493ms
,I/art     (  753): WaitForGcToComplete blocked for 55.378ms for cause Explicit
,I/ActivityManager(  753): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3776 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ConfigService( 1606): onCreate
,W/InputMethodManagerService(  753): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@270ef916 (uid=10034 pid=947)
,W/ContextImpl( 3776): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1583): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1583): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1583): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1583): Module APK com.google.android.play.games already loaded
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1071): run()
,D/BackupManagerService(  753): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  753): Receieved: android.intent.action.PACKAGE_REMOVED
,D/ChimeraCfgMgr( 1583): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1583): Module APK com.google.android.play.games already loaded
,D/TaskPersister(  753): removeObsoleteFile: deleting file=214_task.xml
E/NetworkScheduler.SchedulerReceiver( 1606): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1606): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1583): Removing dialog suppression flag for package com.test.thalitest
,D/gH_CompatibleDatabase( 1583): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1583): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1583): 0 metrics were deleted when clearing package com.test.thalitest.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1071): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1071): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1071): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1071): run()
I/StatsUtilsManager( 1071): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1071): shouldRecordStats() = Too Soon
D/gH_CompatibleDatabase( 1583): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/InputMethodManagerService(  753): Got RemoteException sending setActive(false) notification to pid 3287 uid 10270
,D/gH_CompatibleDatabase( 1583): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1583): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1583): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/Keyboard.Facilitator( 1071): onFinishInput()
,I/UpdateIcingCorporaServi( 1324): UpdateCorporaTask done [took 192 ms] updated apps [took 192 ms] 
,D/gH_CompatibleDatabase( 1583): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1583): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1583): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1583): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1583): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1583): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/art     (  753): Explicit concurrent mark sweep GC freed 9622(471KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.427ms total 183.891ms
,I/ActivityManager(  753): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3813 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/Launcher( 1242): Deferring update until onResume
,W/BaseAppContext( 1583): Using Auth Proxy for data requests.
,W/BaseAppContext( 1583): Using Auth Proxy for data requests.
,W/ResourcesManager( 1242): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GMPM-SVC( 1583): App measurement is starting up, version: 8489
I/GMPM-SVC( 1583): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,D/AndroidRuntime( 3737): Shutting down VM
,W/ResourcesManager( 1242): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Icing   ( 1583): doRemovePackageData com.test.thalitest
,I/Launcher( 1242): Deferring update until onResume
,I/ActivityManager(  753): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3837 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  753): Killing 1979:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  753): failed to open /acct/uid_10031/pid_1979/cgroup.procs: No such file or directory
,I/ActivityManager(  753): Killing 3033:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  753): failed to open /acct/uid_10008/pid_3033/cgroup.procs: No such file or directory
,D/ExternalStorage( 3837): After updating volumes, found 1 active roots
,W/ResourcesManager( 3186): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3186): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3813): Update found 7 roots in 281ms
,D/Documents( 3813): Update found 7 roots in 69ms

```
