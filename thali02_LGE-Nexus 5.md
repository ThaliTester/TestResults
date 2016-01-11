#### Test 55613145dd493c6_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3163): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3163):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3163):   adb logcat -s GAv4
W/GAv4    ( 3163): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3163): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3163): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3163): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2608): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3163): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3163): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 3163): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  735): Killing 2572:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/System  ( 3163): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3163): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  735): failed to open /acct/uid_10069/pid_2572/cgroup.procs: No such file or directory
V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1614): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1614): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1614): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1614): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3228): 
D/AndroidRuntime( 3228): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3228): CheckJNI is OFF
D/AndroidRuntime( 3228): Calling main entry com.android.commands.am.Am
I/ActivityManager(  735): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  735): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3249 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3228): Shutting down VM
V/ActivityManager(  735): Display changed displayId=0
I/WebViewFactory( 3249): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3249): Time to load native libraries: 2 ms (timestamps 8620-8622)
I/LibraryLoader( 3249): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3249): Binding Chromium to main looper Looper (main, tid 1) {1296e73f}
I/LibraryLoader( 3249): Expected native library version number "",actual native library version number ""
I/chromium( 3249): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3249): Initializing chromium process, singleProcess=true
W/art     ( 3249): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3249): ApplicationContext is null in ApplicationStatus
W/chromium( 3249): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3249): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3249): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3249): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3464aaa1:true
,W/art     ( 3249): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3249): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3249): CordovaWebView is running on device made by: LGE
,W/art     ( 3249): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3249): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3249): Render dirty regions requested: true
,D/Atlas   ( 3249): Validating map...
,W/chromium( 3249): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  735): Killing 2522:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10045/pid_2522/cgroup.procs: No such file or directory
,I/OpenGLRenderer( 3249): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3249): Enabling debug mode 0
,W/BindingManager( 3249): Cannot call determinedVisibility() - never saw a connection for the pid: 3249
,W/IInputConnectionWrapper( 3249): showStatusIcon on inactive InputConnection
,I/ActivityManager(  735): Displayed com.test.thalitest/.MainActivity: +502ms (total +57s423ms)
,D/JsMessageQueue( 3249): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3249): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342720
D/JX-Cordova( 3249): jxcore cordova android initializing
,W/jxcore-log( 3249): Initializing JXcore engine
W/jxcore-log( 3249): JXcore engine is ready
W/jxcore-log( 3249): Starting JXcore engine
,W/.test.thalitest( 3249): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8371]" dev="sockfs" ino=8371 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3249): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 3249): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9507]" dev="sockfs" ino=9507 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3249): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19423]" dev="sockfs" ino=19423 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3249): Platform android
W/jxcore-log( 3249): 
W/jxcore-log( 3249): Process ARCH arm
W/jxcore-log( 3249): 
,I/jxcore-log( 3249): JXcore Cordova bridge is ready!
I/jxcore-log( 3249): 
,W/jxcore-log( 3249): JXcore engine is started
I/Choreographer( 3249): Skipped 106 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3249): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3249): Toggling radios to true
I/jxcore-log( 3249): 
,D/BluetoothAdapter( 3249): enable(): BT is already enabled..!
,D/WifiService(  735): New client listening to asynchronous messages
,D/WifiService(  735): setWifiEnabled: true pid=3249, uid=10270
E/WifiService(  735): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3249): Radios toggled
I/jxcore-log( 3249): 
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3249): Received device characteristics:
I/jxcore-log( 3249): Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3249): Bluetooth name: Nexus 5
I/jxcore-log( 3249): Device name: LGE-Nexus 5
I/jxcore-log( 3249): 
,I/wpa_supplicant( 1027): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  735): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  735): do suspend true
,I/jxcore-log( 3249): Perf Test app loaded loaded
I/jxcore-log( 3249): 
,I/Choreographer( 3249): Skipped 69 frames!  The application may be doing too much work on its main thread.
D/CommandListener(  181): Clearing all IP addresses on wlan0
,W/NetworkUtils( 1377): OkHttp exception
W/EventLoggerService( 1377): Unable to send logs Error code: 262146
,V/NativeCrypto( 1569): Read error: ssl=0xb3cf7e00: I/O error during system call, Connection timed out
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NativeCrypto( 1569): SSL shutdown failed: ssl=0xb3cf7e00: I/O error during system call, Broken pipe
,I/jxcore-log( 3249): check test folder
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): found test : ./testFindPeers.js
I/jxcore-log( 3249): 
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  735): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
,I/jxcore-log( 3249): found test : ./testSendData.js
I/jxcore-log( 3249): 
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiStateMachine(  735): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1027): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  735): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
D/ConnectivityService(  735): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  735): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  735): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  735): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1614): CM callback handler got msg 524292
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524292
D/TelephonyNetworkFactory( 1252): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiNetworkAgent(  735): NetworkAgent: NetworkAgent channel lost
,I/chromium( 3249): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 1027): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1027): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1027): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1027): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  735): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  735): Start Dhcp Watchdog 2
,E/native  (  735): do suspend false
,E/WifiStateMachine(  735): scanCount==0 - aborting
,I/dhcpcd  ( 3338): version 5.5.6 starting
,E/dhcpcd  ( 3338): get_duid: Read-only file system
,I/dhcpcd  ( 3338): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3338): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3338): wlan0: leased 192.168.1.114 for 86400 seconds,
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2709): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1614): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,E/GpsLocationProvider(  735): No APN found to select.
,D/SystemUpdateService( 1614): onCreate
,D/SystemUpdateService( 1614): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1614): active receiver: enabled
I/iu.Environment( 1614): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,E/GpsLocationProvider(  735): No APN found to select.
,I/SystemUpdateService( 1614): showing system update notification
,I/iu.UploadsManager( 1614): num queued entries: 0
I/iu.UploadsManager( 1614): num updated entries: 0
,I/iu.SyncManager( 1614): NEXT; no task
,I/Babel   ( 1885): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  735): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3383 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1614): retry (wakeup: false) in 3599926 ms
,D/SystemUpdateService( 1614): onDestroy
E/native  (  735): do suspend true
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  735): Adding iface wlan0 to network 101
,E/WifiStateMachine(  735): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  735): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  735): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  735): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  735): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  735): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  735): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  735): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  735): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  735): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::5255:27ff:fef0:fd0b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1614): CM callback handler got msg 524290
,I/GAv4    ( 3383): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3383):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3383):   adb logcat -s GAv4
,W/GAv4    ( 3383): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3383): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3383): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 12:55:53 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452516953033], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452516953017]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Validated
D/ConnectivityService(  735): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1614): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1252): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WebViewFactory( 3383): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3383): Time to load native libraries: 2 ms (timestamps 5751-5753)
I/LibraryLoader( 3383): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3383): Binding Chromium to main looper Looper (main, tid 1) {3143b659}
,I/LibraryLoader( 3383): Expected native library version number "",actual native library version number ""
,I/chromium( 3383): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3383): Initializing chromium process, singleProcess=true
,W/art     ( 3383): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3383): ApplicationContext is null in ApplicationStatus
,W/chromium( 3383): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3383): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3383): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3383): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3383): Requires BLUETOOTH permission
,I/NSApplication( 3383): Starting up...
,I/ActivityManager(  735): Killing 2686:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10003/pid_2686/cgroup.procs: No such file or directory
,V/MusicLeanback( 2709): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1614): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1614): onCreate
,D/SystemUpdateService( 1614): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1614): active receiver: enabled
,I/iu.Environment( 1614): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1614): showing system update notification
,I/iu.UploadsManager( 1614): num queued entries: 0
,I/iu.UploadsManager( 1614): num updated entries: 0
I/iu.SyncManager( 1614): NEXT; no task
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1614): retry (wakeup: false) in 3599971 ms
,D/SystemUpdateService( 1614): onDestroy
,I/Babel   ( 1885): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  735): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3249): BLE is supported
I/jxcore-log( 3249): 
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2709): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2709): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1614): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/art     (  735): Explicit concurrent mark sweep GC freed 43889(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 997us total 103.809ms
,D/SystemUpdateService( 1614): onCreate
,D/SystemUpdateService( 1614): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1614): active receiver: enabled
,I/SystemUpdateService( 1614): showing system update notification
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1614): retry (wakeup: false) in 3599972 ms
,D/SystemUpdateService( 1614): onDestroy
,E/GpsLocationProvider(  735): No APN found to select.
,D/Finsky  ( 2608): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2608): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1569): Vacuum at: now=1452516965050 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1569): disconnect managed GoogleApiClient
,I/jxcore-log( 3249): Connected to the server!
I/jxcore-log( 3249): 
,I/chromium( 3249): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager(  735): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3543 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3543): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3543):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3543):   adb logcat -s GAv4
,W/GAv4    ( 3543): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3543): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3543): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  735): Killing 2667:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  735): Client connection lost with reason: 4
,W/libprocessgroup(  735): failed to open /acct/uid_1000/pid_2667/cgroup.procs: No such file or directory
,I/jxcore-log( 3249): --- start :testFindPeers.js---
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): testFindPeers created [object Object]
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): serverPort is 8876
I/jxcore-log( 3249): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3249): bind: Binding a new listener
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3249): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3249): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3249): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): start: OK
I/io.jxcore.node.ConnectionHelper( 3249): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3249): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3249): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): start: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3249): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3249): start: OK
I/jxcore-log( 3249): StartBroadcasting started ok
I/jxcore-log( 3249): 
I/chromium( 3249): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): Waiting for incoming connections...
,I/io.jxcore.node.ConnectionHelper( 3249): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3249): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/io.jxcore.node.ConnectionHelper( 3249): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/WifiP2pManager( 3249): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): Service request added successfully
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): Service discovery started successfully
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): setState: RESTARTING
,I/wpa_supplicant( 1027): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): Start timer timeout, starting now...
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): restart: Restarting...
,D/WifiP2pManager( 3249): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): Service request added successfully
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 3249): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3249): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
,I/jxcore-log( 3249): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"A3-1","peerAvailable":true}]
I/jxcore-log( 3249): 
I/jxcore-log( 3249): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 3249): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): setState: RESTARTING
,I/wpa_supplicant( 1027): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): Start timer timeout, starting now...
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): restart: Restarting...
,D/WifiP2pManager( 3249): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): Service request added successfully
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): Service discovery started successfully
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 3249): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3249): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
,I/jxcore-log( 3249): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"G4-1","peerAvailable":true}]
I/jxcore-log( 3249): 
I/jxcore-log( 3249): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 3249): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): restart: Restarting...
,D/WifiP2pManager( 3249): Ignored { when=-8ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): Service request added successfully
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): Service discovery started successfully
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 3249): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3249): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,I/jxcore-log( 3249): timeout now
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): weAreDoneNow
I/jxcore-log( 3249): 
I/jxcore-log( 3249): done, now sending data to server
I/jxcore-log( 3249): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 3249): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 3249): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): restart: Restarting...
,D/WifiP2pManager( 3249): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): Service request added successfully
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): Service discovery started successfully
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3249): teardown
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): testFindPeers stopped
I/jxcore-log( 3249): 
I/io.jxcore.node.ConnectionHelper( 3249): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3249): release: No more listeners, de-initializing...,
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 1027): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3249): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3249): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3249): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): setState: NOT_STARTED
,I/jxcore-log( 3249): StopBroadcasting went ok
I/jxcore-log( 3249): 
I/jxcore-log( 3249): --- start :testSendData.js---
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":14}bt-address length : 13
I/jxcore-log( 3249): 
I/jxcore-log( 3249): daya100000
I/jxcore-log( 3249): 
I/jxcore-log( 3249): check server
I/jxcore-log( 3249): 
I/jxcore-log( 3249): serverPort is 48827
I/jxcore-log( 3249): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3249): bind: Binding a new listener
D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3249): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3249): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3249): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): start: OK
I/io.jxcore.node.ConnectionHelper( 3249): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3249): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3249): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): start: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3249): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3249): start: OK
I/jxcore-log( 3249): StartBroadcasting started ok
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): [ { address: '08:EC:A9:50:75:41', tryCount: 0 },
I/jxcore-log( 3249):   { address: '00:F4:6F:30:E0:6C', tryCount: 0 },
I/jxcore-log( 3249):   { address: '90:E7:C4:F6:69:77', tryCount: 0 },
I/jxcore-log( 3249):   { address: '44:80:EB:7B:5A:05', tryCount: 0 },
I/jxcore-log( 3249):   { address: 'F8:95:C7:87:85:54', tryCount: 0 },
I/jxcore-log( 3249):   { address: 'B0:C5:59:3F:75:69', tryCount: 0 },
I/jxcore-log( 3249):   { address: 'F8:95:C7:87:3C:51', tryCount: 0 },
I/jxcore-log( 3249):   { address: '7C:F9:0E:34:8A:A0', tryCount: 0 },
I/jxcore-log( 3249):   { address: '58:3F:54:73:64:C0', tryCount: 0 },
I/jxcore-log( 3249):   { address: '7C:F9:0E:37:96:AB', tryCount: 0 },
I/jxcore-log( 3249):   { address: '7C:F9:0E:51:18:22', tryCount: 0 },
I/jxcore-log( 3249):   { address: '08:EC:A9:50:76:27', tryCount: 0 },
I/jxcore-log( 3249):   { address: 'E0:DB:10:14:E2:C0', tryCount: 0 } ]
I/jxcore-log( 3249): 
I/jxcore-log( 3249): startWithNextDevice
I/jxcore-log( 3249): 
I/jxcore-log( 3249): do fake peer & start
I/jxcore-log( 3249): 
I/jxcore-log( 3249): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:03:27.140Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:03:27.140Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:03:27.140Z SendDataConnector.js: do connect now
I/jxcore-log( 3249): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): Waiting for incoming connections...
,I/io.jxcore.node.ConnectionHelper( 3249): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3249): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): connect: [08:EC:A9:50:75:41 A3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3249): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
I/jxcore-log( 3249): 2016-01-11T13:03:27.146Z SendDataTCPServer.js: TCP/IP server is bound to port: 48827
I/jxcore-log( 3249): 
I/chromium( 3249): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3249): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3249): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3249): onDiscoveryManagerStateChanged: NOT_STARTED
I/chromium( 3249): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3249): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3249): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): setState: RESTARTING
,I/wpa_supplicant( 1027): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3249): onDiscoveryManagerStateChanged: RUNNING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 309)
W/BluetoothAdapter( 3249): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2056): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2056): info:x10
,D/        ( 2056): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2056): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2056): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2056): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 2056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2056): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2056): Entering PendingCommandState State
,I/ActivityManager(  735): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=3581 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/BluetoothBondStateMachine( 2056): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2056): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2056): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3cc01f70:true
,I/ActivityManager(  735): Killing 2546:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10070/pid_2546/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 2056): StableState(): Entering Off State
,E/bt-btm  ( 2056): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
W/bt-btif ( 2056): bta_dm_check_av:0
,W/bt-btif ( 2056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2056): info:x10
,D/        ( 2056): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2056): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2056): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
E/bt-btif ( 2056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2056): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2056): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2056): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 2056): Failed to remove device: 7C:F9:0E:51:18:22
,I/BluetoothBondStateMachine( 2056): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2056): StableState(): Entering Off State
,W/bt-btif ( 2056): new conn_srvc id:26, app_id:255
W/bt-btif ( 2056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2056): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): Incoming connection initialized (thread ID: 310)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3249): Entering thread (ID: 310)
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): onBytesRead: Read 81 bytes successfully (thread ID: 310)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): Got valid identity from [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): onBytesWritten: 66 bytes successfully written (thread ID: 310)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): removeThreadFromList: Removing thread with ID 310
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): Handshake thread disposed (thread ID: 310)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3249): Exiting thread (ID: 310)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): onConnected: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/io.jxcore.node.ConnectionHelper( 3249): onConnected: Incoming connection to peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/io.jxcore.node.ConnectionHelper( 3249): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3249): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
,I/io.jxcore.node.ConnectionHelper( 3249): onConnected: Incoming socket thread, for peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], created successfully
D/io.jxcore.node.ConnectionHelper( 3249): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3249): Entering thread (ID: 311)
,I/io.jxcore.node.IncomingSocketThread( 3249): Local host address: localhost/127.0.0.1, port: 48827
D/io.jxcore.node.IncomingSocketThread( 3249): Setting local streams and starting stream copying threads...
,I/jxcore-log( 3249): 2016-01-11T13:03:31.427Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3249): 
,I/io.jxcore.node.StreamCopyingThread( 3249): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3249): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3249): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3249): Exiting thread (ID: 311)
,D/io.jxcore.node.StreamCopyingThread( 3249): Entering thread (ID: 313, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3249): Entering thread (ID: 312, name: Sender)
,E/bt-btm  ( 2056): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
W/bt-btif ( 2056): bta_dm_check_av:0
,W/bt-btif ( 2056): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2056): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
W/bt-btif ( 2056): bta_dm_check_av:0
,W/bt-btif ( 2056): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2056): new conn_srvc id:26, app_id:1
W/bt-btif ( 2056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2056): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): onSocketConnected: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 309)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): onBytesWritten: 66 bytes successfully written (thread ID: 314)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): Outgoing connection initialized (*handshake* thread ID: 314)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): Exiting thread (thread ID: 309)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3249): Entering thread (ID: 314)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): Start timer timeout, starting now...
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/jxcore-log( 3249): 2016-01-11T13:03:32.577Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:32.590Z SendDataTCPServer.js: TCP/IP server has received 2970 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:32.596Z SendDataTCPServer.js: TCP/IP server has received 4950 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:32.722Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:32.729Z SendDataTCPServer.js: TCP/IP server has received 6930 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:32.737Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:32.744Z SendDataTCPServer.js: TCP/IP server has received 8910 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:32.782Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:32.819Z SendDataTCPServer.js: TCP/IP server has received 10890 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:32.865Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:32.906Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:32.915Z SendDataTCPServer.js: TCP/IP server has received 14850 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:32.921Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:32.947Z SendDataTCPServer.js: TCP/IP server has received 16830 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:32.957Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:33.104Z SendDataTCPServer.js: TCP/IP server has received 18810 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:33.202Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:33.260Z SendDataTCPServer.js: TCP/IP server has received 20790 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:33.270Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:33.329Z SendDataTCPServer.js: TCP/IP server has received 22770 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:33.393Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:33.400Z SendDataTCPServer.js: TCP/IP server has received 24750 bytes of data
I/jxcore-log( 3249): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3249): 2016-01-11T13:03:33.593Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:33.793Z SendDataTCPServer.js: TCP/IP server has received 26730 bytes of data
I/jxcore-log( 3249): 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
,D/WifiP2pManager( 3249): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): Service request added successfully
,I/jxcore-log( 3249): 2016-01-11T13:03:33.980Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:33.986Z SendDataTCPServer.js: TCP/IP server has received 28710 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:33.998Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:34.067Z SendDataTCPServer.js: TCP/IP server has received 30690 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:34.077Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3249): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3249): 2016-01-11T13:03:34.146Z SendDataTCPServer.js: TCP/IP server has received 32670 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:34.239Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3249): 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3249): 2016-01-11T13:03:34.333Z SendDataTCPServer.js: TCP/IP server has received 34650 bytes of data
I/jxcore-log( 3249): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/btif_config_util( 2056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3249): 2016-01-11T13:03:34.474Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:34.480Z SendDataTCPServer.js: TCP/IP server has received 36630 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:34.487Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:34.640Z SendDataTCPServer.js: TCP/IP server has received 38610 bytes of data
I/jxcore-log( 3249): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3249): 2016-01-11T13:03:34.661Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:34.824Z SendDataTCPServer.js: TCP/IP server has received 40590 bytes of data
I/jxcore-log( 3249): 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): Service discovery started successfully
,I/jxcore-log( 3249): 2016-01-11T13:03:34.920Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:35.108Z SendDataTCPServer.js: TCP/IP server has received 42570 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:35.115Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:35.128Z SendDataTCPServer.js: TCP/IP server has received 44550 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:35.205Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:35.277Z SendDataTCPServer.js: TCP/IP server has received 46530 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:35.284Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:35.435Z SendDataTCPServer.js: TCP/IP server has received 48510 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:35.442Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:35.453Z SendDataTCPServer.js: TCP/IP server has received 50490 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:35.533Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:35.562Z SendDataTCPServer.js: TCP/IP server has received 52470 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:35.614Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:35.621Z SendDataTCPServer.js: TCP/IP server has received 54450 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:35.707Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:35.722Z SendDataTCPServer.js: TCP/IP server has received 56430 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:35.863Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.135Z SendDataTCPServer.js: TCP/IP server has received 58410 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.145Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.162Z SendDataTCPServer.js: TCP/IP server has received 60390 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.170Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.227Z SendDataTCPServer.js: TCP/IP server has received 62370 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.263Z SendDataTCPServer.js: TCP/IP server has received 64350 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.310Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.319Z SendDataTCPServer.js: TCP/IP server has received 66330 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.325Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.330Z SendDataTCPServer.js: TCP/IP server has received 68310 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.391Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.405Z SendDataTCPServer.js: TCP/IP server has received 70290 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.414Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.472Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.513Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.558Z SendDataTCPServer.js: TCP/IP server has received 76230 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.571Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.646Z SendDataTCPServer.js: TCP/IP server has received 78210 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.653Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.724Z SendDataTCPServer.js: TCP/IP server has received 80190 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.802Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.843Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.885Z SendDataTCPServer.js: TCP/IP server has received 84150 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:36.900Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:37.044Z SendDataTCPServer.js: TCP/IP server has received 86130 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:37.053Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:37.115Z SendDataTCPServer.js: TCP/IP server has received 88110 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:37.122Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:37.219Z SendDataTCPServer.js: TCP/IP server has received 90090 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:37.232Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:37.315Z SendDataTCPServer.js: TCP/IP server has received 92070 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:37.324Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:37.330Z SendDataTCPServer.js: TCP/IP server has received 94050 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:37.338Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:37.504Z SendDataTCPServer.js: TCP/IP server has received 96030 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:37.510Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:37.517Z SendDataTCPServer.js: TCP/IP server has received 98010 bytes of data
I/jxcore-log( 3249): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 3249): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper( 3249): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,I/jxcore-log( 3249): 2016-01-11T13:03:37.675Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:03:37.685Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3249): 
,W/bt-btif ( 2056): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 3249): Either failed to read from the output stream or write to the input stream (thread ID: 313, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3249): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3249): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 311
D/io.jxcore.node.IncomingSocketThread( 3249): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3249): doStop: Thread ID: 313
D/io.jxcore.node.IncomingSocketThread( 3249): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3249): doStop: Thread ID: 312
D/io.jxcore.node.IncomingSocketThread( 3249): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3249): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3249): Either failed to read from the output stream or write to the input stream (thread ID: 312, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3249): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3249): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3249): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3249): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3249): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3249): Exiting thread (ID: 312, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3249): Exiting thread (ID: 313, name: Receiver)
,I/jxcore-log( 3249): 2016-01-11T13:03:38.532Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3249): 
,W/bt-rfcomm( 2056): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
W/bt-rfcomm( 2056): RFCOMM_DisconnectInd LCID:0x43
,E/bt-btm  ( 2056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2056): onReceive
,D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16725b6e:true
,I/BTConnectionReceiver( 1377): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1377): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): onConnectionTimeout: [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): shutdown (thread ID: 309)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3249): Exiting thread (ID: 314)
,I/jxcore-log( 3249): 2016-01-11T13:03:46.940Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:75:41 A3-1] timed out
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:03:46.957Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:75:41 A3-1] timed out
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:03:46.958Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3249): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): restart: Restarting...
,W/bt-btif ( 2056): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,D/WifiP2pManager( 3249): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): Service request added successfully
,I/jxcore-log( 3249): 2016-01-11T13:03:51.960Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:03:51.963Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3249): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): Service discovery started successfully
,E/bt-btm  ( 2056): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
E/bt-btm  ( 2056): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2056): bta_dm_check_av:0
,W/bt-btif ( 2056): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2056): onReceive
,I/BTConnectionReceiver( 1377): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1377): Bluetooth Device Name: A3-1
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: P2P: Reject scan trigger since one is already pending
,D/io.jxcore.node.ConnectionHelper( 3249): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3249): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
,I/jxcore-log( 3249): 2016-01-11T13:03:56.979Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:03:56.980Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:03:56.982Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:03:56.982Z SendDataConnector.js: do connect now
I/jxcore-log( 3249): 
I/io.jxcore.node.ConnectionHelper( 3249): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3249): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): connect: [08:EC:A9:50:75:41 A3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): onConnecting: A3-1 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3249): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 316)
W/BluetoothAdapter( 3249): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2056): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2056): info:x10
,D/        ( 2056): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2056): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): restart: Restarting...
,I/BluetoothBondStateMachine( 2056): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 2056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2056): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2056): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2056): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2056): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 2056): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2056): StableState(): Entering Off State
,W/bt-btif ( 2056): new conn_srvc id:26, app_id:255
W/bt-btif ( 2056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2056): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): Incoming connection initialized (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3249): Entering thread (ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): onBytesRead: Read 63 bytes successfully (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): Got valid identity from [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): onBytesWritten: 66 bytes successfully written (thread ID: 317)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): removeThreadFromList: Removing thread with ID 317
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): Handshake thread disposed (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): onIncomingConnectionConnected: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3249): Exiting thread (ID: 317)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): onConnected: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 3249): onConnected: Incoming connection to peer [58:3F:54:73:64:C0 G3-1]
,D/io.jxcore.node.ConnectionHelper( 3249): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
,D/io.jxcore.node.ConnectionHelper( 3249): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 G3-1] is available
I/io.jxcore.node.ConnectionHelper( 3249): onConnected: Incoming socket thread, for peer [58:3F:54:73:64:C0 G3-1], created successfully
D/io.jxcore.node.ConnectionHelper( 3249): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3249): Entering thread (ID: 318)
,I/io.jxcore.node.IncomingSocketThread( 3249): Local host address: localhost/127.0.0.1, port: 48827
D/io.jxcore.node.IncomingSocketThread( 3249): Setting local streams and starting stream copying threads...
,I/jxcore-log( 3249): 2016-01-11T13:04:00.448Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3249): 
,I/io.jxcore.node.StreamCopyingThread( 3249): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3249): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3249): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3249): Exiting thread (ID: 318)
,D/io.jxcore.node.StreamCopyingThread( 3249): Entering thread (ID: 320, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3249): Entering thread (ID: 319, name: Sender)
,W/bt-btif ( 2056): info:x10
,D/        ( 2056): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1377): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1377): Bluetooth Device Name: A3-1
,E/bt-btm  ( 2056): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
W/bt-btif ( 2056): bta_dm_check_av:0
,W/bt-btif ( 2056): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2056): process_service_search_attr_rsp
,W/bt-btif ( 2056): new conn_srvc id:26, app_id:1
W/bt-btif ( 2056): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2056): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): onSocketConnected: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 316)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): onBytesWritten: 66 bytes successfully written (thread ID: 321)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): Outgoing connection initialized (*handshake* thread ID: 321)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): Exiting thread (thread ID: 316)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3249): Entering thread (ID: 321)
,D/WifiP2pManager( 3249): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): onBytesRead: Read 63 bytes successfully (thread ID: 321)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): Handshake succeeded with [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): onHandshakeSucceeded: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3249): Exiting thread (ID: 321)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): onConnected: [08:EC:A9:50:75:41 A3-1]
,I/io.jxcore.node.ConnectionHelper( 3249): onConnected: Outgoing connection to peer [08:EC:A9:50:75:41 A3-1]
D/io.jxcore.node.ConnectionHelper( 3249): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 3249): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 A3-1] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3249): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:75:41 A3-1], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3249): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 3249): Entering thread (ID: 322)
,D/io.jxcore.node.OutgoingSocketThread( 3249): Server socket local port: 59745
I/io.jxcore.node.OutgoingSocketThread( 3249): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3249): onListeningForIncomingConnections: Outgoing connection is using port 59745 (peer ID: 08:EC:A9:50:75:41)
I/jxcore-log( 3249): 2016-01-11T13:04:01.952Z SendDataConnector.js: CLIENT connected to 59745, error: null
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:04:01.953Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3249): 
,I/io.jxcore.node.OutgoingSocketThread( 3249): Incoming data from address: /127.0.0.1, port: 59745
D/io.jxcore.node.OutgoingSocketThread( 3249): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3249): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3249): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3249): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3249): Exiting thread (ID: 322)
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.StreamCopyingThread( 3249): Entering thread (ID: 324, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3249): Entering thread (ID: 323, name: Sender)
,I/jxcore-log( 3249): 2016-01-11T13:04:02.020Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:04:02.024Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3249): 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
I/jxcore-log( 3249): 2016-01-11T13:04:02.889Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:02.892Z SendDataTCPServer.js: TCP/IP server has received 45094 bytes of data
I/jxcore-log( 3249): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): Service discovery started successfully
,I/jxcore-log( 3249): 2016-01-11T13:04:02.932Z SendDataTCPServer.js: TCP/IP server has received 49054 bytes of data
I/jxcore-log( 3249): 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:73010
,I/jxcore-log( 3249): 2016-01-11T13:04:03.116Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.119Z SendDataTCPServer.js: TCP/IP server has received 51034 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.152Z SendDataTCPServer.js: TCP/IP server has received 54994 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.183Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.214Z SendDataTCPServer.js: TCP/IP server has received 56974 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.276Z SendDataTCPServer.js: TCP/IP server has received 58954 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.312Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:04:03.315Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.323Z SendDataTCPServer.js: TCP/IP server has received 60934 bytes of data
I/jxcore-log( 3249): 
,D/        ( 2056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:63816
,I/jxcore-log( 3249): 2016-01-11T13:04:03.374Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.413Z SendDataTCPServer.js: TCP/IP server has received 64894 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.424Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.437Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.447Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.458Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.493Z SendDataTCPServer.js: TCP/IP server has received 72814 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.533Z SendDataTCPServer.js: TCP/IP server has received 76774 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.573Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3249): 
,D/        ( 2056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:52926
,I/jxcore-log( 3249): 2016-01-11T13:04:03.613Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.620Z SendDataTCPServer.js: TCP/IP server has received 78754 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.627Z SendDataTCPServer.js: TCP/IP server has received 80734 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.637Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.672Z SendDataTCPServer.js: TCP/IP server has received 82714 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.679Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.687Z SendDataTCPServer.js: TCP/IP server has received 84694 bytes of data
I/jxcore-log( 3249): 
,D/        ( 2056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:42036
,I/jxcore-log( 3249): 2016-01-11T13:04:03.723Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.734Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.742Z SendDataTCPServer.js: TCP/IP server has received 86674 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.752Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.759Z SendDataTCPServer.js: TCP/IP server has received 88654 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.765Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3249): 
,D/        ( 2056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:33126
,I/jxcore-log( 3249): 2016-01-11T13:04:03.799Z SendDataTCPServer.js: TCP/IP server has received 90634 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.823Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.853Z SendDataTCPServer.js: TCP/IP server has received 96574 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.876Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.882Z SendDataTCPServer.js: TCP/IP server has received 98554 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.893Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.928Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:03.964Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3249): 
,W/bt-btif ( 2056): invalid rfc slot id: 7
,W/io.jxcore.node.StreamCopyingThread( 3249): Either failed to read from the output stream or write to the input stream (thread ID: 320, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3249): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3249): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 G3-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 318
D/io.jxcore.node.OutgoingSocketThread( 3249): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 3249): doStop: Thread ID: 320
D/io.jxcore.node.OutgoingSocketThread( 3249): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3249): doStop: Thread ID: 319
D/io.jxcore.node.OutgoingSocketThread( 3249): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3249): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3249): Either failed to read from the output stream or write to the input stream (thread ID: 319, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3249): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3249): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 G3-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3249): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3249): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3249): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3249): Exiting thread (ID: 319, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3249): Exiting thread (ID: 320, name: Receiver)
,I/jxcore-log( 3249): 2016-01-11T13:04:04.057Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3249): 
,D/        ( 2056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23226
,I/jxcore-log( 3249): 2016-01-11T13:04:04.103Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3249): 
,D/        ( 2056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12336
,I/jxcore-log( 3249): 2016-01-11T13:04:04.215Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3249): 
,D/        ( 2056): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2436
,I/jxcore-log( 3249): 2016-01-11T13:04:04.262Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3249): 
,W/bt-rfcomm( 2056): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 2056): RFCOMM_DisconnectInd LCID:0x46
,I/jxcore-log( 3249): 2016-01-11T13:04:04.397Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:04.569Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:04.570Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): oneRoundDownNow
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:04:04.580Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:04.580Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3249): 
,D/io.jxcore.node.ConnectionHelper( 3249): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
I/io.jxcore.node.OutgoingSocketThread( 3249): close
D/io.jxcore.node.OutgoingSocketThread( 3249): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3249): doStop: Thread ID: 324
D/io.jxcore.node.OutgoingSocketThread( 3249): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3249): doStop: Thread ID: 323
D/io.jxcore.node.OutgoingSocketThread( 3249): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3249): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3249): Either failed to read from the output stream or write to the input stream (thread ID: 323, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3249): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3249): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 A3-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3249): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3249): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3249): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3249): Either failed to read from the output stream or write to the input stream (thread ID: 324, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3249): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3249): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 A3-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3249): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:75:41
,E/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
,D/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3249): Exiting thread (ID: 323, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
,D/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3249): Exiting thread (ID: 324, name: Receiver)
,I/jxcore-log( 3249): 2016-01-11T13:04:04.636Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3249): 
,W/bt-btif ( 2056): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,I/jxcore-log( 3249): ---- round done--------
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): startWithNextDevice
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): do fake peer & start
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:04:04.657Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:04:04.657Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:04:04.657Z SendDataConnector.js: do connect now
I/jxcore-log( 3249): 
I/io.jxcore.node.ConnectionHelper( 3249): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3249): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
,W/io.jxcore.node.ConnectionHelper( 3249): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3249): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 325)
W/BluetoothAdapter( 3249): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2056): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2056): onReceive
,E/bt-btm  ( 2056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2056): onReceive
,I/BTConnectionReceiver( 1377): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1377): Bluetooth Device Name: A3-1
,I/BTConnectionReceiver( 1377): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1377): Bluetooth Device Name: G3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): onConnectionTimeout: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/jxcore-log( 3249): 2016-01-11T13:04:19.669Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] timed out
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:04:19.670Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] timed out
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:19.673Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:24.677Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:04:24.678Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3249): 
,D/io.jxcore.node.ConnectionHelper( 3249): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3249): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
,I/jxcore-log( 3249): 2016-01-11T13:04:29.685Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:04:29.686Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:04:29.687Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:04:29.687Z SendDataConnector.js: do connect now
I/jxcore-log( 3249): 
I/io.jxcore.node.ConnectionHelper( 3249): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3249): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 3249): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3249): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 327)
W/BluetoothAdapter( 3249): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2056): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): setState: RESTARTING
,I/wpa_supplicant( 1027): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 0 device(s) discovered
,W/bt-btif ( 2056): info:x10
,D/        ( 2056): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2056): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2056): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 2056): bta_dm_check_av:0
,W/bt-btif ( 2056): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2056): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2056): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2056): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2056): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2056): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2056): StableState(): Entering Off State
,W/bt-btif ( 2056): new conn_srvc id:26, app_id:255
W/bt-btif ( 2056): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2056): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): Incoming connection initialized (thread ID: 328)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3249): Entering thread (ID: 328)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): onBytesRead: Read 64 bytes successfully (thread ID: 328)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): Got valid identity from [F8:95:C7:87:85:54 G3s-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): onBytesWritten: 66 bytes successfully written (thread ID: 328)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): removeThreadFromList: Removing thread with ID 328
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): Handshake thread disposed (thread ID: 328)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): onIncomingConnectionConnected: [F8:95:C7:87:85:54 G3s-1]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): onConnected: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 3249): onConnected: Incoming connection to peer [F8:95:C7:87:85:54 G3s-1]
D/io.jxcore.node.ConnectionHelper( 3249): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3249): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] is available
,I/io.jxcore.node.ConnectionHelper( 3249): onConnected: Incoming socket thread, for peer [F8:95:C7:87:85:54 G3s-1], created successfully
D/io.jxcore.node.ConnectionHelper( 3249): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3249): Exiting thread (ID: 328)
,D/io.jxcore.node.IncomingSocketThread( 3249): Entering thread (ID: 329)
,I/jxcore-log( 3249): 2016-01-11T13:04:34.550Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3249): 
,I/io.jxcore.node.IncomingSocketThread( 3249): Local host address: localhost/127.0.0.1, port: 48827
D/io.jxcore.node.IncomingSocketThread( 3249): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3249): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3249): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3249): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 3249): Exiting thread (ID: 329)
,D/io.jxcore.node.StreamCopyingThread( 3249): Entering thread (ID: 331, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3249): Entering thread (ID: 330, name: Sender)
,I/jxcore-log( 3249): 2016-01-11T13:04:35.954Z SendDataTCPServer.js: TCP/IP server has received 2970 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:35.962Z SendDataTCPServer.js: TCP/IP server has received 4950 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.029Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.043Z SendDataTCPServer.js: TCP/IP server has received 8910 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.056Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.084Z SendDataTCPServer.js: TCP/IP server has received 12870 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.113Z SendDataTCPServer.js: TCP/IP server has received 17374 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.123Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.136Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.145Z SendDataTCPServer.js: TCP/IP server has received 23314 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.186Z SendDataTCPServer.js: TCP/IP server has received 29254 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.209Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.222Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.254Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.261Z SendDataTCPServer.js: TCP/IP server has received 35194 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.287Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.298Z SendDataTCPServer.js: TCP/IP server has received 37174 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.302Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.321Z SendDataTCPServer.js: TCP/IP server has received 39154 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.328Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.339Z SendDataTCPServer.js: TCP/IP server has received 41134 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.373Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.379Z SendDataTCPServer.js: TCP/IP server has received 45094 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.386Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.409Z SendDataTCPServer.js: TCP/IP server has received 47074 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.419Z SendDataTCPServer.js: TCP/IP server has received 49054 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.423Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.446Z SendDataTCPServer.js: TCP/IP server has received 51034 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.484Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.491Z SendDataTCPServer.js: TCP/IP server has received 54994 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.499Z SendDataTCPServer.js: TCP/IP server has received 56974 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.509Z SendDataTCPServer.js: TCP/IP server has received 58954 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.536Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.548Z SendDataTCPServer.js: TCP/IP server has received 60934 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.565Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.585Z SendDataTCPServer.js: TCP/IP server has received 64894 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.624Z SendDataTCPServer.js: TCP/IP server has received 66874 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.636Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.644Z SendDataTCPServer.js: TCP/IP server has received 68854 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.650Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.662Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.689Z SendDataTCPServer.js: TCP/IP server has received 72814 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.723Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.738Z SendDataTCPServer.js: TCP/IP server has received 76774 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.748Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.753Z SendDataTCPServer.js: TCP/IP server has received 78754 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.779Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.814Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.826Z SendDataTCPServer.js: TCP/IP server has received 84694 bytes of data
I/jxcore-log( 3249): 
,W/bt-sdp  ( 2056): SDP - Rcvd conn cnf with error: 0x22  CID 0x48
E/bt-btif ( 2056): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2056): invalid rfc slot id: 10
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): shutdown (thread ID: 325)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): Exiting thread (thread ID: 325)
,I/jxcore-log( 3249): 2016-01-11T13:04:36.864Z SendDataTCPServer.js: TCP/IP server has received 88654 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:36.903Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3249): 
,E/bt-btm  ( 2056): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 2056): bta_dm_check_av:0
,W/bt-btif ( 2056): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3249): 2016-01-11T13:04:37.055Z SendDataTCPServer.js: TCP/IP server has received 90634 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:37.072Z SendDataTCPServer.js: TCP/IP server has received 94594 bytes of data
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:04:37.104Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3249): 
,W/bt-btif ( 2056): invalid rfc slot id: 9
,W/io.jxcore.node.StreamCopyingThread( 3249): Either failed to read from the output stream or write to the input stream (thread ID: 331, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3249): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3249): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 G3s-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 329
D/io.jxcore.node.IncomingSocketThread( 3249): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3249): doStop: Thread ID: 331
D/io.jxcore.node.IncomingSocketThread( 3249): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3249): doStop: Thread ID: 330
D/io.jxcore.node.IncomingSocketThread( 3249): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3249): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3249): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3249): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3249): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3249): Exiting thread (ID: 331, name: Receiver)
W/io.jxcore.node.StreamCopyingThread( 3249): Either failed to read from the output stream or write to the input stream (thread ID: 330, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3249): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3249): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 G3s-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3249): Exiting thread (ID: 330, name: Sender)
W/bt-rfcomm( 2056): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 2056): RFCOMM_DisconnectInd LCID:0x4a
I/jxcore-log( 3249): 2016-01-11T13:04:37.182Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3249): 
,E/bt-btm  ( 2056): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 2056): bta_dm_check_av:0
,W/bt-btif ( 2056): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): Start timer timeout, starting now...
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/btif_config_util( 2056): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2056): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2056): onReceive
,I/BTConnectionReceiver( 1377): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1377): Bluetooth Device Name: G3s-1
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2056): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2056): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2056): invalid rfc slot id: 11
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 327)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): Maximum number of allowed retries (0) reached, giving up... (thread ID: 327)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): Exiting thread (thread ID: 327)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/jxcore-log( 3249): 2016-01-11T13:04:42.196Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:04:42.197Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:04:42.198Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3249): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): shutdown (thread ID: 327)
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 3249): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): Service request added successfully
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
,I/io.jxcore.node.ConnectionHelper( 3249): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3249): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,I/jxcore-log( 3249): 2016-01-11T13:04:47.199Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:04:47.199Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3249): 
,D/io.jxcore.node.ConnectionHelper( 3249): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3249): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 3249): 2016-01-11T13:04:52.205Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:04:52.206Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:04:52.207Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:04:52.207Z SendDataConnector.js: do connect now
I/jxcore-log( 3249): 
I/io.jxcore.node.ConnectionHelper( 3249): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3249): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 3249): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3249): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 333)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3249): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3249): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2056): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2056): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2056): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2056): invalid rfc slot id: 13
W/BluetoothAdapter( 3249): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2056): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/ActivityManager(  735): Killing 1948:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10031/pid_1948/cgroup.procs: No such file or directory
,I/jxcore-log( 3249): timeout now
I/jxcore-log( 3249): 
I/jxcore-log( 3249): weAreDoneNow, resultArray.length: 1
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): sendReportNow
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): done, now sending data to server
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:05:07.216Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3249): 
,D/io.jxcore.node.ConnectionHelper( 3249): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3249): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 3249): 2016-01-11T13:05:07.218Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3249): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): onConnectionTimeout: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/jxcore-log( 3249): 2016-01-11T13:05:07.220Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] timed out
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:05:07.220Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] timed out
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:05:07.221Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:05:12.222Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:05:12.223Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3249): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): setState: RESTARTING
,I/wpa_supplicant( 1027): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1027): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 0 device(s) discovered
,D/io.jxcore.node.ConnectionHelper( 3249): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3249): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3249): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 3249): 2016-01-11T13:05:17.228Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:05:17.228Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:05:17.229Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3249): 
I/jxcore-log( 3249): 2016-01-11T13:05:17.229Z SendDataConnector.js: do connect now
I/jxcore-log( 3249): 
,I/io.jxcore.node.ConnectionHelper( 3249): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3249): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
,W/io.jxcore.node.ConnectionHelper( 3249): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3249): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3249): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 335)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3249): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3249): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2056): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): Start timer timeout, starting now...
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): restart: Restarting...
,D/WifiP2pManager( 3249): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): Service request added successfully
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1027): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 3 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): Service discovery started successfully
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
,I/io.jxcore.node.ConnectionHelper( 3249): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 3249): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 3249): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3249): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 3249): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3249): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3249): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 3249): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3249): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1027): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3249): teardown
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): testSendData stopped
I/jxcore-log( 3249): 
I/io.jxcore.node.ConnectionHelper( 3249): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3249): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3249): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3249): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3249): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3249): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3249): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3249): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3249): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3249): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3249): setState: NOT_STARTED
,I/jxcore-log( 3249): StopBroadcasting went ok
I/jxcore-log( 3249): 
,I/jxcore-log( 3249): 2016-01-11T13:05:27.050Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3249): 
,I/chromium( 3249): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3249): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3249): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3249): ****TEST TOOK:  ms ****
I/jxcore-log( 3249): 
I/jxcore-log( 3249): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3249): 
,D/AndroidRuntime( 3679): 
D/AndroidRuntime( 3679): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3679): CheckJNI is OFF
,D/AndroidRuntime( 3679): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  735): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  735): Killing 3249:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  735): WIN DEATH: Window{213c7e11 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  735): Client connection lost with reason: 4
,E/bt-btif ( 2056): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:14, channel:-1
E/bt-btif ( 2056): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:15, channel:1
,W/PackageSettings(  735): Skipping PackageSetting{2e339be3 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  735):   Force finishing activity ActivityRecord{a23316d u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  735): Spurious death for ProcessRecord{ba0a20f 3249:com.test.thalitest/u0a270}, curProc for 3249: null
,I/ActivityManager(  735): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1377): Explicit concurrent mark sweep GC freed 25650(1260KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 19MB/25MB, paused 304us total 24.891ms
,I/art     ( 1614): Explicit concurrent mark sweep GC freed 17082(900KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/30MB, paused 515us total 39.540ms
,I/InputReader(  735): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1107): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1569): Ignoring removeGeofence because network location is disabled.
,I/art     ( 1301): Explicit concurrent mark sweep GC freed 3934(293KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 906us total 59.278ms
,I/Adreno-EGL(  946): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  946): Initialized EGL, version 1.4
,D/OpenGLRenderer(  946): Enabling debug mode 0
,I/art     (  735): Explicit concurrent mark sweep GC freed 34849(1785KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.659ms total 81.572ms
,I/art     (  735): WaitForGcToComplete blocked for 84.829ms for cause Explicit
,D/VoicemailCleanupService( 2850): Cleaning up data for package: com.test.thalitest
,I/Keyboard.Facilitator.DecoderInitializer( 1107): run()
,I/UpdateIcingCorporaServi( 1377): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1301): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3e6fd80c new=com.google.android.velvet.VelvetApplication@3e6fd80c
,I/Decoder ( 1107): createOrResetDecoder
,I/ActivityManager(  735): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3718 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ConfigService( 1569): onCreate
,D/BackupManagerService(  735): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  735): Receieved: android.intent.action.PACKAGE_REMOVED
,W/ContextImpl( 3718): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,W/InputMethodManagerService(  735): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@3de69feb (uid=10034 pid=946)
,D/TaskPersister(  735): removeObsoleteFile: deleting file=214_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader( 1107): run()
,D/ChimeraCfgMgr( 1614): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1614): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 1614): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1614): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1614): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1614): Module APK com.google.android.play.games already loaded
,I/UpdateIcingCorporaServi( 1377): UpdateCorporaTask done [took 140 ms] updated apps [took 140 ms] 
,E/NetworkScheduler.SchedulerReceiver( 1569): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1569): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1107): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1107): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1107): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1107): run()
I/StatsUtilsManager( 1107): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1107): shouldRecordStats() = Too Soon
,I/art     (  735): Explicit concurrent mark sweep GC freed 10424(547KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.464ms total 176.821ms
,I/LocationSettingsChecker( 1614): Removing dialog suppression flag for package com.test.thalitest
,D/gH_CompatibleDatabase( 1614): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1614): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1614): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1614): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1614): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1614): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1614): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1614): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1614): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1614): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1614): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1614): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1614): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  735): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3751 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/Launcher( 1301): Deferring update until onResume
,W/ResourcesManager( 1301): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/BaseAppContext( 1614): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1614): App measurement is starting up, version: 8489
I/GMPM-SVC( 1614): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/BaseAppContext( 1614): Using Auth Proxy for data requests.
W/ResourcesManager( 1301): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AndroidRuntime( 3679): Shutting down VM
,I/Icing   ( 1614): doRemovePackageData com.test.thalitest
,I/Launcher( 1301): Deferring update until onResume
,I/ActivityManager(  735): Killing 2997:com.google.android.gms:car/u0a8 (adj 15): empty #17
,I/ActivityManager(  735): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3779 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
W/libprocessgroup(  735): failed to open /acct/uid_10008/pid_2997/cgroup.procs: No such file or directory
,I/ActivityManager(  735): Killing 2780:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10002/pid_2780/cgroup.procs: No such file or directory
,D/ExternalStorage( 3779): After updating volumes, found 1 active roots
,W/ResourcesManager( 3163): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3163): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3751): Update found 7 roots in 368ms

```
