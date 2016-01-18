#### Test 5635717154d1b6f_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3181): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3181):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3181):   adb logcat -s GAv4
W/GAv4    ( 3181): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3181): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3181): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3181): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2577): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3181): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3181): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  734): Killing 2539:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/libprocessgroup(  734): failed to open /acct/uid_10069/pid_2539/cgroup.procs: No such file or directory
V/JNIHelp ( 3181): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3181): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3181): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1616): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1616): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1616): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1616): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3251): 
D/AndroidRuntime( 3251): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3251): CheckJNI is OFF
D/AndroidRuntime( 3251): Calling main entry com.android.commands.am.Am
I/ActivityManager(  734): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  734): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3272 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3251): Shutting down VM
I/ActivityManager(  734): Killing 2494:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
W/libprocessgroup(  734): failed to open /acct/uid_10045/pid_2494/cgroup.procs: No such file or directory
V/ActivityManager(  734): Display changed displayId=0
I/WebViewFactory( 3272): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3272): Time to load native libraries: 2 ms (timestamps 1089-1091)
I/LibraryLoader( 3272): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3272): Binding Chromium to main looper Looper (main, tid 1) {34db2426}
I/LibraryLoader( 3272): Expected native library version number "",actual native library version number ""
I/chromium( 3272): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3272): Initializing chromium process, singleProcess=true
W/art     ( 3272): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3272): ApplicationContext is null in ApplicationStatus
,W/chromium( 3272): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3272): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3272): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3272): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a42f85c:true
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
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  734): Displayed com.test.thalitest/.MainActivity: +431ms (total +60s466ms)
,I/Keyboard.Facilitator( 1064): onFinishInput()
W/IInputConnectionWrapper( 3272): showStatusIcon on inactive InputConnection
,W/BindingManager( 3272): Cannot call determinedVisibility() - never saw a connection for the pid: 3272
,D/JsMessageQueue( 3272): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3272): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1405526272
D/JX-Cordova( 3272): jxcore cordova android initializing
,W/jxcore-log( 3272): Initializing JXcore engine
W/jxcore-log( 3272): JXcore engine is ready
,W/jxcore-log( 3272): Starting JXcore engine
,W/.test.thalitest( 3272): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9489]" dev="sockfs" ino=9489 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3272): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3272): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8446]" dev="sockfs" ino=8446 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3272): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19410]" dev="sockfs" ino=19410 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3272): Platform android
W/jxcore-log( 3272): 
,W/jxcore-log( 3272): Process ARCH arm
W/jxcore-log( 3272): 
,I/jxcore-log( 3272): JXcore Cordova bridge is ready!
I/jxcore-log( 3272): 
,W/jxcore-log( 3272): JXcore engine is started
,I/Choreographer( 3272): Skipped 123 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3272): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3272): Toggling radios to true
I/jxcore-log( 3272): 
,D/BluetoothAdapter( 3272): enable(): BT is already enabled..!
,D/WifiService(  734): New client listening to asynchronous messages
D/WifiService(  734): setWifiEnabled: true pid=3272, uid=10270
E/WifiService(  734): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3272): Radios toggled
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): My device name is: LGE-Nexus 5
I/jxcore-log( 3272): 
,I/wpa_supplicant(  988): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  734): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  734): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1564): Read error: ssl=0x9b053e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1564): SSL shutdown failed: ssl=0x9b053e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  734): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): ValidatedState{ when=-8ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=-8ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  734): Start Disconnecting Watchdog 1
I/wpa_supplicant(  988): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  734): do suspend true
,W/ProcessCpuTracker(  734): Skipping unknown process pid 3339
,D/CommandListener(  181): Clearing all IP addresses on wlan0
D/ConnectivityService(  734): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524292
D/Nat464Xlat(  734): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  734): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1616): CM callback handler got msg 524292
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  734): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1232): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  734): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Disconnected - quitting
,D/WifiNetworkAgent(  734): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  988): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  988): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  988): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  988): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  734): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  734): Start Dhcp Watchdog 2
,E/native  (  734): do suspend false
,E/WifiStateMachine(  734): scanCount==0 - aborting
,I/dhcpcd  ( 3374): version 5.5.6 starting
,E/dhcpcd  ( 3374): get_duid: Read-only file system
,I/dhcpcd  ( 3374): wlan0: rebinding lease of 192.168.1.114
,I/jxcore-log( 3272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3272): 
,I/jxcore-log( 3272): Test app app.js loaded
I/jxcore-log( 3272): 
,I/Choreographer( 3272): Skipped 191 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3272): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/dhcpcd  ( 3374): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3374): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  734): MasterInitialState.processMessage what=3
D/Tethering(  734): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2688): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1616): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1616): onCreate
,D/SystemUpdateService( 1616): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1616): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1616): num queued entries: 0
,I/SystemUpdateService( 1616): active receiver: enabled
,I/SystemUpdateService( 1616): showing system update notification
I/ValidateNoPeople(  734): skipping global notification
,I/iu.UploadsManager( 1616): num updated entries: 0
,I/iu.SyncManager( 1616): NEXT; no task
,V/SystemUpdateService( 1616): retry (wakeup: false) in 3599984 ms
,I/Babel   ( 1886): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  734): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3406 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1616): onDestroy
,E/GpsLocationProvider(  734): No APN found to select.
,E/GpsLocationProvider(  734): No APN found to select.
,E/native  (  734): do suspend true
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  734): Adding iface wlan0 to network 101
,E/WifiStateMachine(  734): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  734): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  734): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  734): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  734): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  734): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  734): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  734): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  734): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  734): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  734): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1616): CM callback handler got msg 524290
,D/Nat464Xlat(  734): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  734): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1616): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524295
,I/GAv4    ( 3406): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3406):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3406):   adb logcat -s GAv4
,W/GAv4    ( 3406): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3406): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3406): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 18 Jan 2016 15:55:24 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453132524894], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453132524880]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Validated
,D/ConnectivityService(  734): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  734): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1616): CM callback handler got msg 524290
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1232): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WebViewFactory( 3406): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3406): Time to load native libraries: 2 ms (timestamps 7353-7355)
I/LibraryLoader( 3406): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3406): Binding Chromium to main looper Looper (main, tid 1) {9b8b028}
,I/LibraryLoader( 3406): Expected native library version number "",actual native library version number ""
,I/chromium( 3406): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3406): Initializing chromium process, singleProcess=true
,W/art     ( 3406): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3406): ApplicationContext is null in ApplicationStatus
,W/chromium( 3406): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3406): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3406): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3406): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3406): Starting up...
,W/AudioManagerAndroid( 3406): Requires BLUETOOTH permission
,I/ActivityManager(  734): Killing 2661:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10003/pid_2661/cgroup.procs: No such file or directory
,V/MusicLeanback( 2688): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1616): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1616): onCreate
,D/SystemUpdateService( 1616): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1616): active receiver: enabled
,I/iu.Environment( 1616): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1616): num queued entries: 0
,I/iu.UploadsManager( 1616): num updated entries: 0
,I/iu.SyncManager( 1616): NEXT; no task
,I/SystemUpdateService( 1616): showing system update notification
,I/ValidateNoPeople(  734): skipping global notification
,V/SystemUpdateService( 1616): retry (wakeup: false) in 3599932 ms
,D/SystemUpdateService( 1616): onDestroy
,I/Babel   ( 1886): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  734): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3272): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3272): BLE advertisement is supported
I/jxcore-log( 3272): 
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  734): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2688): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2688): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1616): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1616): onCreate
,D/SystemUpdateService( 1616): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1616): active receiver: enabled
,I/SystemUpdateService( 1616): showing system update notification
,I/ValidateNoPeople(  734): skipping global notification
,V/SystemUpdateService( 1616): retry (wakeup: false) in 3599981 ms
,I/art     (  734): Explicit concurrent mark sweep GC freed 46681(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 919us total 73.716ms
D/SystemUpdateService( 1616): onDestroy
,E/GpsLocationProvider(  734): No APN found to select.
,D/Finsky  ( 2577): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2577): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1564): Vacuum at: now=1453132534629 tag=VacuumService
,I/GoogleURLConnFactory( 1564): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1564): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,W/PhenotypeConfigurator( 1564): Server returned 404
,I/Keyboard.Facilitator.LanguageModelFlusher( 1064): run()
I/Keyboard.Facilitator( 1064): flushDynamicLanguageModels()
,I/ConfigService( 1564): onCreate
,I/ConfigService( 1564): onDestroy
,I/ClearcutLoggerApiImpl( 1564): disconnect managed GoogleApiClient
,I/jxcore-log( 3272): --= Surplus to requirements =--
I/jxcore-log( 3272): 
I/jxcore-log( 3272): ****TEST TOOK:  ms ****
I/jxcore-log( 3272): 
I/jxcore-log( 3272): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3272): 
,D/AndroidRuntime( 3614): 
D/AndroidRuntime( 3614): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3614): CheckJNI is OFF
,D/AndroidRuntime( 3614): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  734): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  734): Killing 3272:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  734): WIN DEATH: Window{34ce83d5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  734): Client connection lost with reason: 4
,W/PackageSettings(  734): Skipping PackageSetting{3600b85a com.example.hello/10278} due to missing metadata
,I/ActivityManager(  734):   Force finishing activity ActivityRecord{3b7b7d71 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  734): Spurious death for ProcessRecord{3a5e7a75 3272:com.test.thalitest/u0a270}, curProc for 3272: null
,I/ActivityManager(  734): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1266): Explicit concurrent mark sweep GC freed 3943(293KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 705us total 16.570ms
,I/art     ( 1395): Explicit concurrent mark sweep GC freed 13025(935KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 327us total 31.982ms
,I/InputReader(  734): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1064): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1564): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator.DecoderInitializer( 1064): run()
,I/Decoder ( 1064): createOrResetDecoder
,I/Adreno-EGL(  947): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  947): Initialized EGL, version 1.4
,D/VoicemailCleanupService( 2819): Cleaning up data for package: com.test.thalitest
,I/ConfigService( 1564): onCreate
,D/OpenGLRenderer(  947): Enabling debug mode 0
,I/art     ( 1616): Explicit concurrent mark sweep GC freed 3350(133KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 22MB/30MB, paused 716us total 105.610ms
,I/UpdateIcingCorporaServi( 1395): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1266): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@21b62867 new=com.google.android.velvet.VelvetApplication@21b62867
,I/art     (  734): Explicit concurrent mark sweep GC freed 19841(1147KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 2.481ms total 88.106ms
,I/art     (  734): WaitForGcToComplete blocked for 74.285ms for cause Explicit
,I/ActivityManager(  734): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3655 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,W/InputMethodManagerService(  734): Got RemoteException sending setActive(false) notification to pid 3272 uid 10270
,I/Keyboard.Facilitator( 1064): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1064): run()
,D/BackupManagerService(  734): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  734): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  734): removeObsoleteFile: deleting file=216_task.xml
,W/ContextImpl( 3655): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1064): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run()
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
,D/PackageBroadcastService( 1616): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1616): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1616): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1616): Module APK com.google.android.play.games already loaded
,I/art     (  734): Explicit concurrent mark sweep GC freed 5595(298KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.641ms total 132.973ms
,I/Keyboard.Facilitator( 1064): onFinishInput()
,D/ChimeraCfgMgr( 1616): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1616): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1564): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1564): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/IInputConnectionWrapper( 1266): showStatusIcon on inactive InputConnection
,I/LocationSettingsChecker( 1616): Removing dialog suppression flag for package com.test.thalitest
,I/ContactLoggerTask( 1395): canRun() : Disabled
,I/UpdateIcingCorporaServi( 1395): UpdateCorporaTask done [took 180 ms] updated apps [took 127 ms] updated contacts [took 53 ms]
,I/ActivityManager(  734): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3687 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,D/gH_CompatibleDatabase( 1616): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1616): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1616): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1616): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1616): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1616): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1616): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1616): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1616): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1616): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1616): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1616): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1616): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/Launcher( 1266): Deferring update until onResume
,W/ResourcesManager( 1266): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GMPM-SVC( 1616): App measurement is starting up, version: 8489
,I/GMPM-SVC( 1616): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1616): Using Auth Proxy for data requests.
,W/ResourcesManager( 1266): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/BaseAppContext( 1616): Using Auth Proxy for data requests.
,I/ActivityManager(  734): Killing 2627:com.android.settings/1000 (adj 15): empty #17
,I/Launcher( 1266): Deferring update until onResume
,D/WifiService(  734): Client connection lost with reason: 4
,D/AndroidRuntime( 3614): Shutting down VM
,W/libprocessgroup(  734): failed to open /acct/uid_1000/pid_2627/cgroup.procs: No such file or directory
,I/Icing   ( 1616): doRemovePackageData com.test.thalitest
,I/ActivityManager(  734): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3730 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  734): Killing 2513:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10070/pid_2513/cgroup.procs: No such file or directory
,I/ActivityManager(  734): Killing 1946:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10031/pid_1946/cgroup.procs: No such file or directory
,D/ExternalStorage( 3730): After updating volumes, found 1 active roots
,W/ResourcesManager( 3181): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3181): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3687): Update found 7 roots in 313ms
,D/Documents( 3687): Update found 7 roots in 152ms

```
