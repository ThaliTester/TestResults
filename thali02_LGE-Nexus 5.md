#### Test 56151093c886730_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3163): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3163):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3163):   adb logcat -s GAv4
W/GAv4    ( 3163): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3163): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3163): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3163): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2614): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3163): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3163): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  761): Killing 2583:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3163): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3163): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3163): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  761): failed to open /acct/uid_10069/pid_2583/cgroup.procs: No such file or directory
V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1648): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1648): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1648): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1648): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,I/ActivityManager(  761): Killing 2538:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_2538/cgroup.procs: No such file or directory
D/AndroidRuntime( 3217): 
D/AndroidRuntime( 3217): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3217): CheckJNI is OFF
D/AndroidRuntime( 3217): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3231 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3217): Shutting down VM
V/ActivityManager(  761): Display changed displayId=0
I/WebViewFactory( 3231): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3231): Time to load native libraries: 2 ms (timestamps 8990-8992)
I/LibraryLoader( 3231): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3231): Binding Chromium to main looper Looper (main, tid 1) {183e4936}
I/LibraryLoader( 3231): Expected native library version number "",actual native library version number ""
I/chromium( 3231): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3231): Initializing chromium process, singleProcess=true
W/art     ( 3231): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3231): ApplicationContext is null in ApplicationStatus
W/chromium( 3231): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3231): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3231): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3231): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c32249a:true
,W/art     ( 3231): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3231): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3231): CordovaWebView is running on device made by: LGE
,W/art     ( 3231): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3231): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3231): Render dirty regions requested: true
,D/Atlas   ( 3231): Validating map...
,W/chromium( 3231): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3231): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3231): Enabling debug mode 0
,W/IInputConnectionWrapper( 3231): showStatusIcon on inactive InputConnection
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +429ms (total +57s314ms)
,W/BindingManager( 3231): Cannot call determinedVisibility() - never saw a connection for the pid: 3231
,D/JsMessageQueue( 3231): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3231): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1405526272
,D/JX-Cordova( 3231): jxcore cordova android initializing
,W/jxcore-log( 3231): Initializing JXcore engine
W/jxcore-log( 3231): JXcore engine is ready
,W/jxcore-log( 3231): Starting JXcore engine
,W/.test.thalitest( 3231): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6044]" dev="sockfs" ino=6044 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3231): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3231): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8457]" dev="sockfs" ino=8457 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3231): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19759]" dev="sockfs" ino=19759 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3231): Platform android
W/jxcore-log( 3231): 
W/jxcore-log( 3231): Process ARCH arm
W/jxcore-log( 3231): 
,I/jxcore-log( 3231): JXcore Cordova bridge is ready!
I/jxcore-log( 3231): 
W/jxcore-log( 3231): JXcore engine is started
I/Choreographer( 3231): Skipped 117 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3231): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3231): Toggling radios to true
I/jxcore-log( 3231): 
,D/BluetoothAdapter( 3231): enable(): BT is already enabled..!
,D/WifiService(  761): New client listening to asynchronous messages
,D/WifiService(  761): setWifiEnabled: true pid=3231, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3231): Radios toggled
I/jxcore-log( 3231): 
,I/jxcore-log( 3231): My device name is: LGE-Nexus 5
I/jxcore-log( 3231): 
,I/wpa_supplicant( 1030): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  761): do suspend true
D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1570): Read error: ssl=0xaf58be00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1570): SSL shutdown failed: ssl=0xaf58be00: I/O error during system call, Broken pipe
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on <unknown ssid>
E/WifiStateMachine(  761): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1030): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  761): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1251): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
,D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityManager.CallbackHandler( 1648): CM callback handler got msg 524292
,V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1350): OkHttp exception
,W/EventLoggerService( 1350): Unable to send logs Error code: 262146
,I/wpa_supplicant( 1030): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1030): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1030): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1030): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  761): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  761): Start Dhcp Watchdog 2
,E/native  (  761): do suspend false
,E/WifiStateMachine(  761): scanCount==0 - aborting
,I/dhcpcd  ( 3340): version 5.5.6 starting
E/dhcpcd  ( 3340): get_duid: Read-only file system
,I/dhcpcd  ( 3340): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3340): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3340): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  761): do suspend true
,E/WifiStateMachine(  761): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  761): Adding iface wlan0 to network 101
,E/ConnectivityService(  761): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  761): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  761): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  761): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,I/jxcore-log( 3231): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3231): 
D/ConnectivityService(  761): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-4ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761):    accepting network in place of null
D/CSLegacyTypeTracker(  761): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1648): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 17 Jan 2016 12:38:18 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453034298397], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453034298380]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Validated
,D/ConnectivityService(  761): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1251): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1648): CM callback handler got msg 524290
,I/jxcore-log( 3231): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3231): 
,I/jxcore-log( 3231): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3231): 
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1648): CM callback handler got msg 524295
,I/jxcore-log( 3231): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3231): 
,I/jxcore-log( 3231): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3231): 
,I/jxcore-log( 3231): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3231): 
,I/jxcore-log( 3231): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3231): 
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
D/Tethering(  761): MasterInitialState.processMessage what=3
,I/jxcore-log( 3231): Test app app.js loaded
I/jxcore-log( 3231): 
,I/NetworkMonitor( 2727): type=WIFI subType= reason=null isConnected=true
,I/chromium( 3231): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/NetworkMonitor( 2727): type=WIFI subType= reason=null isConnected=true
V/MusicLeanback( 2727): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1648): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,E/GpsLocationProvider(  761): No APN found to select.
,D/SystemUpdateService( 1648): onCreate
,D/SystemUpdateService( 1648): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/GpsLocationProvider(  761): No APN found to select.
,I/SystemUpdateService( 1648): active receiver: enabled
,I/SystemUpdateService( 1648): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1648): retry (wakeup: false) in 3599984 ms
,I/ActivityManager(  761): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3393 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1648): onDestroy
,I/GAv4    ( 3393): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3393):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3393):   adb logcat -s GAv4
,W/GAv4    ( 3393): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  761): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/GAv4    ( 3393): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3393): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3393): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3393): Time to load native libraries: 1 ms (timestamps 5198-5199)
,I/LibraryLoader( 3393): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3393): Binding Chromium to main looper Looper (main, tid 1) {89a7ab8}
I/LibraryLoader( 3393): Expected native library version number "",actual native library version number ""
I/chromium( 3393): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3393): Initializing chromium process, singleProcess=true
W/art     ( 3393): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3393): ApplicationContext is null in ApplicationStatus
,W/chromium( 3393): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3393): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3393): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3393): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3393): Requires BLUETOOTH permission
,I/NSApplication( 3393): Starting up...
,I/ActivityManager(  761): Killing 2699:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2699/cgroup.procs: No such file or directory
,V/MusicLeanback( 2727): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1648): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1648): onCreate
,D/SystemUpdateService( 1648): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1648): active receiver: enabled
,I/SystemUpdateService( 1648): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1648): retry (wakeup: false) in 3599965 ms
,D/SystemUpdateService( 1648): onDestroy
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2727): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2727): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1648): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1648): onCreate
,D/SystemUpdateService( 1648): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1648): active receiver: enabled
,I/SystemUpdateService( 1648): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1648): retry (wakeup: false) in 3599970 ms
,D/SystemUpdateService( 1648): onDestroy
,I/art     (  761): Explicit concurrent mark sweep GC freed 45212(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.313ms total 114.324ms
,E/GpsLocationProvider(  761): No APN found to select.
,D/Finsky  ( 2614): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2614): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1570): Vacuum at: now=1453034312037 tag=VacuumService
,D/PerfProfileCollectorService( 1648): User is not opt-in to Usage & Diagnostics.
D/PerfProfileCollectorService( 1648): removeStateFiles() called
D/PerfProfileCollectorService( 1648): User is not opt-in to Usage & Diagnostics.
,I/ClearcutLoggerApiImpl( 1570): disconnect managed GoogleApiClient
,I/jxcore-log( 3231): --= Surplus to requirements =--
I/jxcore-log( 3231): 
I/jxcore-log( 3231): ****TEST TOOK:  ms ****
I/jxcore-log( 3231): 
I/jxcore-log( 3231): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3231): 
,D/AndroidRuntime( 3532): 
D/AndroidRuntime( 3532): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3532): CheckJNI is OFF
,D/AndroidRuntime( 3532): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 3231:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  761): WIN DEATH: Window{102ce84a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  761): Client connection lost with reason: 4
,W/PackageSettings(  761): Skipping PackageSetting{dbdac6a com.example.hello/10278} due to missing metadata
,I/ActivityManager(  761):   Force finishing activity ActivityRecord{2b90adb6 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  761): Spurious death for ProcessRecord{2bf9965e 3231:com.test.thalitest/u0a270}, curProc for 3231: null
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  761):   Force finishing activity ActivityRecord{2b90adb6 u0 com.test.thalitest/.MainActivity t216 f}
W/ActivityManager(  761): Duplicate finish request for ActivityRecord{2b90adb6 u0 com.test.thalitest/.MainActivity t216 f}
,I/art     ( 1350): Explicit concurrent mark sweep GC freed 8603(587KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 18MB/25MB, paused 299us total 19.720ms
,I/art     ( 1648): Explicit concurrent mark sweep GC freed 18592(972KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 444us total 31.704ms
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1570): Ignoring removeGeofence because network location is disabled.
,I/art     ( 1310): Explicit concurrent mark sweep GC freed 3914(292KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 223us total 35.895ms
,I/Keyboard.Facilitator( 1098): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1098): run()
,D/VoicemailCleanupService( 2818): Cleaning up data for package: com.test.thalitest
,I/Decoder ( 1098): createOrResetDecoder
,I/art     (  761): Explicit concurrent mark sweep GC freed 18251(1101KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 4.457ms total 82.312ms
,I/UpdateIcingCorporaServi( 1350): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1310): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2297d037 new=com.google.android.velvet.VelvetApplication@2297d037
,I/Adreno-EGL(  949): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  949): Initialized EGL, version 1.4
,D/OpenGLRenderer(  949): Enabling debug mode 0
,I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3572 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ConfigService( 1570): onCreate
,D/TaskPersister(  761): removeObsoleteFile: deleting file=216_task.xml
,W/InputMethodManagerService(  761): Got RemoteException sending setActive(false) notification to pid 3231 uid 10270
,I/Keyboard.Facilitator( 1098): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1098): run()
,I/art     (  761): Explicit concurrent mark sweep GC freed 5323(270KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 3.704ms total 147.538ms
W/ContextImpl( 3572): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1648): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1648): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1648): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1648): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1648): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1648): Module APK com.google.android.play.games already loaded
I/ActivityManager(  761): Killing 2675:com.android.settings/1000 (adj 15): empty #17
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1098): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1098): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1098): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1098): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1098): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1098): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1098): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1098): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1098): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1098): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1098): run()
I/StatsUtilsManager( 1098): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1098): shouldRecordStats() = Too Soon
,D/WifiService(  761): Client connection lost with reason: 4
,D/AndroidRuntime( 3532): Shutting down VM
,W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2675/cgroup.procs: No such file or directory
,I/Launcher( 1310): Deferring update until onResume
,I/LocationSettingsChecker( 1648): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1570): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1570): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/ResourcesManager( 1310): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1310): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  761): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/UpdateIcingCorporaServi( 1350): UpdateCorporaTask done [took 312 ms] updated apps [took 311 ms] 
,I/ActivityManager(  761): Resuming delayed broadcast
,W/BaseAppContext( 1648): Using Auth Proxy for data requests.
,D/gH_CompatibleDatabase( 1648): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1648): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1648): 0 metrics were deleted when clearing package com.test.thalitest.
,I/Launcher( 1310): Deferring update until onResume
D/gH_CompatibleDatabase( 1648): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1648): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1648): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1648): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1648): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1648): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1648): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1648): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1648): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1648): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  761): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3608 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,W/BaseAppContext( 1648): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1648): App measurement is starting up, version: 8489
,I/GMPM-SVC( 1648): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/Icing   ( 1648): doRemovePackageData com.test.thalitest
,I/ActivityManager(  761): Killing 2557:com.google.android.gm/u0a70 (adj 15): empty #17
,I/ActivityManager(  761): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3635 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2557/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Killing 1949:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10031/pid_1949/cgroup.procs: No such file or directory
,D/ExternalStorage( 3635): After updating volumes, found 1 active roots
,W/ResourcesManager( 3163): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3163): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.

```
