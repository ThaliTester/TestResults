#### Test 56151093914d164_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3455): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3455):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3455):   adb logcat -s GAv4
D/ChimeraCfgMgr( 1692): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1692): Module APK com.google.android.play.games already loaded
W/GAv4    ( 3455): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3455): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3455): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3455): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2722): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3455): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3455): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  760): Killing 2919:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
V/JNIHelp ( 3455): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3455): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3455): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  760): failed to open /acct/uid_10061/pid_2919/cgroup.procs: No such file or directory
V/GLSActivity( 1616): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1692): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1692): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1692): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1692): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/ActivityManager(  760): Killing 3049:com.google.android.apps.cloudprint/u0a35 (adj 15): empty #17
W/libprocessgroup(  760): failed to open /acct/uid_10035/pid_3049/cgroup.procs: No such file or directory
,D/AndroidRuntime( 3508): 
D/AndroidRuntime( 3508): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3508): CheckJNI is OFF
D/AndroidRuntime( 3508): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3529 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3508): Shutting down VM
V/ActivityManager(  760): Display changed displayId=0
I/WebViewFactory( 3529): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3529): Time to load native libraries: 3 ms (timestamps 8980-8983)
I/LibraryLoader( 3529): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3529): Binding Chromium to main looper Looper (main, tid 1) {3b21c098}
I/LibraryLoader( 3529): Expected native library version number "",actual native library version number ""
I/chromium( 3529): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3529): Initializing chromium process, singleProcess=true
W/art     ( 3529): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3529): ApplicationContext is null in ApplicationStatus
,W/chromium( 3529): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3529): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3529): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3529): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22952e78:true
,W/art     ( 3529): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3529): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3529): CordovaWebView is running on device made by: LGE
,W/art     ( 3529): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3529): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3529): Render dirty regions requested: true
,D/Atlas   ( 3529): Validating map...
,W/chromium( 3529): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3529): Initialized EGL, version 1.4
D/OpenGLRenderer( 3529): Enabling debug mode 0
,W/IInputConnectionWrapper( 3529): showStatusIcon on inactive InputConnection
,I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +449ms (total +57s201ms)
,W/BindingManager( 3529): Cannot call determinedVisibility() - never saw a connection for the pid: 3529
,D/JsMessageQueue( 3529): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3529): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1356454528
,D/JX-Cordova( 3529): jxcore cordova android initializing
,W/jxcore-log( 3529): Initializing JXcore engine
W/jxcore-log( 3529): JXcore engine is ready
,W/jxcore-log( 3529): Starting JXcore engine
,W/.test.thalitest( 3529): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8445]" dev="sockfs" ino=8445 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3529): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3529): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9489]" dev="sockfs" ino=9489 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3529): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[21008]" dev="sockfs" ino=21008 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3529): Platform android
W/jxcore-log( 3529): 
W/jxcore-log( 3529): Process ARCH arm
W/jxcore-log( 3529): 
,I/jxcore-log( 3529): JXcore Cordova bridge is ready!
I/jxcore-log( 3529): 
,W/jxcore-log( 3529): JXcore engine is started
,I/Choreographer( 3529): Skipped 121 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3529): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3529): Toggling radios to true
I/jxcore-log( 3529): 
,D/BluetoothAdapter( 3529): enable(): BT is already enabled..!
,D/WifiService(  760): New client listening to asynchronous messages
,D/WifiService(  760): setWifiEnabled: true pid=3529, uid=10270
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3529): Radios toggled
I/jxcore-log( 3529): 
,I/jxcore-log( 3529): My device name is: LGE-Nexus 5
I/jxcore-log( 3529): 
,I/wpa_supplicant( 1040): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  760): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  760): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1616): Read error: ssl=0x9b2f7e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1616): SSL shutdown failed: ssl=0x9b2f7e00: I/O error during system call, Broken pipe
D/ConnectivityService(  760): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  760): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1040): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  760): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/ConnectivityService(  760): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/CSLegacyTypeTracker(  760): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler( 1692): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Disconnected - quitting
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  760): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1248): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  760): NetworkAgent: NetworkAgent channel lost
,V/GLSActivity( 1616): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1616): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1377): OkHttp exception
W/EventLoggerService( 1377): Unable to send logs Error code: 262146
,I/wpa_supplicant( 1040): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1040): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1040): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1040): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  760): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  760): Start Dhcp Watchdog 2
,E/native  (  760): do suspend false
,E/WifiStateMachine(  760): scanCount==0 - aborting
,I/dhcpcd  ( 3621): version 5.5.6 starting
,E/dhcpcd  ( 3621): get_duid: Read-only file system
,I/dhcpcd  ( 3621): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3621): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3621): wlan0: leased 192.168.1.114 for 86400 seconds
,I/jxcore-log( 3529): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3529): 
,E/native  (  760): do suspend true
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  760): Adding iface wlan0 to network 101
,E/ConnectivityService(  760): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  760): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  760): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  760): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  760): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760):    accepting network in place of null
,D/CSLegacyTypeTracker(  760): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  760): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1692): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 17 Jan 2016 15:02:28 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453042948958], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453042948942]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Validated
,D/ConnectivityService(  760): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1248): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1692): CM callback handler got msg 524290
,I/jxcore-log( 3529): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3529): 
,I/jxcore-log( 3529): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3529): 
,I/jxcore-log( 3529): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3529): 
,I/jxcore-log( 3529): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3529): 
,I/jxcore-log( 3529): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3529): 
,I/jxcore-log( 3529): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3529): 
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 2791): type=WIFI subType= reason=null isConnected=true
,D/Tethering(  760): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2791): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2791): type=WIFI subType= reason=null isConnected=true
I/jxcore-log( 3529): Test app app.js loaded
I/jxcore-log( 3529): 
,I/SystemUpdateService( 1692): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/Choreographer( 3529): Skipped 194 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3529): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/SystemUpdateService( 1692): onCreate
,D/SystemUpdateService( 1692): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/GpsLocationProvider(  760): No APN found to select.
,I/SystemUpdateService( 1692): active receiver: enabled
,I/SystemUpdateService( 1692): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1692): retry (wakeup: false) in 3599969 ms
,I/ActivityManager(  760): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3685 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1692): onDestroy
,E/GpsLocationProvider(  760): No APN found to select.
,I/GAv4    ( 3685): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3685):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3685):   adb logcat -s GAv4
,W/GAv4    ( 3685): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3685): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3685): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1692): CM callback handler got msg 524295
,D/ConnectivityService(  760): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/WebViewFactory( 3685): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3685): Time to load native libraries: 1 ms (timestamps 5183-5184)
I/LibraryLoader( 3685): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3685): Binding Chromium to main looper Looper (main, tid 1) {3de218ca}
,I/LibraryLoader( 3685): Expected native library version number "",actual native library version number ""
,I/chromium( 3685): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3685): Initializing chromium process, singleProcess=true
,W/art     ( 3685): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3685): ApplicationContext is null in ApplicationStatus
,W/chromium( 3685): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3685): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3685): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3685): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3685): Requires BLUETOOTH permission
,I/art     (  760): Explicit concurrent mark sweep GC freed 43813(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 28MB/42MB, paused 1.783ms total 73.544ms
I/NSApplication( 3685): Starting up...
,I/ActivityManager(  760): Killing 3027:com.google.android.apps.cloudprint:sync/u0a35 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10035/pid_3027/cgroup.procs: No such file or directory
,V/MusicLeanback( 2791): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1692): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1692): onCreate
,D/SystemUpdateService( 1692): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1692): active receiver: enabled
,I/SystemUpdateService( 1692): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1692): retry (wakeup: false) in 3599982 ms
,D/SystemUpdateService( 1692): onDestroy
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2791): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2791): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  760): No APN found to select.
,I/SystemUpdateService( 1692): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1692): onCreate
,D/SystemUpdateService( 1692): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1692): active receiver: enabled
,I/SystemUpdateService( 1692): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1692): retry (wakeup: false) in 3599970 ms
,D/SystemUpdateService( 1692): onDestroy
,D/Finsky  ( 2722): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2722): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/ChimeraCfgMgr( 1692): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1692): Module APK com.google.android.play.games already loaded
,I/GamesSyncServiceMain( 1692): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 1692): Failed to execute periodic sync, missing client context - aborting
,V/GLSActivity( 1616): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1616): Vacuum at: now=1453042962512 tag=VacuumService
,I/art     ( 1616): Explicit concurrent mark sweep GC freed 55533(3MB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 21MB/36MB, paused 771us total 61.502ms
,I/PhenotypeConfigurator( 1616): Scheduling Phenotype for one-off execution 5279 seconds from now (1453042962731)
,D/GetConfigurationSnapshotOperation( 1616): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1616): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1616): Using platform SSLCertificateSocketFactory
,I/ClearcutLoggerApiImpl( 1616): disconnect managed GoogleApiClient
,I/jxcore-log( 3529): TAP version 13
I/jxcore-log( 3529): 
,I/jxcore-log( 3529): # setup
I/jxcore-log( 3529): 
,I/jxcore-log( 3529): # multiplex can send data
I/jxcore-log( 3529): 
,I/jxcore-log( 3529): # teardown
I/jxcore-log( 3529): 
,I/ActivityManager(  760): Killing 1986:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10031/pid_1986/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3873 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3873): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3873):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3873):   adb logcat -s GAv4
,W/GAv4    ( 3873): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3873): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3873): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  760): Killing 2613:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2613/cgroup.procs: No such file or directory
,W/bt-smp  ( 2122): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2122): Plain text(LSB ~ MSB) = a6 bd 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2122): Encrypted text(LSB ~ MSB) = 34 69 93 fd 73 f6 11 90 42 d4 b2 4e 70 34 9d a2 
,W/bt-btm  ( 2122): Stopping oneshot timer
,I/UsageStatsService(  760): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3925): 
D/AndroidRuntime( 3925): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3925): CheckJNI is OFF
D/AndroidRuntime( 3925): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  760): Killing 3529:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  760): WIN DEATH: Window{4ed25a8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  760): Client connection lost with reason: 4
I/ActivityManager(  760):   Force finishing activity ActivityRecord{3e1a6bf4 u0 com.test.thalitest/.MainActivity t216}
W/PackageSettings(  760): Skipping PackageSetting{37b8b1ac com.example.hello/10278} due to missing metadata
W/ActivityManager(  760): Spurious death for ProcessRecord{38ce56ba 3529:com.test.thalitest/u0a270}, curProc for 3529: null
I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/art     ( 1692): Explicit concurrent mark sweep GC freed 18546(989KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 22MB/30MB, paused 453us total 32.161ms
I/art     ( 1377): Explicit concurrent mark sweep GC freed 9019(579KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 295us total 30.516ms
I/art     ( 1313): Explicit concurrent mark sweep GC freed 7246(544KB) AllocSpace objects, 2(253KB) LOS objects, 38% free, 25MB/41MB, paused 720us total 19.618ms
I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1616): Ignoring removeGeofence because network location is disabled.
D/NetworkChangeNotifierAutoDetect(  940): Network connectivity changed, type is: 2
I/Keyboard.Facilitator( 1103): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1103): run()
I/Decoder ( 1103): createOrResetDecoder
I/LibraryLoader( 1516): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
I/OpenGLRenderer(  940): Initialized EGL, version 1.4
D/OpenGLRenderer(  940): Enabling debug mode 0
D/VoicemailCleanupService( 1351): Cleaning up data for package: com.test.thalitest
I/art     (  760): Explicit concurrent mark sweep GC freed 31087(1683KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 963us total 101.783ms
I/art     (  760): WaitForGcToComplete blocked for 93.242ms for cause Explicit
W/art     (  940): Attempt to remove local handle scope entry from IRT, ignoring
I/UpdateIcingCorporaServi( 1377): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ConfigService( 1616): onCreate
W/Launcher( 1313): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@39d80f1 new=com.google.android.velvet.VelvetApplication@39d80f1
W/InputMethodManagerService(  760): Got RemoteException sending setActive(false) notification to pid 3529 uid 10270
I/Keyboard.Facilitator( 1103): onFinishInput()
I/LibraryLoader( 1516): Time to load native libraries: 85 ms (timestamps 72-157)
I/LibraryLoader( 1516): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/chromium( 1516): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 1516): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1516): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3969 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  760): Explicit concurrent mark sweep GC freed 4832(259KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 3.605ms total 155.409ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1103): run()
W/ContextImpl( 3969): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
D/TaskPersister(  760): removeObsoleteFile: deleting file=216_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader( 1103): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
D/PackageBroadcastService( 1692): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1692): Clearing selected account for com.test.thalitest
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Loading LM = contacts
D/ChimeraCfgMgr( 1692): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1692): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1103): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1103): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1103): run()
I/StatsUtilsManager( 1103): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1103): shouldRecordStats() = Too Soon
D/ChimeraCfgMgr( 1692): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1692): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1616): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1616): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/LocationSettingsChecker( 1692): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 1692): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1692): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1692): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1692): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1692): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1692): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1692): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/ActivityManager(  760): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/UpdateIcingCorporaServi( 1377): UpdateCorporaTask done [took 246 ms] updated apps [took 246 ms] 
I/ActivityManager(  760): Resuming delayed broadcast
W/InputMethodManagerService(  760): Starting input on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@1d99382 (uid=10034 pid=940)
D/gH_CompatibleDatabase( 1692): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1692): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1692): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1692): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
W/InputMethodManagerService(  760): Starting input on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@1d99382 (uid=10034 pid=940)
I/ActivityManager(  760): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4011 uid=10039 gids={50039, 9997} abi=armeabi-v7a
D/gH_CompatibleDatabase( 1692): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1692): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/art     (  196): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 178us total 8.200ms
I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 169us total 7.417ms
I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 7.422ms
E/BufferQueueProducer(  175): [com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity] cancelBuffer: BufferQueue has been abandoned
I/GMPM-SVC( 1692): App measurement is starting up, version: 8489
I/GMPM-SVC( 1692): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/BaseAppContext( 1692): Using Auth Proxy for data requests.
W/BaseAppContext( 1692): Using Auth Proxy for data requests.
D/AndroidRuntime( 3925): Shutting down VM
I/Icing   ( 1692): doRemovePackageData com.test.thalitest
I/ActivityManager(  760): Killing 3009:com.google.android.videos/u0a77 (adj 15): empty #17
I/ActivityManager(  760): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4038 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
W/libprocessgroup(  760): failed to open /acct/uid_10077/pid_3009/cgroup.procs: No such file or directory
I/ActivityManager(  760): Killing 2006:com.android.providers.calendar/u0a2 (adj 15): empty #17
W/libprocessgroup(  760): failed to open /acct/uid_10002/pid_2006/cgroup.procs: No such file or directory
I/Launcher( 1313): Deferring update until onResume
E/SQLiteLog( 1313): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
D/ExternalStorage( 4038): After updating volumes, found 1 active roots
W/ResourcesManager( 1313): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3455): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3455): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 1313): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1313): Deferring update until onResume

```
