#### Test 56151093b6ab50f_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1601): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1601): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3145): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3145):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3145):   adb logcat -s GAv4
W/GAv4    ( 3145): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3145): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3145): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3145): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2607): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3145): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3145): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  735): Killing 2578:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3145): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AndroidRuntime( 3194): 
D/AndroidRuntime( 3194): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
W/System  ( 3145): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3145): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 3194): CheckJNI is OFF
W/libprocessgroup(  735): failed to open /acct/uid_10069/pid_2578/cgroup.procs: No such file or directory
V/GLSActivity( 1565): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3194): Calling main entry com.android.commands.am.Am
I/ActivityManager(  735): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  735): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3218 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3194): Shutting down VM
V/ActivityManager(  735): Display changed displayId=0
I/WebViewFactory( 3218): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/Icing   ( 1601): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/LibraryLoader( 3218): Time to load native libraries: 2 ms (timestamps 9310-9312)
I/LibraryLoader( 3218): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3218): Binding Chromium to main looper Looper (main, tid 1) {8f752b8}
I/LibraryLoader( 3218): Expected native library version number "",actual native library version number ""
I/chromium( 3218): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3218): Initializing chromium process, singleProcess=true
W/art     ( 3218): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3218): ApplicationContext is null in ApplicationStatus
W/chromium( 3218): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
I/Icing   ( 1601): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1601): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
E/libEGL  ( 3218): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3218): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3218): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/Icing   ( 1601): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2178fcc8:true
W/art     ( 3218): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3218): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3218): CordovaWebView is running on device made by: LGE
W/art     ( 3218): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3218): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3218): Render dirty regions requested: true
D/Atlas   ( 3218): Validating map...
W/chromium( 3218): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3218): Initialized EGL, version 1.4
D/OpenGLRenderer( 3218): Enabling debug mode 0
I/Keyboard.Facilitator( 1080): onFinishInput()
W/BindingManager( 3218): Cannot call determinedVisibility() - never saw a connection for the pid: 3218
W/IInputConnectionWrapper( 3218): showStatusIcon on inactive InputConnection
I/ActivityManager(  735): Displayed com.test.thalitest/.MainActivity: +450ms (total +59s762ms)
D/JsMessageQueue( 3218): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3218): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3218): jxcore cordova android initializing
I/ActivityManager(  735): Killing 2525:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
W/libprocessgroup(  735): failed to open /acct/uid_10045/pid_2525/cgroup.procs: No such file or directory
,W/jxcore-log( 3218): Initializing JXcore engine
W/jxcore-log( 3218): JXcore engine is ready
,W/jxcore-log( 3218): Starting JXcore engine
,W/.test.thalitest( 3218): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8415]" dev="sockfs" ino=8415 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3218): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3097 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3218): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9446]" dev="sockfs" ino=9446 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3218): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19795]" dev="sockfs" ino=19795 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3218): Platform android
W/jxcore-log( 3218): 
W/jxcore-log( 3218): Process ARCH arm
W/jxcore-log( 3218): 
,I/jxcore-log( 3218): JXcore Cordova bridge is ready!
I/jxcore-log( 3218): 
W/jxcore-log( 3218): JXcore engine is started
I/Choreographer( 3218): Skipped 109 frames!  The application may be doing too much work on its main thread.
I/chromium( 3218): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3218): Toggling radios to true
I/jxcore-log( 3218): 
,D/BluetoothAdapter( 3218): enable(): BT is already enabled..!
,D/WifiService(  735): New client listening to asynchronous messages
,D/WifiService(  735): setWifiEnabled: true pid=3218, uid=10270
E/WifiService(  735): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3218): Radios toggled
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): My device name is: LGE-Nexus 5
I/jxcore-log( 3218): 
,I/wpa_supplicant( 1041): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  735): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  735): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1565): Read error: ssl=0xb3b2ae00: I/O error during system call, Connection timed out
V/NativeCrypto( 1565): SSL shutdown failed: ssl=0xb3b2ae00: I/O error during system call, Broken pipe
,D/ConnectivityService(  735): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  735): Start Disconnecting Watchdog 1
,E/native  (  735): do suspend true
,I/wpa_supplicant( 1041): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/CommandListener(  180): Clearing all IP addresses on wlan0
D/ConnectivityService(  735): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  735): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  735): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524292
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1601): CM callback handler got msg 524292
D/ConnectivityService(  735): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Disconnected - quitting
,D/TelephonyNetworkFactory( 1215): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  735): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiNetworkAgent(  735): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant( 1041): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1041): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1041): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1041): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  735): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
,E/WifiStateMachine(  735): Start Dhcp Watchdog 2
,E/native  (  735): do suspend false
,E/WifiStateMachine(  735): scanCount==0 - aborting
,I/dhcpcd  ( 3305): version 5.5.6 starting
,E/dhcpcd  ( 3305): get_duid: Read-only file system
,I/dhcpcd  ( 3305): wlan0: rebinding lease of 192.168.1.114
,I/jxcore-log( 3218): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3218): 
,I/jxcore-log( 3218): Test app app.js loaded
I/jxcore-log( 3218): 
,I/Choreographer( 3218): Skipped 189 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3218): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  735): MasterInitialState.processMessage what=3
D/Tethering(  735): MasterInitialState.processMessage what=3
,I/dhcpcd  ( 3305): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,V/MusicLeanback( 2715): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/dhcpcd  ( 3305): wlan0: leased 192.168.1.114 for 86400 seconds
,I/SystemUpdateService( 1601): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1601): onCreate
D/SystemUpdateService( 1601): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/iu.Environment( 1601): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1601): num queued entries: 0
,E/GpsLocationProvider(  735): No APN found to select.
,I/iu.UploadsManager( 1601): num updated entries: 0
,I/iu.SyncManager( 1601): NEXT; no task
,E/GpsLocationProvider(  735): No APN found to select.
,I/SystemUpdateService( 1601): active receiver: enabled
,I/SystemUpdateService( 1601): showing system update notification
,I/Babel   ( 1893): connection state changed from CONNECTED to DISCONNECTED
,I/ValidateNoPeople(  735): skipping global notification
,I/ActivityManager(  735): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3338 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/SystemUpdateService( 1601): retry (wakeup: false) in 3599960 ms
,D/SystemUpdateService( 1601): onDestroy
,E/native  (  735): do suspend true
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  735): Adding iface wlan0 to network 101
,E/WifiStateMachine(  735): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  735): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  735): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  735): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  735): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  735): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  735): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  735): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/CSLegacyTypeTracker(  735): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  735): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
I/GAv4    ( 3338): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3338):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3338):   adb logcat -s GAv4
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1601): CM callback handler got msg 524290
,D/Nat464Xlat(  735): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  735): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1601): CM callback handler got msg 524295
,W/GAv4    ( 3338): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3338): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3338): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 18 Jan 2016 07:35:02 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453102502262], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453102502242]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Validated
,D/ConnectivityService(  735): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1601): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1215): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WebViewFactory( 3338): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3338): Time to load native libraries: 1 ms (timestamps 5313-5314)
I/LibraryLoader( 3338): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3338): Binding Chromium to main looper Looper (main, tid 1) {3bc9b5ea}
,I/LibraryLoader( 3338): Expected native library version number "",actual native library version number ""
I/chromium( 3338): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3338): Initializing chromium process, singleProcess=true
,W/art     ( 3338): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3338): ApplicationContext is null in ApplicationStatus
,W/chromium( 3338): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3338): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3338): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3338): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3338): Starting up...
,W/AudioManagerAndroid( 3338): Requires BLUETOOTH permission
,I/ActivityManager(  735): Killing 2691:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10003/pid_2691/cgroup.procs: No such file or directory
,V/MusicLeanback( 2715): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1601): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1601): onCreate
,D/SystemUpdateService( 1601): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1601): active receiver: enabled
,I/iu.Environment( 1601): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1601): num queued entries: 0
I/iu.UploadsManager( 1601): num updated entries: 0
I/iu.SyncManager( 1601): NEXT; no task
,I/SystemUpdateService( 1601): showing system update notification
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1601): retry (wakeup: false) in 3599941 ms
,D/SystemUpdateService( 1601): onDestroy
,I/Babel   ( 1893): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  735): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3218): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3218): BLE advertisement is supported
I/jxcore-log( 3218): 
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2715): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2715): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1601): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1601): onCreate
,D/SystemUpdateService( 1601): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1601): active receiver: enabled
,I/SystemUpdateService( 1601): showing system update notification
,E/GpsLocationProvider(  735): No APN found to select.
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1601): retry (wakeup: false) in 3599976 ms
,D/SystemUpdateService( 1601): onDestroy
,D/Finsky  ( 2607): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2607): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/art     (  735): Explicit concurrent mark sweep GC freed 47507(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.389ms total 91.858ms
,V/GLSActivity( 1565): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1565): Vacuum at: now=1453102512836 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1080): run()
I/Keyboard.Facilitator( 1080): flushDynamicLanguageModels()
,I/ConfigService( 1565): onCreate
,I/ConfigService( 1565): onDestroy
,I/ClearcutLoggerApiImpl( 1565): disconnect managed GoogleApiClient
,I/jxcore-log( 3218): --= Surplus to requirements =--
I/jxcore-log( 3218): 
I/jxcore-log( 3218): ****TEST TOOK:  ms ****
I/jxcore-log( 3218): 
I/jxcore-log( 3218): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3218): 
,D/AndroidRuntime( 3522): 
D/AndroidRuntime( 3522): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3522): CheckJNI is OFF
,D/AndroidRuntime( 3522): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  735): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  735): Killing 3218:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  735): WIN DEATH: Window{17c927f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  735): Client connection lost with reason: 4
,W/PackageSettings(  735): Skipping PackageSetting{14dd61cc com.example.hello/10278} due to missing metadata
,I/ActivityManager(  735):   Force finishing activity ActivityRecord{3c57c42d u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  735): Spurious death for ProcessRecord{302950a6 3218:com.test.thalitest/u0a270}, curProc for 3218: null
I/ActivityManager(  735): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1601): Explicit concurrent mark sweep GC freed 33028(2MB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 22MB/30MB, paused 461us total 37.033ms
,I/Keyboard.Facilitator( 1080): resetDictionaries() : en_US
,I/InputReader(  735): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1565): Ignoring removeGeofence because network location is disabled.
,I/art     ( 1261): Explicit concurrent mark sweep GC freed 3912(292KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 452us total 31.568ms
,I/Keyboard.Facilitator.DecoderInitializer( 1080): run()
,I/Decoder ( 1080): createOrResetDecoder
,I/art     ( 1410): Explicit concurrent mark sweep GC freed 12771(909KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 316us total 53.125ms
,D/VoicemailCleanupService( 1325): Cleaning up data for package: com.test.thalitest
,I/art     (  735): Explicit concurrent mark sweep GC freed 15619(977KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.751ms total 71.135ms
,I/art     (  735): WaitForGcToComplete blocked for 17.656ms for cause Explicit
,I/UpdateIcingCorporaServi( 1410): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/Adreno-EGL(  949): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  949): Initialized EGL, version 1.4
,W/Launcher( 1261): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1ed27891 new=com.google.android.velvet.VelvetApplication@1ed27891
,D/OpenGLRenderer(  949): Enabling debug mode 0
,I/ActivityManager(  735): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3562 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ConfigService( 1565): onCreate
,D/BackupManagerService(  735): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  735): Receieved: android.intent.action.PACKAGE_REMOVED
,W/InputMethodManagerService(  735): Got RemoteException sending setActive(false) notification to pid 3218 uid 10270
,D/TaskPersister(  735): removeObsoleteFile: deleting file=216_task.xml
,I/Keyboard.Facilitator( 1080): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1080): run()
,I/UpdateIcingCorporaServi( 1410): UpdateCorporaTask done [took 136 ms] updated apps [took 136 ms] 
,W/ContextImpl( 3562): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1080): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1080): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1080): run() : Loading LM = contacts
,I/art     (  735): Explicit concurrent mark sweep GC freed 6833(349KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.804ms total 167.665ms
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1080): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1080): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1080): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1080): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1080): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1080): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1080): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1080): run()
I/StatsUtilsManager( 1080): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1080): shouldRecordStats() = Too Soon
D/PackageBroadcastService( 1601): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1601): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1601): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1601): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1601): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1601): Module APK com.google.android.play.games already loaded
,I/Keyboard.Facilitator( 1080): onFinishInput()
,W/IInputConnectionWrapper( 1261): showStatusIcon on inactive InputConnection
E/NetworkScheduler.SchedulerReceiver( 1565): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1565): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1601): Removing dialog suppression flag for package com.test.thalitest
,I/Launcher( 1261): Deferring update until onResume
,W/ResourcesManager( 1261): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1601): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1601): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1601): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1601): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/ResourcesManager( 1261): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/gH_CompatibleDatabase( 1601): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1601): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1601): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1601): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1601): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1601): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1601): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1601): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1601): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/Launcher( 1261): Deferring update until onResume
,I/ActivityManager(  735): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3595 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/GMPM-SVC( 1601): App measurement is starting up, version: 8489
I/GMPM-SVC( 1601): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/BaseAppContext( 1601): Using Auth Proxy for data requests.
,W/BaseAppContext( 1601): Using Auth Proxy for data requests.
,I/ActivityManager(  735): Killing 2670:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  735): Client connection lost with reason: 4
,D/AndroidRuntime( 3522): Shutting down VM
,W/libprocessgroup(  735): failed to open /acct/uid_1000/pid_2670/cgroup.procs: No such file or directory
,I/Icing   ( 1601): doRemovePackageData com.test.thalitest
,E/SQLiteLog( 1601): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/FileUtils( 1601): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/Icing   ( 1601): Failed to open Apps corpus file.
,E/SQLiteDatabase( 1601): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 1601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1601): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2307)
E/SQLiteDatabase( 1601): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 1601): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 1601): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 1601): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 1601): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 1601): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 1601): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 1601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 1601): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
,E/GMPM-SVC( 1601): Opening the database failed, dropping and recreating it
,E/Icing   ( 1601): Failed to open Apps corpus file.
,E/SQLiteDatabase( 1601): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 1601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1601): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
E/SQLiteDatabase( 1601): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 1601): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 1601): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 1601): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 1601): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 1601): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 1601): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 1601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 1601): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
,E/SharedPreferencesImpl( 1601): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak

```
